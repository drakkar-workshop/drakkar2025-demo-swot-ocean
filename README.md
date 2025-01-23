# drakkar2025-demo-swot-ocean
Material for the on-site activity devoted to SWOT satellite data during https://drakkar2025.sciencesconf.org

## Jupyter Notebooks

The repository contains two notebooks:

1. **`SWOT_movies_CalVal.ipynb`**  
   Demonstrates how to read SWOT L3 data from an S3 bucket and how to create a video from the SWOT data swaths over the crossover regions.

3. **`Wavenumber_spectra_CalVal.ipynb`**  
   Demonstrates the use of the `widetrax` library to compute Wavenumber spectra during the CalVal period and in your region of Interest.

## Installing packages

Before running the notebooks, you’ll need to install a couple of libraries:

1. **Install `pyinterp`**  
   `pyinterp` is required for the functionality of the notebooks. Without it, other libraries may not work properly.  
   To install `pyinterp`, follow the detailed steps outlined in the [official documentation](https://cnes.github.io/pangeo-pyinterp/setup.html).  

2. **Install `widetrax`**  
   Once `pyinterp` is installed, you can proceed to install `widetrax` using `pip`. Simply follow the instructions provided [here](https://widetrax.readthedocs.io/en/latest/overview.html#installation).

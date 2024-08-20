# Plotting GOES True Color Data stored in AWS
## Written By Jared Rennie

This tutorial uses python to download and plot TrueColor data from the GOES-R series. Derived from this notebook: https://github.com/blaylockbk/pyBKB_v3/blob/master/BB_GOES/mapping_GOES16_TrueColor.ipynb

### What You Need

First off, the entire codebase works in Python... sort of. 

You will need the following programs installed: 
- Python
- s3fs | numpy | xarray | matplotlib | cartopy | h5netcdf | h5py 
    
The "easiest" way is to install these is by installing <a href='https://www.anaconda.com/' target="_blank">Anaconda</a>, and then applying <a href='https://conda-forge.org/' target="_blank">conda-forge</a>. Afterward, then you can install the above packages. 

### Launch right now with binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jjrennie/goes-truecolor/HEAD?labpath=GOES_Plot_Tutorial.ipynb)

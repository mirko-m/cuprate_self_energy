# cuprate_self_energy

This repository contains contour plots of the self-energy of a single hole doped into a CuO2 layer. Since this is an ongoing project I cannot upload the code that was used to generate the data, but if you are interested please feel free to contact me.

The repository contains:
* Data files containing:
  + The spectal function
  + The real part of the self-energy
  + The imaginary part of the self-energy
  + The momentum values
  + the frequency (omega) values.
* A jupyter notebook with:
  + A description of the model
  + Code to load and plot the data using Python
  + Plots of the data
  
## Format of the data files
The name of the data files indicates which type of data is stored (self-energy, spectral function (spwt), momentum (kxky) or frequency (omega)). Other parameters are also part of the filename. For a complete desciption refer to the jupyter notebook plot_self_energy.ipynb . For the self-energy and spectral function the frequency (omega) changes accross columns and the momentum changes across rows.

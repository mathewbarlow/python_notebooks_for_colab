This repository contains python notebooks made for Google Colab. 

If you have the required packages installed on your own system, you can comment out or delete the '!pip install ...' lines in these notebooks and they should run without further modification.

<b> shallow_water_model_shtns.ipynb </b> 

This google colab notebook sets up and runs a global shallow water model. The model uses the spectral trasnform approached, based on the SHTns package from Nathanaël Schaeffer: https://bitbucket.org/nschaeff/shtns/src/master/. The model is set to run the non-linear barotropically unstable shallow water test case, based on the example provided by Jeffrey Whitaker: https://gist.github.com/jswhit/3845307. The work of Nathanaël and Jeff, the availability of Google Colab, and support from NOAA MAPP NA20OAR4310424 is gratefully acknowledged.

<img align="left" width="600" height="170" src="images/swe_output.png">

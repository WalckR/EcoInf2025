# This folder contains data and scripts for analyses and figures presented in the manuscript "High-resolution mapping of peatland CO2 fluxes using drone multispectral images"


Manuscript reference: Walcker, R., Le Lay, C., Gandois, L., Elger, A., Jassey V. (in revision) High-resolution mapping of peatland CO2 fluxes using drone multispectral images. Ecological Informatics.

Analysis presented here have been performed using the Jupyter notebook programed in Python language.

!! Please note: this repository contains the scripts used to run the actual analysis presented in the manuscript. Since the time of publication, some aspects may have changed and thus some of these scripts could create errors that did not originally occur.
!! Please note: figures 1, 2, 3 and 4 of the article are not provided here because generated mannually using ESRI ArcGIS Pro and Microsoft PowerPoint. 


# Scripts: 

1- Code to display figure 5: STEP01_Fig5.ipynb
  
2- Code to display figure 6: STEP02_Fig6.ipynb
  
3- Code to display figure 7: STEP03_Fig7.ipynb
  
4- Code to generate models: STEP04_Modelling.ipynb
  
5- Code to perform feature importance analysis: STEP05_FeatureImportance.ipynb

6- Code to display figure 8: STEP06_Fig8.ipynb

7- Code to generate maps: STEP07_Mapping_NEE_ER_GEP.ipynb

8- Code to display figure 9: STEP08_Fig9.ipynb

9- Code to display figure 10: STEP09_Fig10.ipynb

# Data:

1- CO2_Plots_L93: shapefile (ESRI) to locate places were CO2 flux measurments were made. SCR is EPSG:2154 (Lambert 93)

2- Spectral_Quadrats_L93: shapefile (ESRI) to locate places were image reflectance were averaged next to CO2 plots. SCR is EPSG:2154 (Lambert 93)

3- UAV_signature_XXXX: csv file containing reflectance data

4- FIELD_FLUX.xlsx: xlsx file containing CO2 flux data

5- Dataset: csv file containing flux and reflectance data

6- Dataset_with_indices: csv file containing flux, reflectance data and vegetation indices

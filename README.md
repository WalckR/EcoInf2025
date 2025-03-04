# This folder contains data and scripts for analyses and figures presented in the manuscript "High-resolution mapping of peatland CO2 fluxes using drone multispectral images"


Manuscript reference: 1.	Walcker, R., Le Lay, C., Gandois, L., Elger, A., Jassey, V. E. J. (2025) High-resolution mapping of peatland CO2 fluxes using drone multispectral images. Ecological Informatics 86: 103060. https://doi.org/10.1016/j.ecoinf.2025.103060

Analysis presented here have been performed using the Jupyter notebook programed in Python language.

!! Please note: this repository contains the scripts used to run the actual analysis presented in the manuscript. Since the time of publication, some aspects may have changed and thus some of these scripts could create errors that did not originally occur.

!! Please note: figures 1, 2, 3 and 4 of the article are not provided here because generated mannually using ESRI ArcGIS Pro and Microsoft PowerPoint. 

# Data:

1- CO2_Plots_L93: shapefile (ESRI) to locate places were CO2 flux measurments were made. SCR is EPSG:2154 (Lambert 93)

2- Spectral_Quadrats_L93: shapefile (ESRI) to locate places were image reflectance were averaged next to CO2 plots. SCR is EPSG:2154 (Lambert 93)

3- FIELD_XXXX: csv files containing CO2 flux data. Needed for STEP01_Fig5.ipynb

4- UAV_signature_XXXX: csv files containing reflectance data. Needed for STEP02_Fig6.ipynb

5- Dataset: csv and xsl files containing all flux and reflectance data

6- Dataset_with_indices: csv file containing flux, reflectance data and vegetation indices. Produced by STEP03_Fig7.ipynb and needed for STEP04_Modelling.ipynb, STEP05_FeatureImportance.ipynb and STEP06_Fig8.ipynb

# Drone images: 

Drone images are made availlable on OpenAerialMap (https://map.openaerialmap.org), a set of tools for searching, sharing, and using openly licensed satellite and UAV imagery. 

!! Please note: following OpenAerialMap requirements, image formats have been changed from 64-bit float to 8-bit unsigned integer. RGB bands are provided as true-color composite and RE and NIR bands as single bands. Calculations based on these reformatted images may not exactly correspond to those presented in the article. Contact the corresponding author if necessary. 

1- Images acquired on May the 17th:

2- Images acquired on June the 15th:

3- Images acquired on July the 10th:

4-  Images acquired on October the 5th:

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

HEAD
Project for the course SDS210 at UZH



**Title**: "Detection of Burned Areas after the 2023 Lahaina Wildfires Using Satellite Data"



**Description**: The goal of the project was to set up an algorithm that can detect burned areas after a wildfire. The study area was Lahaina on Hawaii, which was heavily affected by wildfires in 2023. Two different approaches were compared. One approach is based on the difference of band ratios (NBR and NDVI) of Sentinel-2 bands. The other approach calculated difference metrics (Euclidean distance and cosine similarity) to detect major changes over 64 spectral bands.



**Data sources**: The preprocessed data were provided over the following link: https://drive.google.com/drive/folders/1cnFhMAxAHG-53SUhneyHhJmdYA7DOddb



* Original data Sentinel-2 data can be accessed through the Copernicus browser (https://browser.dataspace.copernicus.eu/)
* Original AlphaEarth Embeddings can be accessed through Google Earth Engine (https://code.earthengine.google.com/)



**Requirements:** Python 3.14 and the packages listed in the environment.yml



**Execution Order:** If the requirements are met, the folder structure is the same as on GitHub and the raw data is saved in the corresponding folder, the main.ipynb can be run directly.


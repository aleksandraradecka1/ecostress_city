## Viewing the surface temperature of a city 🌡️🛰️🏙️

![](maps/my_gif.gif)

#### Goal: 
to create a gif that displays the land surface temperature (LST) for a selected part of a city, alongside an optical image obtained within the same time frame

#### Data:
- ECOSTRESS surface temperature (product: ECO2LSTE.001)
- ECOSTRESS surface temperature statistics 
- ECOSTRESS cloud mask (product: ECO2CLD.001)
- ECOSTRESS cloud mask lookup
- Sentinel-2 L1C image 

#### Example area & time: 
Bialystok's (Poland) city, year of 2022

#### Processing steps:
1. selecting the area and time to be analyzed   
2. downloading Sentinel-2 data using API
3. downloading ECOSTRESS data using API
4. transforming the data to a common coordinate system
5. stacking and clipping the data to a common spatial extent
6. calculating the Surface Temperature 
7. familiarizing with the LST statistics
8. converting cloud raster masks into polygon features
9. creating an animated gif

#### Sources:
- geojson drawing page: https://geojson.io/
- ECOSTRESS page: https://ecostress.jpl.nasa.gov/
- ECOSTRESS API: https://appeears.earthdatacloud.nasa.gov/api/?python#introduction
- Creodias platform: https://creodias.eu/

Prepared by: Aleksandra Radecka <br/>
e-mail: aleksandraradecka@protonmail.com
LinkedIn: https://www.linkedin.com/in/aleksandraradecka/

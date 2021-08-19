# Population and Settlements

Global mapping of population is rapidly growing in recent years. They are available at detailed spatial scales. The analysis is based on satellite or other geospatial data layers. Population data are necessary for the analysis of impacts of population growth, monitor population changes, and intervention planning.

## Landscan Global Population Database

The LandScan Global Population Database is developed at the Department of Energy's [Oak Ridge National Laboratory](https://landscan.ornl.gov). The data represents finest resolution global population distribution database available. LandScan is known as a highly practical application in humanitarian affairs because it provides most reliable population distribution model.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Visualized population density on the dashboard  |
| Variable  | Total population  |
| Geographic coverage  | Global  |
| Spatial resolution  | The 30 arc-second cell, or 0.008333333 decimal degrees, represents approximately 1 km2 near the equator  |
| Temporal resolution  | Annual  |
| Format  | ESRI grid format and an ESRI binary raster format  |
| Unit  | The values of the cells are integer population counts representing an average, or ambient, population distribution  |
| Source  | [https://landscan.ornl.gov/landscan-datasets](https://landscan.ornl.gov/landscan-datasets)  |
| Reference  | [https://landscan.ornl.gov/documentation](https://landscan.ornl.gov/documentation)  |

**Symbology**

The threshold and the symbology for the Landscan population density can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| No population  | `#c2c3c6` ![#c2c3c6](https://via.placeholder.com/15/c2c3c6/000000?text=+) | rgb(194, 195, 198)  |
| 1 to 5  | `#fbf6c2` ![#fbf6c2](https://via.placeholder.com/15/fbf6c2/000000?text=+)  | rgb(251, 246, 194)  |
| 6 - 25  | `#f6ef8d` ![#f6ef8d](https://via.placeholder.com/15/f6ef8d/000000?text=+)  | rgb(246, 239, 141)  |
| 26 - 50  | `#f4e957` ![#f4e957](https://via.placeholder.com/15/f4e957/000000?text=+)  | rgb(244, 233, 87)  |
| 51 - 100  | `#eda343` ![#eda343](https://via.placeholder.com/15/eda343/000000?text=+)  | rgb(237, 163, 67)  |
| 101 - 500  | `#e26d38` ![#e26d38](https://via.placeholder.com/15/e26d38/000000?text=+)  | rgb(226, 109, 56)  |
| 501 - 2,500  | `#da3832` ![#da3832](https://via.placeholder.com/15/da3832/000000?text=+)  | rgb(218, 56, 50)  |
| 2,501 - 5,000  | `#b93634` ![#b93634](https://via.placeholder.com/15/b93634/000000?text=+)  | rgb(185, 54, 52)  |
| 5,001 - 130,000  | `#561b1b` ![#561b1b](https://via.placeholder.com/15/561b1b/000000?text=+)  | rgb(86, 27, 27)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EtAMMJWQIXVBtqamXiL2QpQBKGI3fX0kp9a4QIMQRei1xQ?e=tjWv46](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EtAMMJWQIXVBtqamXiL2QpQBKGI3fX0kp9a4QIMQRei1xQ?e=tjWv46)

    For latest data, please check their official website.


## High Resolution Settlement Layer - Facebook

To create high-resolution population maps, Facebook use machine learning techniques to identify buildings from commercially available satellite images. Then work with partners at Columbia University to overlay general population estimates based on publicly available census data and other population statistics. The resulting maps are the most detailed and actionable tools available for aid and research organizations.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | a proxy for impact analysis  |
| Variable  | Total population, Men, Women, Under 5, Youth 15-24, Women of reproductive ages 15-49, Elderly 60+  |
| Geographic coverage  | Global  |
| Spatial resolution  | 30 meter/pixel  |
| Temporal resolution  | n/a (Year estimation is 2019)  |
| Format  | GeoTIFF  |
| Unit  | Population counts at 30m resolution  |
| Source  | [https://data.humdata.org/organization/facebook](https://data.humdata.org/organization/facebook)  |
| Reference  | [https://dataforgood.fb.com/docs/high-resolution-population-density-maps-demographic-estimates-documentation/](https://dataforgood.fb.com/docs/high-resolution-population-density-maps-demographic-estimates-documentation/)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Ej_e_8XWfcdAkMy251QIFhUBMKdd2Koae-h4iuwz7xFaaw?e=dKtl0j](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Ej_e_8XWfcdAkMy251QIFhUBMKdd2Koae-h4iuwz7xFaaw?e=dKtl0j)

    For latest data, please check their official page at Humanitarian Data Exchange (HDX).


## Global Human Settlement Layer - JRC

The Global Human Settlement (GHS) - [http://ghsl.jrc.ec.europa.eu](http://ghsl.jrc.ec.europa.eu) - framework produces global spatial information about the human presence on the planet over time. This in the form of built up maps, population density maps and settlement maps. This information is generated with evidence-based analytics and knowledge using new spatial data mining technologies. The framework uses heterogeneous data including global archives of fine-scale satellite imagery, census data, and volunteered geographic information. The data is processed fully automatically and generates analytics and knowledge reporting objectively and systematically about the presence of population and built-up infrastructures.

The main datasets are offered for download as open and free data. The GHS P2016 suite consists of multitemporal products, that offers an insight into the human presence in the past: 1975, 1990, 2000, and 2014. There are three main type of products: built-up (`GHS-BUILT`), population (`GHS-POP`), city model (`GHS-SMOD`). The grid data are distributed as raster files in `TIF` format. The `ZIP` files contain raster files together with pyramids (i.e., `TIF` and `OVR` files). 

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | a proxy for impact analysis  |
| Variable  | Total population  |
| Geographic coverage  | Global  |
| Spatial resolution  | 250 meter/pixel  |
| Temporal resolution  | 1975, 1990, 2000, 2014, 2016  |
| Format  | GeoTIFF  |
| Unit  | Population counts at 250m resolution  |
| Source  | [https://ghsl.jrc.ec.europa.eu/download.php](https://ghsl.jrc.ec.europa.eu/download.php)  |
| Reference  | [https://ghsl.jrc.ec.europa.eu](https://ghsl.jrc.ec.europa.eu)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EthmQD2P4ttFiwhKESlM-_kBlnEdmyFjq-NgL95N4xdikQ?e=Zp572J](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EthmQD2P4ttFiwhKESlM-_kBlnEdmyFjq-NgL95N4xdikQ?e=Zp572J)

	For latest data, please check their official website.


## World Settlement Footprint

Human settlements are the cause and consequence of most environmental and societal changes on Earth; however, their location and extent is still under debate. We provide here a new `10m` resolution (`0.32 arcsec`) global map of human settlements on Earth for the year 2015, namely the World Settlement Footprint 2015 (WSF2015). 

The raster dataset has been generated by means of an advanced classification system which, for the first time, jointly exploits open-and-free optical and radar satellite imagery. The WSF2015 has been validated against 900,000 samples labelled by crowdsourcing photointerpretation of very high resolution Google Earth imagery and outperforms all other similar existing layers; in particular, it considerably improves the detection of very small settlements in rural regions and better outlines scattered suburban areas. 

The dataset can be used at any scale of observation in support to all applications requiring detailed and accurate information on human presence (e.g., socioeconomic development, population distribution, risks assessment, etc.).

The World Settlement Footprint (WSF) 2015 is a `10m` (`0.32 arcsec`) resolution binary mask outlining the 2015 global settlement extent derived by jointly exploiting multitemporal Sentinel-1 radar and Landsat-8 optical satellite imagery. 

The archive is organized for download in 306 GeoTIFF files (`EPSG:4326` projection, `deflate` compression) each one referring to a portion of `10x10` degree size (`1110x1110km`) whose upper-left and lower-right corner coordinates are specified in the file name [e.g., the tile `WSF2015_v1_EPSG4326_e010_n60_e020_n50.tif` covers the area between (`10E;60N`) and (`20E;50N`)]. 

A virtual mosaic file (i.e., `WSF2015_v1_EPSG4326.vrt`) is also provided which allows visualizing the global product at once on most diffused GIS platforms (e.g., ArcGIS, QGIS, MapInfo). Settlements are associated with value `255`; all other pixels are associated with value `0`.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | a proxy for impact analysis  |
| Variable  | Settlement areas  |
| Geographic coverage  | Global  |
| Spatial resolution  | 10, 100, 250, 500 m/pixel, 1 km and 10 km/pixel  |
| Temporal resolution  | 2015  |
| Format  | GeoTIFF  |
| Unit  | Settelement areas at xx resolution  |
| Source  | [https://www.nature.com/articles/s41597-020-00580-5](https://www.nature.com/articles/s41597-020-00580-5)  |
| Reference  | [https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-9628/16557_read-40454/](https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-9628/16557_read-40454/)  |

Official Download Link: 

WSF2015 can be downloaded from a dedicated repository

- [10m](https://figshare.com/articles/dataset/World_Settlement_Footprint_WSF_2015/10048412)
- [100m](https://figshare.com/articles/dataset/World_Settlement_Footprint_WSF_2015_-_Percent_Settlement_Area_-_100m/100484750)
- [250m](https://figshare.com/articles/dataset/World_Settlement_Footprint_WSF_2015_-_Percent_Settlement_Area_-_250m/10048514)
- [500m](https://figshare.com/articles/dataset/World_Settlement_Footprint_WSF_2015_-_Percent_Settlement_Area_-_500m/10048520)
- [1km](https://figshare.com/articles/dataset/World_Settlement_Footprint_WSF_2015_-_Percent_Settlement_Area_-_1km/10048535)
- [10km](https://figshare.com/articles/dataset/World_Settlement_Footprint_WSF_2015_-_Percent_Settlement_Area_-_10km/10048541)

**Downloads**

!!! info "**Location**"

    Sharepoint: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EmwVa31ReQtEmn2Tthv8kY4BcD2Ip2QqeWMa_axEvdgqRQ?e=4aI8wk](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EmwVa31ReQtEmn2Tthv8kY4BcD2Ip2QqeWMa_axEvdgqRQ?e=4aI8wk)

    For latest data, please check their official download link above.

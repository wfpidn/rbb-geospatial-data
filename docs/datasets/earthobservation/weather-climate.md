# Weather and Climate

The climate are varies by location and by time of year. Dekad rainfall, daily rainfall forecast and monthly temperature are a few of the many datasets found under our climate section.

## Rainfall

Many research institutions are producing global satellite precipitation estimate, and mostly available for public. Most notably products are CHIRPS, GPM IMERG, and NOAA GEFS. 

### CHIRPS

Climate Hazards Group InfraRed Precipitation with Station data (CHIRPS) from Climate Hazard Center (CHC), Department of Geography, University of California Santa Barbara - [https://www.chc.ucsb.edu/data/chirps](https://www.chc.ucsb.edu/data/chirps) is a 35+ year quasi-global rainfall data set. Spanning 50°S-50°N (and all longitudes) and ranging from 1981 to near-present, CHIRPS incorporates CHC's in-house climatology, CHPclim, 0.05° resolution satellite imagery, and in-situ station data to create gridded rainfall time series for trend analysis and seasonal drought monitoring. 

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays dekad and monthly rainfall data  |
| Variable  | Total rainfall  |
| Geographic coverage  | Global 50N-50S, 180W-180E |
| Spatial resolution  | 0.05 degree ~ 5.6 km at equator  |
| Temporal resolution  | daily, pentad, dekad, monthly, 2-monthly, 3-monthly and annual  |
| Format  | GeoTIFF, BIL and NetCDF  |
| Unit  | Total mm for given time step, mm/pentad, mm/month, etc.  |
| Source  | [https://data.chc.ucsb.edu/products/CHIRPS-2.0/](https://data.chc.ucsb.edu/products/CHIRPS-2.0/)  |
| Reference  | [https://wiki.chc.ucsb.edu/CHIRPS_FAQ](https://wiki.chc.ucsb.edu/CHIRPS_FAQ)  |

**Symbology**

The threshold and the symbology for the `dekad` rainfall in milimeters can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| No Rain  | `#e1e1e1` ![#e1e1e1](https://via.placeholder.com/15/e1e1e1/000000?text=+) | rgb(225, 225, 225)  |
| 1 to 3  | `#ffffff` ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)  | rgb(255, 255, 255)  |
| 3 to 10  | `#f9f3d5` ![#f9f3d5](https://via.placeholder.com/15/f9f3d5/000000?text=+)  | rgb(249, 243, 213)  |
| 10 to 20  | `#dce2a8` ![#dce2a8](https://via.placeholder.com/15/dce2a8/000000?text=+)  | rgb(220, 226, 168)  |
| 20 to 30  | `#a8c58d` ![#a8c58d](https://via.placeholder.com/15/a8c58d/000000?text=+)  | rgb(168, 197, 141)  |
| 30 to 40  | `#77a87d` ![#77a87d](https://via.placeholder.com/15/77a87d/000000?text=+)  | rgb(119, 168, 125)  |
| 40 to 60  | `#ace8f8` ![#ace8f8](https://via.placeholder.com/15/ace8f8/000000?text=+)  | rgb(172, 232, 248)  |
| 60 to 80  | `#4cafd9` ![#4cafd9](https://via.placeholder.com/15/4cafd9/000000?text=+)  | rgb(76, 175, 217)  |
| 80 to 100  | `#1d5ede` ![#1d5ede](https://via.placeholder.com/15/1d5ede/000000?text=+)  | rgb(29, 94, 222)  |
| 100 to 120  | `#001bc0` ![#001bc0](https://via.placeholder.com/15/001bc0/000000?text=+)  | rgb(0, 27, 192)  |
| 120 to 150  | `#9131f1` ![#9131f1](https://via.placeholder.com/15/9131f1/000000?text=+)  | rgb(145, 49, 241)  |
| 150 to 200  | `#e983f3` ![#e983f3](https://via.placeholder.com/15/e983f3/000000?text=+)  | rgb(233, 131, 243)  |
| +200 and above  | `#f6c7ec` ![#f6c7ec](https://via.placeholder.com/15/f6c7ec/000000?text=+)  | rgb(246, 199, 236)  |

The threshold and the symbology for the `monthly` rainfall in milimeters can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| No Rain  | `#e1e1e1` ![#e1e1e1](https://via.placeholder.com/15/e1e1e1/000000?text=+) | rgb(225, 225, 225)  |
| 1 to 20  | `#ffffff` ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)  | rgb(255, 255, 255)  |
| 20 to 40  | `#f9f3d5` ![#f9f3d5](https://via.placeholder.com/15/f9f3d5/000000?text=+)  | rgb(249, 243, 213)  |
| 40 to 60  | `#dce2a8` ![#dce2a8](https://via.placeholder.com/15/dce2a8/000000?text=+)  | rgb(220, 226, 168)  |
| 60 to 80  | `#a8c58d` ![#a8c58d](https://via.placeholder.com/15/a8c58d/000000?text=+)  | rgb(168, 197, 141)  |
| 80 to 100  | `#77a87d` ![#77a87d](https://via.placeholder.com/15/77a87d/000000?text=+)  | rgb(119, 168, 125)  |
| 100 to 125  | `#ace8f8` ![#ace8f8](https://via.placeholder.com/15/ace8f8/000000?text=+)  | rgb(172, 232, 248)  |
| 125 to 150  | `#4cafd9` ![#4cafd9](https://via.placeholder.com/15/4cafd9/000000?text=+)  | rgb(76, 175, 217)  |
| 150 to 200  | `#1d5ede` ![#1d5ede](https://via.placeholder.com/15/1d5ede/000000?text=+)  | rgb(29, 94, 222)  |
| 200 to 250  | `#001bc0` ![#001bc0](https://via.placeholder.com/15/001bc0/000000?text=+)  | rgb(0, 27, 192)  |
| 250 to 300  | `#9131f1` ![#9131f1](https://via.placeholder.com/15/9131f1/000000?text=+)  | rgb(145, 49, 241)  |
| 300 to 350  | `#e983f3` ![#e983f3](https://via.placeholder.com/15/e983f3/000000?text=+)  | rgb(233, 131, 243)  |
| +350 and above  | `#f6c7ec` ![#f6c7ec](https://via.placeholder.com/15/f6c7ec/000000?text=+)  | rgb(246, 199, 236)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EmDYs8Wl_tlEqDNVBIhMMEEB6s-LNcoD4ET1GYPmJ_xjKQ?e=ikAANf](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EmDYs8Wl_tlEqDNVBIhMMEEB6s-LNcoD4ET1GYPmJ_xjKQ?e=ikAANf)

    For latest data, please check their official website.


### GPM IMERG

The GPM is next-generation of the Tropical Rainfall Measuring Mission (TRMM - https://pmm.nasa.gov/TRMM). Like the TRMM, the GPM mission aims at providing uniformly calibrated precipitation estimates at a quasi-global scale by merging the measurements from its constellation of microwave and IR satellites. All GPM data sets including measurements obtained from each platform (Level 2) are available on the PMM site (https://pmm.nasa.gov/data-access). Among many GPM products, the Multi-satellitE Retrievals for GPM (IMERG) is most interesting to the users since it delivers the ‘best’ precipitation estimates by combining data obtained from all available microwave and infrared (IR) platforms of the GPM satellite constellation. 

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Daily and monthly monitoring on precipitation  |
| Variable  | Total precipitation  |
| Geographic coverage  | Global 60N-60S, 180W-180E |
| Spatial resolution  | 0.1 degree ~ 11.1 km at equator  |
| Temporal resolution  | dailyand monthly |
| Format  | NetCDF  |
| Unit  | Total mm for given time step, mm/hour, mm/day, etc.  |
| Source  | Daily: [https://disc.gsfc.nasa.gov/datasets/GPM_3IMERGDF_06/summary](https://disc.gsfc.nasa.gov/datasets/GPM_3IMERGDF_06/summary), Monthly: [https://disc.gsfc.nasa.gov/datasets/GPM_3IMERGM_06/summary](https://disc.gsfc.nasa.gov/datasets/GPM_3IMERGM_06/summary), Climatology: [https://gpm.nasa.gov/data/imerg/precipitation-climatology](https://gpm.nasa.gov/data/imerg/precipitation-climatology)  |
| Reference  | [https://pmm.gsfc.nasa.gov/GPM](https://pmm.gsfc.nasa.gov/GPM)  |

**Symbology**

The threshold and the symbology for the `daily` rainfall in milimeters can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| No Rain  | `#e1e1e1` ![#e1e1e1](https://via.placeholder.com/15/e1e1e1/000000?text=+) | rgb(225, 225, 225)  |
| 1 to 3  | `#ffffff` ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)  | rgb(255, 255, 255)  |
| 3 to 10  | `#f9f3d5` ![#f9f3d5](https://via.placeholder.com/15/f9f3d5/000000?text=+)  | rgb(249, 243, 213)  |
| 10 to 20  | `#dce2a8` ![#dce2a8](https://via.placeholder.com/15/dce2a8/000000?text=+)  | rgb(220, 226, 168)  |
| 20 to 30  | `#a8c58d` ![#a8c58d](https://via.placeholder.com/15/a8c58d/000000?text=+)  | rgb(168, 197, 141)  |
| 30 to 40  | `#77a87d` ![#77a87d](https://via.placeholder.com/15/77a87d/000000?text=+)  | rgb(119, 168, 125)  |
| 40 to 60  | `#ace8f8` ![#ace8f8](https://via.placeholder.com/15/ace8f8/000000?text=+)  | rgb(172, 232, 248)  |
| 60 to 80  | `#4cafd9` ![#4cafd9](https://via.placeholder.com/15/4cafd9/000000?text=+)  | rgb(76, 175, 217)  |
| 80 to 100  | `#1d5ede` ![#1d5ede](https://via.placeholder.com/15/1d5ede/000000?text=+)  | rgb(29, 94, 222)  |
| 100 to 120  | `#001bc0` ![#001bc0](https://via.placeholder.com/15/001bc0/000000?text=+)  | rgb(0, 27, 192)  |
| 120 to 150  | `#9131f1` ![#9131f1](https://via.placeholder.com/15/9131f1/000000?text=+)  | rgb(145, 49, 241)  |
| 150 to 200  | `#e983f3` ![#e983f3](https://via.placeholder.com/15/e983f3/000000?text=+)  | rgb(233, 131, 243)  |
| +200 and above  | `#f6c7ec` ![#f6c7ec](https://via.placeholder.com/15/f6c7ec/000000?text=+)  | rgb(246, 199, 236)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: 

    Daily [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EpPACJEZArxHpJxrvNlnkgoBhDXxhoO6P8q7DZu69H4QxA?e=4xkSS3](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EpPACJEZArxHpJxrvNlnkgoBhDXxhoO6P8q7DZu69H4QxA?e=4xkSS3)

    Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EtyaGoYvM1hKjuf5KxZ0rUsBhK93BLW25iIpdtMdevfC9A?e=VfpRVj](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EtyaGoYvM1hKjuf5KxZ0rUsBhK93BLW25iIpdtMdevfC9A?e=VfpRVj)

    For latest data, please check their official website.


### NOAA GEFS

The Global Ensemble Forecast System (GEFS), previously known as the GFS Global ENSemble (GENS), is a weather forecast model made up of 21 separate forecasts, or ensemble members. The National Centers for Environmental Prediction ([NCEP](https://www.ncep.noaa.gov)) of NOAA started the GEFS to address the nature of uncertainty in weather observations, which is used to initialize weather forecast models. The GEFS attempts to quantify the amount of uncertainty in a forecast by generating an ensemble of multiple forecasts, each minutely different, or perturbed, from the original observations.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays 6-hour and daily precipitation forecast  |
| Variable  | Total precipitation forecast  |
| Geographic coverage  | Global |
| Spatial resolution  | 0.25 degree ~ 27.5 km at equator  |
| Temporal resolution  | Every 6-hour, up to 16-days ahead  |
| Format  | GRIB2  |
| Unit  | Total mm/6-hour.  |
| Source  | [https://nomads.ncep.noaa.gov/cgi-bin/filter_gefs_atmos_0p25s.pl](https://nomads.ncep.noaa.gov/cgi-bin/filter_gefs_atmos_0p25s.pl)  |
| Reference  | [https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/global-ensemble-forecast-system-gefs](https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/global-ensemble-forecast-system-gefs)  |

**Symbology**

The threshold and the symbology for the `daily` rainfall in milimeters can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| No Rain  | `#e1e1e1` ![#e1e1e1](https://via.placeholder.com/15/e1e1e1/000000?text=+) | rgb(225, 225, 225)  |
| 1 to 3  | `#ffffff` ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)  | rgb(255, 255, 255)  |
| 3 to 10  | `#f9f3d5` ![#f9f3d5](https://via.placeholder.com/15/f9f3d5/000000?text=+)  | rgb(249, 243, 213)  |
| 10 to 20  | `#dce2a8` ![#dce2a8](https://via.placeholder.com/15/dce2a8/000000?text=+)  | rgb(220, 226, 168)  |
| 20 to 30  | `#a8c58d` ![#a8c58d](https://via.placeholder.com/15/a8c58d/000000?text=+)  | rgb(168, 197, 141)  |
| 30 to 40  | `#77a87d` ![#77a87d](https://via.placeholder.com/15/77a87d/000000?text=+)  | rgb(119, 168, 125)  |
| 40 to 60  | `#ace8f8` ![#ace8f8](https://via.placeholder.com/15/ace8f8/000000?text=+)  | rgb(172, 232, 248)  |
| 60 to 80  | `#4cafd9` ![#4cafd9](https://via.placeholder.com/15/4cafd9/000000?text=+)  | rgb(76, 175, 217)  |
| 80 to 100  | `#1d5ede` ![#1d5ede](https://via.placeholder.com/15/1d5ede/000000?text=+)  | rgb(29, 94, 222)  |
| 100 to 120  | `#001bc0` ![#001bc0](https://via.placeholder.com/15/001bc0/000000?text=+)  | rgb(0, 27, 192)  |
| 120 to 150  | `#9131f1` ![#9131f1](https://via.placeholder.com/15/9131f1/000000?text=+)  | rgb(145, 49, 241)  |
| 150 to 200  | `#e983f3` ![#e983f3](https://via.placeholder.com/15/e983f3/000000?text=+)  | rgb(233, 131, 243)  |
| +200 and above  | `#f6c7ec` ![#f6c7ec](https://via.placeholder.com/15/f6c7ec/000000?text=+)  | rgb(246, 199, 236)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: GFS Historical [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EnxOg8ZxP8ZAr3w9-vaNkdsB0vZVOsd1LA81JCMpz3QHWw?e=BmWYDi](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EnxOg8ZxP8ZAr3w9-vaNkdsB0vZVOsd1LA81JCMpz3QHWw?e=BmWYDi)

    For latest data, please check their official website.


## Land Surface Temperature

Various satellite data provide land surface temperature as one of the product, Landsat, MODIS Terra Aqua and Sentinel are some of them.

### MODIS

The Moderate Resolution Imaging Spectroradiometer MODIS/Terra Land Surface Temperature and Emissivity 8-Day L3 Global 1 km Grid SIN V006 (MOD11A2) dataset provides global land surface temperature data (LST). The MOD11A2 version 6 product provides an average, 8-day, per-pixel LST  in a 1200 x 1200 kilometer grid. Each pixel value in the MOD11A2 is a simple average of all the corresponding MOD11A1 LST pixels collected within that 8 day period. The 8 day compositing period was chosen because twice that period is the exact ground track repeat period of the Terra and Aqua platforms. 

The MOD11C3 Version 6 product provides monthly Land Surface Temperature and Emissivity (LST&E) values in a 0.05 degree (5,600 meters at the equator) latitude/longitude Climate Modeling Grid (CMG). A CMG granule is a geographic grid with 7,200 columns and 3,600 rows representing the entire globe. The LST&E values in the MOD11C3 product are derived by compositing and averaging the values from the corresponding month of MOD11C1 daily files.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays `8-days` and `monthly` land surface temperature data  |
| Variable  | Day time temperature  |
| Geographic coverage  | Global |
| Spatial resolution  | `1 km` and `5.6 km`  |
| Temporal resolution  | `8-days` and `monthly`  |
| Format  | HDF-EOS  |
| Unit  | Kelvin, with scale factor 0.02.  |
| Source  | 8-days: [https://e4ftl01.cr.usgs.gov/MOLT/MOD11A2.006/](https://e4ftl01.cr.usgs.gov/MOLT/MOD11A2.006/), monthly: [https://e4ftl01.cr.usgs.gov/MOLT/MOD11C3.061/](https://e4ftl01.cr.usgs.gov/MOLT/MOD11C3.061/)  |
| Reference  | 8-days: [https://lpdaac.usgs.gov/products/mod11a2v006/](https://lpdaac.usgs.gov/products/mod11a2v006/), monthly: [https://lpdaac.usgs.gov/products/mod11c3v006/](https://lpdaac.usgs.gov/products/mod11c3v006/)  |

**Symbology**

The threshold and the symbology for the `8-days` land surface temperature in degree celcius (°C) can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| -40 and below  | `#b2182b` ![#b2182b](https://via.placeholder.com/15/b2182b/000000?text=+) | rgb(178, 24, 43)  |
| -40 to -30  | `#d6604d` ![#d6604d](https://via.placeholder.com/15/d6604d/000000?text=+)  | rgb(214, 96, 77)  |
| -30 to -20  | `#f4a582` ![#f4a582](https://via.placeholder.com/15/f4a582/000000?text=+)  | rgb(244, 165, 130)  |
| -20 to -10  | `#fddbc7` ![#fddbc7](https://via.placeholder.com/15/fddbc7/000000?text=+)  | rgb(253, 219, 199)  |
| -10 to +10  | `#f7f7f7` ![#f7f7f7](https://via.placeholder.com/15/f7f7f7/000000?text=+)  | rgb(247, 247, 247)  |
| +10 to +20  | `#d1e5f0` ![#d1e5f0](https://via.placeholder.com/15/d1e5f0/000000?text=+)  | rgb(209, 229, 240)  |
| +20 to +30  | `#92c5de` ![#92c5de](https://via.placeholder.com/15/92c5de/000000?text=+)  | rgb(146, 197, 222)  |
| +30 to +40  | `#4393c3` ![#4393c3](https://via.placeholder.com/15/4393c3/000000?text=+)  | rgb(67, 147, 195)  |
| +40 and above  | `#2166ac` ![#2166ac](https://via.placeholder.com/15/2166ac/000000?text=+)  | rgb(33, 102, 172)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: 

    LST 8-days:  [https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EoPZoj_eWUJGioKh7ZS6mQQBQQ7sX9axuRkqSX4SRGf5yg?e=g62qxG](https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EoPZoj_eWUJGioKh7ZS6mQQBQQ7sX9axuRkqSX4SRGf5yg?e=g62qxG)

    LST monthly: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EnyLg1_EijlPvtIpOPAkvl8Buji9p4Dcohj0aU2jfr0_OQ?e=S37KFC](https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EnyLg1_EijlPvtIpOPAkvl8Buji9p4Dcohj0aU2jfr0_OQ?e=S37KFC)

    For latest data, please check their official website.


## Evapotranspiration

Evapotranspiration (ET), for the most part, is the combination of transpiration from vegetation and evaporation from soil surfaces.

###  SSEBop

Actual ET (ETa) is produced using the Operational Simplified Surface Energy Balance (SSEBop) model (Senay et al., 2013) for 2003 to present. The SSEBop setup is based on the Simplified Surface Energy Balance (SSEB) approach (Senay et al., 2007, 2011) with unique parameterization for operational applications. It combines ET fractions generated from remotely sensed Moderate Resolution Imaging Spectroradiometer (MODIS) thermal imagery, acquired every 10 days, with reference ET using a thermal index approach. The unique feature of the SSEBop parameterization is that it uses a pre-defined, seasonally and spatially dynamic surface psychrometer parameter to calculate ET fraction as the difference between observed LST (dry-bulb) and a cold/wet boundary condition (wet-bulb) using the principle of satellite psychrometry (Senay, 2018). The original formulation of SSEB is an adaptation of the hot and cold pixel principle of SEBAL (Bastiaanssen et al., 1998) and METRIC (Allen et al., 2007) models. A recent evaluation of the global ETa product shows promising performance of ETa Anomaly for drought monitoring purposes while water budget studies, requiring absolute magnitudes, may need to apply a local/region-specific bias correction procedure (Senay et. al, 2020).

ETa data and anomaly products (current vs. 2003 – 2015) are available at: [https://earlywarning.usgs.gov/fews](https://earlywarning.usgs.gov/fews).

The actual ET data unit is millimeters (mm) and the associated color ramp is available for download as a .style file for ArcGIS and as txt file with RGB color codes. The SSEBop_symbology folder includes instructions on how to add the color ramp in ArcMap and further suggestions on the data visualization.

The anomalies are the ratio of ETa and the corresponding median ETa, expressed as a percent value and have the color ramp below. The color ramp, txt file with RGB color codes, and colormap file (.clr) are available in the SSEBop_symbology folder.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays `dekad`, `monthly` and `annual` actual evapotranspiration and anomaly data  |
| Variable  | Actual evapotranspiration and anomaly  |
| Geographic coverage  | Global |
| Spatial resolution  | 1 km  |
| Temporal resolution  | `dekad`, `monthly` and `annual`  |
| Format  | GeoTIFF  |
| Unit  | `mm` and `%`  |
| Source  | Dekadal Actual ET: [https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/dekadal/eta/downloads/](https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/dekadal/eta/downloads/), Monthly Actual ET: [https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/monthly/eta/downloads/](https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/monthly/eta/downloads/), Monthly ET Anomaly: [https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/monthly/eta/anomaly/downloads/](https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/monthly/eta/anomaly/downloads/), Annual Actual ET: [https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/yearly/etav5/downloads/](https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/fews/web/global/yearly/etav5/downloads/)  |
| Reference  | Dekadal: [https://earlywarning.usgs.gov/fews/product/461](https://earlywarning.usgs.gov/fews/product/461), Monthly: [https://earlywarning.usgs.gov/fews/product/460](https://earlywarning.usgs.gov/fews/product/460), Annual: [https://earlywarning.usgs.gov/fews/product/458](https://earlywarning.usgs.gov/fews/product/458)  |


**Symbology**

The threshold and the symbology for the ET anomaly (%) can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| < 50  | `#e5793a` ![#e5793a](https://via.placeholder.com/15/e5793a/000000?text=+) | rgb(229, 121, 58)  |
| 50 to 70  | `#ebab43` ![#ebab43](https://via.placeholder.com/15/ebab43/000000?text=+)  | rgb(235, 171, 67)  |
| 70 to 90  | `#f6d37f` ![#f6d37f](https://via.placeholder.com/15/f6d37f/000000?text=+)  | rgb(246, 211, 127)  |
| 90 to 110  | `#cccccc` ![#cccccc](https://via.placeholder.com/15/cccccc/000000?text=+)  | rgb(204, 204, 204)  |
| 110 to 130  | `#dae7bd` ![#dae7bd](https://via.placeholder.com/15/dae7bd/000000?text=+)  | rgb(218,  231, 189)  |
| 130 to 150  | `#a7c854` ![#a7c854](https://via.placeholder.com/15/a7c854/000000?text=+)  | rgb(167, 200, 84)  |
| > 150  | `#5aa655` ![#5aa655](https://via.placeholder.com/15/5aa655/000000?text=+)  | rgb(90, 166, 85)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**

    Dekadal Actual ET: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EpTVJXSunclJhAmCavMfFMwBdl5OVE0oJXO3EiacFTughA?e=wqe4br](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EpTVJXSunclJhAmCavMfFMwBdl5OVE0oJXO3EiacFTughA?e=wqe4br)<br>
    Monthly Actual ET: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Er7qrAywlKVLqe4E8lp0gkEBtD-HaOaJFQuJFgUawro0Nw?e=4lTC4h](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Er7qrAywlKVLqe4E8lp0gkEBtD-HaOaJFQuJFgUawro0Nw?e=4lTC4h)<br>
    Monthly ET Anomaly: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EgMhnhChXINHiJkgO2FC8VgB1RarLdgHeKkSqcHv-D8c8A?e=zMMOcc](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EgMhnhChXINHiJkgO2FC8VgB1RarLdgHeKkSqcHv-D8c8A?e=zMMOcc)<br>
    Annual Actual ET: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EmfbvxJNnhlPuehQaGy77QQB1lHhMgbUIpVY5s9YeNqC9A?e=0YMb69](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EmfbvxJNnhlPuehQaGy77QQB1lHhMgbUIpVY5s9YeNqC9A?e=0YMb69)<br>
    Annual ET Anomaly: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EgPJtm5qP11Ev26cy8-EhvgBwp6C5gEQh4bN7fVv3pldCA?e=0zw0zV](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EgPJtm5qP11Ev26cy8-EhvgBwp6C5gEQh4bN7fVv3pldCA?e=0zw0zV)<br>
    Symbology: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EnArLdzrlgJCjWhYwEP2uxEBnDWeQW8u0JhcXp_yJ3eZPQ?e=bF79E6](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EnArLdzrlgJCjWhYwEP2uxEBnDWeQW8u0JhcXp_yJ3eZPQ?e=bF79E6)<br>

    For latest data, please check their official website.

###  MODIS

The MOD16A2 Version 6 Evapotranspiration/Latent Heat Flux product is an 8-day composite dataset produced at 500 meter (m) pixel resolution. The algorithm used for the MOD16 data product collection is based on the logic of the Penman-Monteith equation, which includes inputs of daily meteorological reanalysis data along with Moderate Resolution Imaging Spectroradiometer (MODIS) remotely sensed data products such as vegetation property dynamics, albedo, and land cover.

Provided in the MOD16A2 product are layers for composited Evapotranspiration (ET), Latent Heat Flux (LE), Potential ET (PET) and Potential LE (PLE) along with a quality control layer. Two low resolution browse images, ET and LE, are also available for each MOD16A2 granule.

The pixel values for the two Evapotranspiration layers (ET and PET) are the sum of all eight days within the composite period and the pixel values for the two Latent Heat layers (LE and PLE) are the average of all eight days within the composite period. Note that the last acquisition period of each year is a 5 or 6-day composite period, depending on the year.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays `8-days` Evapotranspiration/Latent Heat Flux product  |
| Variable  | Evapotranspiration (ET), Latent Heat Flux (LE), Potential ET (PET) and Potential LE (PLE)  |
| Geographic coverage  | Regional |
| Spatial resolution  | 500 m  |
| Temporal resolution  | `8-days`  |
| Format  | GeoTIFF  |
| Unit  | Scale factor for LE and PLE (`J/m^2/day`): `10000`, ET and PET (`kg/m^2/day`): `0.1`  |
| Source  | [https://e4ftl01.cr.usgs.gov/MOLT/MOD16A2.006/](https://e4ftl01.cr.usgs.gov/MOLT/MOD16A2.006/)  |
| Reference  | [https://lpdaac.usgs.gov/products/mod16a2v006/](https://lpdaac.usgs.gov/products/mod16a2v006/)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**

    LE: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Er1CsV6-Bo5PmeptTNvOk9EBoQHpaff2_9xzys-wdVx43g?e=69spHJ](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Er1CsV6-Bo5PmeptTNvOk9EBoQHpaff2_9xzys-wdVx43g?e=69spHJ)<br>
    PLE: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Eug4SEiVawpHmmvzkTVmcBMBvdVner2fyq_2Qj3bSltYAA?e=vRFBuQ](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Eug4SEiVawpHmmvzkTVmcBMBvdVner2fyq_2Qj3bSltYAA?e=vRFBuQ)<br>
    ET: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EugotvnRJ3hClB_7I3z67TcB8PvQwwyuN6PSpnj5C9skIA?e=sBzGZF](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/EugotvnRJ3hClB_7I3z67TcB8PvQwwyuN6PSpnj5C9skIA?e=sBzGZF)<br>
    PET: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Eg-KkTd_2PNEiY3EKVJB9R4BVppAmGUVY5tI8QBEplSMKQ?e=bk7jYM](https://wfp.sharepoint.com/:f:/s/RBBGISEO-1/Eg-KkTd_2PNEiY3EKVJB9R4BVppAmGUVY5tI8QBEplSMKQ?e=bk7jYM)<br>

    For latest data, please check their official website.

## Snow

Snow cover and extent data is very important for RBB to help monitor the situation in some countries: Mongolia, DPR Korea, Afghanistan, Pakistan, Tajikistan, Kyrgyzstan, Nepal and Bhutan.

### MODIS

The data set provides the maximum snow cover extent observed over an eight-day period within 10° x 10° MODIS sinusoidal grid tiles. Tiles are generated by compositing 500 m observations from the 'MODIS/Terra Snow Cover Daily L3 Global 500m Grid' data set.

Maximum snow cover extent is generated by reading 8 days of 500 m resolution MOD10A1 tiles. If snow is observed in a cell on any day in the period, the cell is mapped as snow. If no snow is found, the cell is filled with the clear-view observation that occurred most often (e.g. snow free land, ocean, etc.). Cloud cover is only reported if the cell was cloud-obscured for all eight days in the period.

Snow cover is detected using the Normalized Difference Snow Index (NDSI). Snow-covered land typically has a very high reflectance in visible bands and very low reflectance in the shortwave infrared; the NDSI reveals the magnitude of this difference. 

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays `8-days` Snow cover and maximum extent  |
| Variable  | 8-days Snow Cover, Maximum Snow Extent  |
| Geographic coverage  | Regional |
| Spatial resolution  | 500 m  |
| Temporal resolution  | `8-days`  |
| Format  | GeoTIFF  |
| Unit  | none |
| Source  | [https://n5eil01u.ecs.nsidc.org/MOST/MOD10A2.061/](https://n5eil01u.ecs.nsidc.org/MOST/MOD10A2.061/)  |
| Reference  | [https://nsidc.org/data/mod10a2](https://nsidc.org/data/mod10a2)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**

    Snow Cover [https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EvfHupYMLn5JukCh_SCv5gEByyfUgMmIOMzcqK0fu_hU7g?e=28bPgB](https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EvfHupYMLn5JukCh_SCv5gEByyfUgMmIOMzcqK0fu_hU7g?e=28bPgB)<br>
    Maximum Snow Extent [https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/Euiyz6i9I_VFjGk-Jh67CQYBIKwGyVzC4xdmHUhFfqY-5w?e=2t0DDR](https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/Euiyz6i9I_VFjGk-Jh67CQYBIKwGyVzC4xdmHUhFfqY-5w?e=2t0DDR)

    For latest data, please check their official website.

## Cloud Cover

Cloud cover can influence numerous important ecological processes including reproduction, growth, survival, and behavior, yet our assessment of its importance at the appropriate spatial scales has remained remarkably limited. If captured over large extent yet at sufficiently fine spatial grain cloud cover dynamics may provide key information for delineating a variety of habitat types and predicting species distributions. 

### Cloud Cover Climatology

[EarthEnv](http://www.earthenv.org/) develop new near-global, fine-grain (≈1km) monthly cloud frequencies from 15 years of twice-daily MODIS satellite images that expose spatio-temporal cloud cover dynamics of previously undocumented global complexity. We demonstrate that cloud cover varies strongly in its geographic heterogeneity and that the direct, observation-based nature of cloud-derived metrics can improve predictions of habitats, ecosystem, and species distributions with reduced spatial autocorrelation compared to commonly used interpolated climate data. These findings support the fundamental role of remote sensing as an effective lens through which to understand and globally monitor the fine-grain spatial variability of key biodiversity and ecosystem properties.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays cloud cover climatology  |
| Variable  | Cloud cover percentage  |
| Geographic coverage  | Global |
| Spatial resolution  | 1 km  |
| Format  | GeoTIFF  |
| Unit  | Percent (%)  |
| Source  | [http://www.earthenv.org/cloud](http://www.earthenv.org/cloud)  |
| Reference  | [http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002415](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002415)  |

**Downloads**

!!! info "**Location**"

    Sharepoint: Regional coverage [https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/Eul2PX08JHNHgCvt_rus52ABi_golMKR4tzd-zP960viXQ?e=hVbpmD](https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/Eul2PX08JHNHgCvt_rus52ABi_golMKR4tzd-zP960viXQ?e=hVbpmD)

    For latest data, please check their official website.

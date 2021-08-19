# Vegetation, Cropland and Land Use Land Cover (LULC)

Various satellite data provide vegetation indices, cropland and landuse landcover as one of the product, Landsat, MODIS Terra Aqua and Sentinel are some of them.

## Vegetation Indices

Vegetation indices, usually produced on 8 or 16-day and monthly intervals and at multiple spatial resolutions, provide consistent spatial and temporal comparisons of vegetation canopy greenness, a composite property of leaf area, chlorophyll and canopy structure. Two vegetation indices are derived from atmospherically-corrected reflectance in the red, near-infrared, and blue wavebands; the normalized difference vegetation index (NDVI), and the enhanced vegetation index (EVI), which minimizes canopy-soil variations and improves sensitivity over dense vegetation conditions. The two products more effectively characterize the global range of vegetation states and processes.

### MODIS

The MOD13A1 and MOD13Q1 Version 6 product provides Vegetation Index (VI) values at a per pixel basis at 1 kilometer (km) and 250 meter (m) spatial resolution. There are two primary vegetation layers. The first is the Normalized Difference Vegetation Index (NDVI), which is referred to as the continuity index to the existing National Oceanic and Atmospheric Administration-Advanced Very High Resolution Radiometer (NOAA-AVHRR) derived NDVI. The second vegetation layer is the Enhanced Vegetation Index (EVI), which has improved sensitivity over high biomass regions. The algorithm for this product chooses the best available pixel value from all the acquisitions from the 16 day period. The criteria used is low clouds, low view angle and the highest NDVI/EVI value. 

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays `monthly` and  `16-days` vegetation indices data  |
| Variable  | NDVI and EVI  |
| Geographic coverage  | Regional |
| Spatial resolution  | `1 km` (MOD13A1) and `250 m` (MOD13Q1) |
| Temporal resolution  | Monthly and 16-days  |
| Format  | HDF-EOS  |
| Unit  | n/a, Scale factor `0.0001`  |
| Source  | Monthly: [https://e4ftl01.cr.usgs.gov/MOLT/MOD13A3.006/](https://e4ftl01.cr.usgs.gov/MOLT/MOD13A3.006/), 16-days: [https://e4ftl01.cr.usgs.gov/MOLT/MOD13Q1.006/](https://e4ftl01.cr.usgs.gov/MOLT/MOD13Q1.006/)  |
| Reference  | MOD13A3 [https://lpdaac.usgs.gov/products/mod13a3v006/](https://lpdaac.usgs.gov/products/mod13a3v006/), MOD13Q1 [https://lpdaac.usgs.gov/products/mod13q1v006/](https://lpdaac.usgs.gov/products/mod13q1v006/)  |

**Symbology**

The threshold and the symbology for the `monthly` and `16-days` NDVI can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| 0 and below  | `#002596` ![#002596](https://via.placeholder.com/15/002596/000000?text=+) | rgb(0, 37, 150)  |
| 0 to 0.05  | `#752a27` ![#752a27](https://via.placeholder.com/15/752a27/000000?text=+)  | rgb(117, 42, 39)  |
| 0.06 to 0.10  | `#b4672a` ![#b4672a](https://via.placeholder.com/15/b4672a/000000?text=+)  | rgb(180, 103, 42)  |
| 0.11 to 0.15  | `#f3a63b` ![#f3a63b](https://via.placeholder.com/15/f3a63b/000000?text=+)  | rgb(243, 166, 59)  |
| 0.16 to 0.25  | `#f6c042` ![#f6c042](https://via.placeholder.com/15/f6c042/000000?text=+)  | rgb(246, 192, 66)  |
| 0.26 to 0.35  | `#fffd54` ![#fffd54](https://via.placeholder.com/15/fffd54/000000?text=+)  | rgb(255, 253, 84)  |
| 0.34 to 0.42  | `#bdfb50` ![#bdfb50](https://via.placeholder.com/15/bdfb50/000000?text=+)  | rgb(189, 251, 80)  |
| 0.43 to 0.50  | `#8af94d` ![#8af94d](https://via.placeholder.com/15/8af94d/000000?text=+)  | rgb(138, 249, 77)  |
| 0.51 to 0.58  | `#64d640` ![#64d640](https://via.placeholder.com/15/64d640/000000?text=+)  | rgb(100, 214, 64)  |
| 0.59 to 0.66  | `#4ba52f` ![#4ba52f](https://via.placeholder.com/15/4ba52f/000000?text=+)  | rgb(75, 165, 47)  |
| 0.67 to 0.74  | `#33741f` ![#33741f](https://via.placeholder.com/15/33741f/000000?text=+)  | rgb(51, 116, 31)  |
| 0.75 to 1  | `#1f4d11` ![#1f4d11](https://via.placeholder.com/15/1f4d11/000000?text=+)  | rgb(31, 77, 17)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - EVI, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EuLVdmJ_hmVFoYAS8YLXgzwBUc-iFe0hwTtWXoKLEnC9jw?e=VSu2bi](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EuLVdmJ_hmVFoYAS8YLXgzwBUc-iFe0hwTtWXoKLEnC9jw?e=VSu2bi)
    - NDVI, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EhQu26Bo7wdFmPPvRJfQPeQBi5Vs2b09dzGDhvdGs23mog?e=RHeqFv](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EhQu26Bo7wdFmPPvRJfQPeQBi5Vs2b09dzGDhvdGs23mog?e=RHeqFv)
    - Pixel Reliability, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Es0QBime5kBApGTtx_EZImQBQj5M77cGFXm3m032Dby9lA?e=cWDres](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Es0QBime5kBApGTtx_EZImQBQj5M77cGFXm3m032Dby9lA?e=cWDres)
    - VI Quality, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EnbGVuTZ-UpNuMlhTkGNDRQB8cEY1FiTpuOrXNduQs71hQ?e=jOXUTh](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EnbGVuTZ-UpNuMlhTkGNDRQB8cEY1FiTpuOrXNduQs71hQ?e=jOXUTh)
    - EVI, 16-days [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EsRwR7GFhfNOiB3NcUcUtUMBFiicyHt2ZsORtyySLERdGw?e=EDHWCh](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EsRwR7GFhfNOiB3NcUcUtUMBFiicyHt2ZsORtyySLERdGw?e=EDHWCh)
    - Pixel Reliability, 16-days [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ElnwdNx2UelOn3x4WdLHPjMBf6dSh5jHpI1T5TnOx_F6Dg?e=wOsufG](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ElnwdNx2UelOn3x4WdLHPjMBf6dSh5jHpI1T5TnOx_F6Dg?e=wOsufG)


    For latest data, please check their official website.


## Leaf Area Index/FPAR

LAI is defined as the one-sided green leaf area per unit ground area in broadleaf canopies and as one-half the total needle surface area per unit ground area in coniferous canopies. FPAR is defined as the fraction of incident photosynthetically active radiation, 400-700 nanometers (nm), absorbed by the green elements of a vegetation canopy.

### MODIS

The MOD15A2H Version 6 Moderate Resolution Imaging Spectroradiometer (MODIS) combined Leaf Area Index (LAI) and Fraction of Photosynthetically Active Radiation (FPAR) product is an 8-day composite dataset with 500 meter (m) pixel size. The algorithm chooses the “best” pixel available from all the acquisitions of the Terra sensor from within the 8-day period.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays `8-days` leaf area index/FPAR data  |
| Variable  | LAI and FPAR  |
| Geographic coverage  | Regional |
| Spatial resolution  | `500 m` |
| Temporal resolution  | `8-days` |
| Format  | HDF-EOS  |
| Unit  | n/a, Scale factor FPAR `0.01` LAI  `0.1` |
| Source  | [https://e4ftl01.cr.usgs.gov/MOLT/MOD15A2H.006/](https://e4ftl01.cr.usgs.gov/MOLT/MOD15A2H.006/)  |
| Reference  | [https://lpdaac.usgs.gov/products/mod15a2hv006/](https://lpdaac.usgs.gov/products/mod15a2hv006/)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - LAI [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EvnrPESVPJNMoq48TJiGX_kBHvTKjSNIy8B1GiVehp-Eyg?e=PzT56P](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EvnrPESVPJNMoq48TJiGX_kBHvTKjSNIy8B1GiVehp-Eyg?e=PzT56P)
    - FPAR [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EqM1cxQYWv9Pl2LAKMRHiioBPs4DZPGC-NgPtmDcZIBuDw?e=gz95Wp](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EqM1cxQYWv9Pl2LAKMRHiioBPs4DZPGC-NgPtmDcZIBuDw?e=gz95Wp)


### VIIRS

The Visible Infrared Imaging Radiometer Suite (VIIRS) Leaf Area Index (LAI) and Fraction of Photosynthetically Active Radiation (FPAR) Version 1 data product provides information about the vegetative canopy layer at 500 meter resolution (VNP15A2H). The VIIRS sensor is located onboard the NOAA/NASA joint Suomi National Polar-Orbiting Partnership (Suomi NPP) satellite. LAI is an index that quantifies the one-sided leaf area of a canopy, while FPAR is the fraction of incoming solar energy absorbed through photosynthesis at 400 to 700 nanometers. This product is intentionally designed after the Terra and Aqua Moderate Resolution Imaging Spectroradiometer (MODIS) LAI/FPAR operational algorithm to promote the continuity of the Earth Observation System (EOS) mission.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays `8-days` leaf area index/FPAR data  |
| Variable  | LAI and FPAR  |
| Geographic coverage  | Regional |
| Spatial resolution  | `500 m` |
| Temporal resolution  | `8-days` |
| Format  | HDF-EOS  |
| Unit  | n/a, Scale factor FPAR `0.01` LAI  `0.1` |
| Source  | [https://e4ftl01.cr.usgs.gov/VIIRS/VNP15A2H.001/](https://e4ftl01.cr.usgs.gov/VIIRS/VNP15A2H.001/)  |
| Reference  | [https://lpdaac.usgs.gov/products/vnp15a2hv001/](https://lpdaac.usgs.gov/products/vnp15a2hv001/)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - LAI [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EgO3eVgO8YFCm3aiqKVFIZUBr7hEKq9iEOEFzi-BKwx1ew?e=wr3QTh](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EgO3eVgO8YFCm3aiqKVFIZUBr7hEKq9iEOEFzi-BKwx1ew?e=wr3QTh)
    - FPAR [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ElOjg5F6KDtOoiMCOXbRHZkBixt4IVkeCG0mJBv1Kputew?e=Rgkitg](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ElOjg5F6KDtOoiMCOXbRHZkBixt4IVkeCG0mJBv1Kputew?e=Rgkitg)

## Croplands

Land cover maps represent spatial information on different types (classes) of physical coverage of the Earth's surface, e.g. forests, grasslands, croplands, lakes, wetlands. Cropland includes areas used for the production of adapted crops for harvest. Two subcategories of cropland are recognized: cultivated and non-cultivated. Cultivated cropland comprises land in row crops or close-grown crops and also other cultivated cropland, for example, hay land or pasture land that is in a rotation with row or close-grown crops. Non-cultivated cropland includes permanent hay land and horticultural cropland.

### GFSAD30

The [GFSAD30](https://geography.wr.usgs.gov/science/croplands/index.html) is a NASA-funded project to provide high-resolution global cropland data and their water use that contributes towards global food security in the twenty-first century. The GFSAD30 products are derived through multi-sensor remote sensing data (e.g., Landsat, MODIS, AVHRR), secondary data, and field-plot data and aims at documenting cropland dynamics from 1990 to 2017.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | a proxy for impact analysis  |
| Variable  | Crop extent  |
| Geographic coverage  | Global  |
| Spatial resolution  | 30 meter/pixel  |
| Temporal resolution  | n/a (Year estimation is 2015)  |
| Format  | GeoTIFF  |
| Unit  | n/a  |
| Source  | [Southeast and Northeast Asia](https://lpdaac.usgs.gov/products/gfsad30seacev001/)  |
| Reference  | [https://lpdaac.usgs.gov/documents/168/GFSAD30SEACE_User_Guide_V1.pdf](https://lpdaac.usgs.gov/documents/168/GFSAD30SEACE_User_Guide_V1.pdf)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - GFSAD30: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Eldy4SdrdHNBp6yo8NmoFD0Bs212lGrm3MXPsfMfokq3eA?e=05FB92](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Eldy4SdrdHNBp6yo8NmoFD0Bs212lGrm3MXPsfMfokq3eA?e=05FB92)

### MODIS

MODIS global croplands extent datasets utilized 250m MODIS (MODerate Resolution Imaging Spectroradiometer) data to map global production cropland extent. A set of multi-year MODIS metrics incorporating four MODIS land bands, NDVI (Normalized Difference Vegetation Index) and thermal data was employed to depict cropland phenology over the period 2000-2008.

With a spatial resolution of 250m, the Global Cropland Extent product represents the finest-scale global cropland map derived using synoptic inputs, and due to the inclusion of 9 years of MODIS data it is designed to be relatively insensitive to inter-annual variability in depicting core cropland production areas. 

**About the data**

| Characteristic  | Cropland Probability  | Discrete Cropland/Non-Cropland  |
|---|---|---|
| Function  | a proxy for impact analysis  | a proxy for impact analysis  |
| Variable  | Crop extent  | Crop extent  |
| Geographic coverage  | Global  | Global  |
| Spatial resolution  | 250 meter/pixel  | 250 meter/pixel  |
| Temporal resolution  | n/a (Year estimation is 2010)  | n/a (Year estimation is 2010)  |
| Format  | GeoTIFF  | GeoTIFF  |
| Unit  | Value from 1 to 100 is probability that pixel is production cropland. Value of 0 is water and value of 255 is no data.  | A value of 1 means cropland, 0 means not cropland. A value of 254 means water and 255 is no data.  |
| Source  | [http://glad.geog.umd.edu/dataset/gce/250mprob](http://glad.geog.umd.edu/dataset/gce/250mprob)  | [http://glad.geog.umd.edu/dataset/gce/modis-global-crop-extent-discrete-croplandnot-cropland-data](http://glad.geog.umd.edu/dataset/gce/modis-global-crop-extent-discrete-croplandnot-cropland-data)  |
| Reference  | [http://glad.geog.umd.edu/dataset/gce/global-cropland-extent](http://glad.geog.umd.edu/dataset/gce/global-cropland-extent)  | [http://glad.geog.umd.edu/dataset/gce/global-cropland-extent](http://glad.geog.umd.edu/dataset/gce/global-cropland-extent)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - Cropland Probability [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Eldy4SdrdHNBp6yo8NmoFD0Bs212lGrm3MXPsfMfokq3eA?e=05FB92](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Eldy4SdrdHNBp6yo8NmoFD0Bs212lGrm3MXPsfMfokq3eA?e=05FB92)<br>
    - Discrete Cropland/Non-Cropland: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Eldy4SdrdHNBp6yo8NmoFD0Bs212lGrm3MXPsfMfokq3eA?e=05FB92](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Eldy4SdrdHNBp6yo8NmoFD0Bs212lGrm3MXPsfMfokq3eA?e=05FB92)


## Land Use Land Cover

Land cover indicates the physical land type such as forest or open water whereas land use documents how people are using the land. 

Land cover data documents how much of a region is covered by forests, wetlands, impervious surfaces, agriculture, and other land and water types. Water types include wetlands or open water. Land use shows how people use the landscape – whether for development, conservation, or mixed uses. The different types of land cover can be managed or used quite differently.

Land cover can be determined by analyzing satellite and aerial imagery. Land use cannot be determined from satellite imagery. Land cover maps provide information to help managers best understand the current landscape. To see change over time, land cover maps for several different years are needed.

### Copernicus

Copernicus Global Landcover is a discrete map and 10 continuous cover fractions (9 base land cover classes and seasonal water) to provide spatial information about land for a diversity of applications ranging from global forest monitoring, global crop monitoring, biodiversity and nature conservation to climate modelling.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays annual land cover data  |
| Variable  | Land cover  |
| Geographic coverage  | Global |
| Spatial resolution  | `100 m` |
| Temporal resolution  | `annual`, `2015 - 2019` |
| Format  | GeoTIFF  |
| Unit  | n/a  |
| Source  | [https://land.copernicus.eu/global/products/lc](https://land.copernicus.eu/global/products/lc)  |
| Reference  | [https://blog.vito.be/remotesensing/lcviewer](https://blog.vito.be/remotesensing/lcviewer)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    Copernicus Landcover: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Ejwt9mtwwPJNiYMxFMGobmsBbosBywKaTX7LtvtQhajzmA?e=NR3i7r](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Ejwt9mtwwPJNiYMxFMGobmsBbosBywKaTX7LtvtQhajzmA?e=NR3i7r)

### ESACCI

This dataset provides global maps describing the land surface into 22 classes, which have been defined using the United Nations Food and Agriculture Organization’s (UN FAO) Land Cover Classification System (LCCS). In addition to the land cover (LC) maps, four quality flags are produced to document the reliability of the classification and change detection.

In order to ensure continuity, these land cover maps are consistent with the series of global annual LC maps from the 1990s to 2015 produced by the European Space Agency (ESA) Climate Change Initiative (CCI), which are also available on the ESA CCI LC viewer.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays annual land cover data  |
| Variable  | Land cover  |
| Geographic coverage  | Global |
| Spatial resolution  | `300 m` |
| Temporal resolution  | `annual`, `1992 - 2020` |
| Format  | netCDF  |
| Unit  | n/a  |
| Source  | [https://cds.climate.copernicus.eu/cdsapp#!/dataset/satellite-land-cover?tab=overview](https://cds.climate.copernicus.eu/cdsapp#!/dataset/satellite-land-cover?tab=overview)  |
| Reference  | [https://www.esa-landcover-cci.org/?q=node/197](https://www.esa-landcover-cci.org/?q=node/197)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**

    ESAACCI Landcover: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Epx0WFyqTXRLmpLspON4QTIBkMti0I0cXcOaQDXf3d7eSg?e=tc7hW4](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Epx0WFyqTXRLmpLspON4QTIBkMti0I0cXcOaQDXf3d7eSg?e=tc7hW4)
    

### GlobCOVER

GlobCover is an ESA initiative which began in 2005 in partnership with JRC, EEA, FAO, UNEP, GOFC-GOLD and IGBP. The aim of the project was to develop a service capable of delivering global composites and land cover maps using as input observations from the 300m MERIS sensor on board the ENVISAT satellite mission. ESA makes available the land cover maps, which cover 2 periods: December 2004 - June 2006 and January - December 2009.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays land cover data  |
| Variable  | Land cover  |
| Geographic coverage  | Global |
| Spatial resolution  | `300 m` |
| Temporal resolution  | n/a, `2009` |
| Format  | GeoTIFF  |
| Unit  | n/a  |
| Source  | [http://due.esrin.esa.int/page_globcover.php](http://due.esrin.esa.int/page_globcover.php)  |
| Reference  | [http://due.esrin.esa.int/page_gcvRef.php](http://due.esrin.esa.int/page_gcvRef.php)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**

    GlobCover Landcover: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EhHo2zGObHNGhqDswQaGfl4B21SdJjz90_jR1zc7RSZecQ?e=xDvVnI](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EhHo2zGObHNGhqDswQaGfl4B21SdJjz90_jR1zc7RSZecQ?e=xDvVnI)
    

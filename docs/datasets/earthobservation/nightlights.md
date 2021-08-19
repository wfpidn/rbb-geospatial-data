# Nightlights

See the world at night

## VIIRS DNB

The Earth Observations Group ([EOG](https://payneinstitute.mines.edu/eog/nighttime-lights/)) is producing a version 1 suite of average radiance composite images using nighttime data from the Visible Infrared Imaging Radiometer Suite (VIIRS) Day/Night Band (DNB).

Prior to averaging, the DNB data is filtered to exclude data impacted by stray light, lightning, lunar illumination, and cloud-cover. Cloud-cover is determined using the VIIRS Cloud Mask product (VCM). In addition, data near the edges of the swath are not included in the composites (aggregation zones 29-32).

Temporal averaging is done on a monthly and annual basis. The version 1 series of monthly composites has not been filtered to screen out lights from aurora, fires, boats, and other temporal lights. However, the annual composites have layers with additional separation, removing temporal lights and background (non-light) values.

The version 1 products span the globe from 75N latitude to 65S. The products are produced in 15 arc-second geographic grids and are made available in geotiff format as a set of 6 tiles. The tiles are cut at the equator and each span 120 degrees of latitude. Each tile is actually a set of images containing average radiance values and numbers of available observations.

### Monthly Cloud-free DNB Composite

In the monthly cloud-free DNB composites, there are many areas of the globe where it is impossible to get good quality data coverage for that month. This can be due to cloud-cover, especially in the tropical regions, or due to solar illumination, as happens toward the poles in their respective summer months. Therefore, it is imperative that users of these data utilize the cloud-free observations file and not assume a value of zero in the average radiance image means that no lights were observed. 

The version 1 monthly series is run globally using two different configurations. The first excludes any data impacted by stray light. The second includes these data if the radiance values have undergone the stray-light correction procedure (Reference). These two configurations are denoted in the filenames as "vcm" and "vcmsl" respectively. The "vcmsl" version, that includes the stray-light corrected data, will have more data coverage toward the poles, but will be of reduced quality. It is up to the users to determine which set is best for their applications. 

**About the data**

| Name  | Descriptions  |
| --- | --- |
| Delivery File Type  | (*.tif) Internal DEFLATE compressed GeoTIFF (*.gz) Gzipped GeoTIFF  |
| Delivery File Content  | avg_rade9h, cf_cvg, cvg  |
| Delivery File Config  | vcm, vcmsl  |
| Unit  | (avg_rade9h) nW/cm2/sr  |
| Image File Type  | GeoTIFF  |
| Image CRS  | EPSG:4326 (Geographic Latitude/Longitude)  |
| Image Resolution  | 15 arc second (~500m at the Equator)  |
| Tiled  | No  |
| Coverage  | 180W, 75N, 180E, 65S. Note: The global coverage of monthly VNL is greatly affected by the length of day in different time of year. In summer time northern hemisphere will have less nighttime coverage due to longer day.  |


### Annual VNL V2

A new consistently processed time series of annual global VIIRS nighttime lights has been produced from monthly cloud-free average radiance grids spanning 2012* to 2020. The new methodology is a modification of the original method based on nightly data (Annual VNL V1). 

* For 2012 annual VNL V2, there are two sets. (A) 201204-201212, and (B) 201204-201303. Only set (B) has masked median and average, as well as lit area mask.

In both methods there is an initial filtering to remove sunlit, moonlit and cloudy pixels, leading to rough composites that contains lights, fires, aurora and background. In the original method, the rough annual composites are made from a full year of nightly DNB data. In the new method, the rough composites are made on monthly increments and then combined to form rough annual composites. Both methods employ outlier removal to discard biomass burning pixels and isolate the background. 

In the original method the outlier removal is performed on scattergrams generated for each 15 arc second grid cell, with outliers clipped off from both the high and low radiance sides of the scattergram. The discard of outlier pixels proceeds until the scattergram’s standard deviation stabilizes. The new method uses the twelve-month median radiance to discard high and low radiance outliers, filtering out most fires and isolating the background. Background areas are zeroed out in both methods using the data range (DR) calculated from 3x3 grid cells. In both methods, the DR threshold for background is indexed to cloud-cover levels, with higher DR thresholds in areas having low numbers of cloud-free coverages. In the new method, particular attention is given to setting a single DR threshold for distinguishing lit grid cells from background for each 15 arc second grid cell. This is achieved by setting the DR threshold from a multiyear maximum median and a corresponding multiyear percent cloud-cover grids. The multiyear approach makes it possible to detect lighting present in each 15 arc second grid cell with a single DR threshold across all the years in the series.

**About the data**

| Name  | Descriptions  |
| --- | --- |
| Delivery File Type  | gz (gzipped)  |
| Delivery File Content  | average, average-masked, cf_cvg, cvg, max, median, median-masked, min   |
| Delivery File Config  | vcmslcfg (when available)  |
| Image File Type  | GeoTIFF  |
| Unit  | (average, average-masked, max, median, median-masked, min) nW/cm2/sr  |
| CRS  | EPSG:4326 (Geographic Latitude/Longitude)  |
| Resolution  | 15 arc second (~500m at the Equator)  |
| Tiled  | No  |
| Coverage  | 180W, 75N, 180E, 65S  |

**Downloads**

!!! info "**Location**"

    **Google Drive:**
    
    - Monthly Cloud-free DNB Composite: [https://drive.google.com/drive/folders/1arhzMN4dCwtWcr5RDZXxU2zuOjU48n9T?usp=sharing](https://drive.google.com/drive/folders/1arhzMN4dCwtWcr5RDZXxU2zuOjU48n9T?usp=sharing)
    - Annual VNL V2: [https://drive.google.com/drive/folders/1Savgjsmt7EtSvXMULrg2zRbq2CTgWKlS?usp=sharing](https://drive.google.com/drive/folders/1Savgjsmt7EtSvXMULrg2zRbq2CTgWKlS?usp=sharing)
    - DMSP archive: [https://drive.google.com/drive/folders/1wwhqIm7Z8_U1Zydv7a3bUutOq04JU_5P?usp=sharing](https://drive.google.com/drive/folders/1wwhqIm7Z8_U1Zydv7a3bUutOq04JU_5P?usp=sharing)

    For latest data, please check their official website. [https://eogdata.mines.edu/products/vnl/](https://eogdata.mines.edu/products/vnl/)
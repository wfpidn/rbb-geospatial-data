# Vegetation Condition Index

The Vegetation Condition Index (VCI) compares the current NDVI to the range of values observed in the same period in previous years. The VCI is expressed in % and gives an idea where the observed value is situated between the extreme values (minimum and maximum) in the previous years. Lower and higher values indicate bad and good vegetation state conditions, respectively. The VCI associates with moisture condition of vegetation

The anomaly is calculated based on percentage of the average

VCI = 100 * (VI - min_VI)/(max_VI - min_VI)

where:

- VI is the current value of VI
- min_VI is the long-term minimum value of VI
- max_VI is the long-term maximum value of VI.

VI long-term max and min derived from MODIS data

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | a proxy for Vegetation Health Index calculation  |
| Variable  | VCI  |
| Geographic coverage  | Regional  |
| Spatial resolution  | 1 km and 250 m at equator  |
| Temporal resolution  | Monthly and 16-days  |
| Format  | GeoTIFF  |
| Unit  | Percent (%)  |


**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - VCI, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Enn8IfUUiyJCixY23kkyNEoBwA9ODfRl8pSGzgIUf9ErSA?e=UCRGsK](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/Enn8IfUUiyJCixY23kkyNEoBwA9ODfRl8pSGzgIUf9ErSA?e=UCRGsK)
    
    - VCI, 16-days [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EuDyy8OMdMFEt-0Qv8PnITsBy6oBAdQvO8eNJqabsdEeBQ?e=bktMOD](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EuDyy8OMdMFEt-0Qv8PnITsBy6oBAdQvO8eNJqabsdEeBQ?e=bktMOD)
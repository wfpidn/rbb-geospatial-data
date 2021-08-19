# Vegetation indices anomaly

The objective is to evaluate the monthly deviation of vegetation indices (VI) over the country. This is achieved through analysis of Anomalies, (i.e. a comparison against a reference). 

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays Monthly and 16-days VI anomaly data  |
| Variable  | VI anomaly  |
| Geographic coverage  | Regional |
| Spatial resolution  | 1 km (MOD13A3) and 250 m (MOD13Q1) at equator  |
| Temporal resolution  | Monthly and 16-days.  |
| Format  | GeoTIFF  |
| Unit  | Percent (%)  |


## Ratio anomaly

The anomaly is calculated based on percentage of the average

`Ratio anomaly` (%) = `100` * `VI`/`mean_VI`

where `VI` is current VI and `mean_VI` is long-term average of VI.

VI ratio anomaly derived from MODIS data

**Symbology**

The threshold and the symbology for the ratio anomaly can follow below colorcodes and image.

| Class  | Hex  | RGB  |
|---|---|---|
| 50% and below  | `#6a2b0e` ![#6a2b0e](https://via.placeholder.com/15/6a2b0e/000000?text=+) | rgb(106, 43, 14)  |
| 50 to 70%  | `#e06c2c` ![#e06c2c](https://via.placeholder.com/15/e06c2c/000000?text=+)  | rgb(224, 108, 44)  |
| 70 to 80%  | `#ebb049` ![#ebb049](https://via.placeholder.com/15/ebb049/000000?text=+)  | rgb(235, 176, 73)  |
| 80 to 90%  | `#e5db9e` ![#e5db9e](https://via.placeholder.com/15/e5db9e/000000?text=+)  | rgb(229, 219, 158)  |
| 90 to 110%  | `#ffffff` ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)  | rgb(255, 255, 255)  |
| 110 to 120%  | `#d6fb57` ![#d6fb57](https://via.placeholder.com/15/d6fb57/000000?text=+)  | rgb(214, 251, 87)  |
| 120 to 130%  | `#6fec48` ![#6fec48](https://via.placeholder.com/15/6fec48/000000?text=+)  | rgb(111, 236, 72)  |
| 130 to 150%  | `#3f8b48` ![#3f8b48](https://via.placeholder.com/15/3f8b48/000000?text=+)  | rgb(63, 139, 39)  |
| 150% and above  | `#1e4b10` ![#1e4b10](https://via.placeholder.com/15/1e4b10/000000?text=+)  | rgb(30, 75, 16)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - Ratio anomaly, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EutUkI4Q83ZPnCZGXLnZLB4BgCGJXspMcnHqIvtGCGh2pQ?e=Cxx5Ll](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EutUkI4Q83ZPnCZGXLnZLB4BgCGJXspMcnHqIvtGCGh2pQ?e=Cxx5Ll)
    - Ratio anomaly, 16-days [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ElJ05xl1bPFKsdpKlIMxg4YB0qcGFGW-ts-M7Dfa_exhYQ?e=YASnfT](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ElJ05xl1bPFKsdpKlIMxg4YB0qcGFGW-ts-M7Dfa_exhYQ?e=YASnfT)

## Difference anomaly

The anomaly is calculated based on difference of the average

`Difference anomaly` = `VI` - `mean_VI`

where `VI` is current VI and `mean_VI` is long-term average of VI.

VI difference anomaly derived from MODIS data

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - Difference anomaly, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EugiMYLpHEFKmQ12Wqw69nsBUoAa4M4gUzBN1m4-GM_4HQ?e=GWgbhr](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EugiMYLpHEFKmQ12Wqw69nsBUoAa4M4gUzBN1m4-GM_4HQ?e=GWgbhr)
    - Difference anomaly, 16-days [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EnbGVuTZ-UpNuMlhTkGNDRQB8cEY1FiTpuOrXNduQs71hQ?e=jOXUTh](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/EnbGVuTZ-UpNuMlhTkGNDRQB8cEY1FiTpuOrXNduQs71hQ?e=jOXUTh)

## Standardized anomaly

The anomaly is calculated based on difference of the average and divide with standard deviation

`Difference anomaly` = `VI` - `mean_VI`/`std_VI`

where `VI` is current VI, `mean_VI` and `std_VI` is long-term average and standard deviationof VI.

VI standardized anomaly derived from MODIS data

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - Standardized anomaly, Monthly [https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ErqeGE4t5ERAv8oaXDkMn78BiANVHte5EEZBIzoyo7bQdw?e=16AcgT](https://wfp.sharepoint.com/:f:/s/RBBGISEO-2/ErqeGE4t5ERAv8oaXDkMn78BiANVHte5EEZBIzoyo7bQdw?e=16AcgT)
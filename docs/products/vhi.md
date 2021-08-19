# Vegetation Health Index

Vegetation Health Index (VHI) is based on a combination of (i) Vegetation Condition Index (VCI): associates with moisture condition of vegetation; and (ii) Temperature Condition Index (VCI): associates with thermal condition of vegetation. 

The VCI is constructed using the NDVI and land surface temperature (LST) for TCI. The VHI is effective enough to be used as proxy data for monitoring vegetation health, drought, moisture, thermal condition, etc.

After computing the VCI and TCI values, the final index for agricultural drought is 

`VHI = 0.5 * (TCI + VCI)`

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays 16-days VHI data  |
| Variable  | VHI  |
| Geographic coverage  | Global  |
| Spatial resolution  | 1 km at equator  |
| Temporal resolution  | 16-days.  |
| Format  | GeoTIFF  |
| Unit  | n/a  |

**Symbology**

The threshold and the symbology for the VHI can follow below colorcodes and image.

| Class  | Threshold  | Hex  | RGB  |
|---|---|---|---|
| No Drought  | 40 and above  | `#b2b2b2` ![#b2b2b2](https://via.placeholder.com/15/b2b2b2/000000?text=+) | rgb(178, 178, 178)  |
| Mild Drought  | 30 to 40  | `#ffe5d9` ![#ffe5d9](https://via.placeholder.com/15/ffe5d9/000000?text=+)  | rgb(255, 229, 217)  |
| Moderate Drought  | 20 to 30  | `#fcaf92` ![#fcaf92](https://via.placeholder.com/15/fcaf92/000000?text=+)  | rgb(252, 175, 146)  |
| Severe Drought  | 10 to 20  | `#fa6948` ![#fa6948](https://via.placeholder.com/15/fa6948/000000?text=+)  | rgb(250, 105, 72)  |
| Extreme Drought  | 10 and below  | `#cc181e` ![#cc181e](https://via.placeholder.com/15/cc181e/000000?text=+)  | rgb(204, 24, 30)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
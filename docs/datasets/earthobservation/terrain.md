# Terrain

Terrain or relief (also topographical relief) involves the vertical and horizontal dimensions of land surface. In physical geography, terrain is the lay of the land. This is usually expressed in terms of the elevation, slope, and orientation of terrain features. Terrain affects surface water flow and distribution. Over a large area, it can affect weather and climate patterns.

There are many global elevation data that available for free at 1 arcsecond spatial resolution: NASADEM, SRTM, ASTER GDEM and ALOS DEM.

## NASADEM

NASADEM is a revision of SRTM, filling in holes with the best available other data. NASADEM data products were derived from original telemetry data from the Shuttle Radar Topography Mission (SRTM), a collaboration between NASA and the National Geospatial-Intelligence Agency (NGA), as well as participation from the German and Italian space agencies. 

SRTM’s primary focus was to generate a near-global DEM of the Earth using radar interferometry. In addition to Terra Advanced Spaceborne Thermal and Reflection Radiometer (ASTER) Global Digital Elevation Model (GDEM) Version 3 data, NASADEM also relied on Ice, Cloud, and Land Elevation Satellite (ICESat) Geoscience Laser Altimeter System (GLAS) ground control points of its lidar shots to improve surface elevation measurements that led to improved geolocation accuracy. 

Other reprocessing improvements include the conversion to geoid reference and the use of GDEMs and Advanced Land Observing Satellite Panchromatic Remote-sensing instrument for Stereo Mapping (PRISM) AW3D30 DEM, and interpolation for void filling. 

NASADEM are distributed in 1 degree latitude by 1 degree longitude tiles and consist of all land between 60° N and 56° S latitude. This accounts for about 80% of Earth’s total landmass. NASADEM_HGT data product layers include DEM, number of scenes (NUM), and an updated SRTM water body dataset (water mask). The NUM layer indicates the number of scenes that were processed for each pixel and the source of the data. A low-resolution browse image showing elevation is also available for each NASADEM_HGT granule.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays elevation data  |
| Variable  | Elevation  |
| Geographic coverage  | Global 60N-56S, 180W-180E |
| Spatial resolution  | 1 arcsecond  |
| Temporal resolution  | n/a  |
| Format  | HGT, nc and GeoTIFF  |
| Unit  | meters.  |
| Source  | [https://e4ftl01.cr.usgs.gov/MEASURES/NASADEM_HGT.001/](https://e4ftl01.cr.usgs.gov/MEASURES/NASADEM_HGT.001/)  |
| Reference  | [https://lpdaac.usgs.gov/products/nasadem_hgtv001/](https://lpdaac.usgs.gov/products/nasadem_hgtv001/)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**

    NASADEM for RBB countries: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EnLg0gucwtZCv00BJvoZqIYBytSxRV_wZAPikjRJJ-XOag?e=ktovEu](https://wfp.sharepoint.com/:f:/s/RBBGISEO-4/EnLg0gucwtZCv00BJvoZqIYBytSxRV_wZAPikjRJJ-XOag?e=ktovEu)

    For latest data, please check their official website.

## Copernicus DEM

The Copernicus DEM is a Digital Surface Model (DSM) which represents the surface of the Earth including buildings, infrastructure, and vegetation. The Copernicus DEM is provided in 3 different instances. Two worldwide coverages at 90m (GLO-90) and 30m (GLO-30) resolution are openly available to the public for download via the PANDA Catalogue and FTP. A further European coverage (EEA-10) is provided at 10m resolution, but data is restricted to eligible users who meet required access rights.

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays elevation data  |
| Variable  | Elevation  |
| Geographic coverage  | Global  |
| Spatial resolution  | 30m, 90m  |
| Temporal resolution  | n/a  |
| Format  | GeoTIFF  |
| Unit  | meters.  |
| Source  | [https://panda.copernicus.eu/web/cds-catalogue/welcome/](https://panda.copernicus.eu/web/cds-catalogue/welcome)  |
| Reference  | [https://bit.ly/3kEnXem](https://bit.ly/3kEnXem)  |

**Downloads**

!!! info "**Location**"

    **Google Drive:**

    Copernicus DEM for RBB countries: [https://drive.google.com/drive/folders/1Ke7fmUgmLZ-HDx74pAXU1WUU192HAcpQ?usp=sharing](https://drive.google.com/drive/folders/1Ke7fmUgmLZ-HDx74pAXU1WUU192HAcpQ?usp=sharing)

    For latest data, please check their official website.

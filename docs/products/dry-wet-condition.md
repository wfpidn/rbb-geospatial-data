# Dry and Wet Condition

## Consecutive Dry Days

The number of consecutive dry days (CDD) is the largest number of consecutive days with daily precipitation amount less than 1 mm (or depending on the rain days criteria of the country), within a certain time. Usually the process counts the number of days in the past 90 days to measure the drought level.

**How it works**

Calculate the number of rain days based on the threshold and calculate the count of the most recent days since a rain day or the most recent consecutive string of days that meet the threshold criteria is summed.

Threshold criteria: 1, 2.5, 5, 10 and 20 milimeters of rainfall

```
IF previousCDD == null THEN previousCDD == 0
ELSEIF todayRAIN > 1 AND previousCDD == 0 THEN previousCDD + 1
```

CDD derived from IMERG data

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays daily CDD  |
| Variable  | CDD  |
| Geographic coverage  | Global 60N-60S, 180W-180E |
| Spatial resolution  | 0.1 degree ~ 11.1 km at equator  |
| Temporal resolution  | Daily  |
| Format  | GeoTIFF  |
| Unit  | Number of day  |

**Symbology**

The threshold and the symbology for the CDD can follow below color codes and image.

| Class  | Threshold  | Hex  | RGB  |
|---|---|---|---|
| No Drought  | 0  | `#cccccc` ![#cccccc](https://via.placeholder.com/15/cccccc/000000?text=+)  | rgb(204, 204, 204)  |
| Very Short  | 1 - 5  | `#ffe5d9` ![#ffe5d9](https://via.placeholder.com/15/ffe5d9/000000?text=+)  | rgb(255, 229, 217)  |
| Short  | 6 - 10  | `#fcbba2` ![#fcbba2](https://via.placeholder.com/15/fcbba2/000000?text=+)  | rgb(252, 187, 162)  |
| Moderate  | 11 - 20  | `#fc9272` ![#fc9272](https://via.placeholder.com/15/fc9272/000000?text=+)  | rgb(252, 146, 114)  |
| Long  | 21 - 30  | `#fa6948` ![#fa6948](https://via.placeholder.com/15/fa6948/000000?text=+)  | rgb(250, 105, 72)  |
| Very Long  | 31 - 60  | `#de2c26` ![#de2c26](https://via.placeholder.com/15/de2c26/000000?text=+)  | rgb(222, 44, 38)  |
| Extreme Drought  | +60  | `#a60f14` ![#a60f14](https://via.placeholder.com/15/a60f14/000000?text=+)  | rgb(166, 15, 20)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    CDD 1mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Ehk5sEAK48xDvOxcQeBIS_kBdT7mYfBTelib4v1z2qPrbw?e=BoXOql](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Ehk5sEAK48xDvOxcQeBIS_kBdT7mYfBTelib4v1z2qPrbw?e=BoXOql)<br>
    CDD 2.5mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EpCLiKC2SbpGpa9JR8_stQgBGIWWlUc5zCRyxQTd5KruPw?e=y8XyYG](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EpCLiKC2SbpGpa9JR8_stQgBGIWWlUc5zCRyxQTd5KruPw?e=y8XyYG)<br>
    CDD 5mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EuKY56cbPvNBjOA-lJoDrAoBoSNf-qpWMURSLeZswKne5g?e=zFILBb](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EuKY56cbPvNBjOA-lJoDrAoBoSNf-qpWMURSLeZswKne5g?e=zFILBb)<br>
    CDD 10mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Ei1uKCm2Z01Kk9OqQFK5tbIB2APb3auuZiqAKflVZExC6Q?e=RCjhWR](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Ei1uKCm2Z01Kk9OqQFK5tbIB2APb3auuZiqAKflVZExC6Q?e=RCjhWR)<br>
    CDD 20mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/El1O5F1_6VNNpOwzFyOdyMQBGiAqjAj67lHwraoCAZqCjg?e=txu7Rd](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/El1O5F1_6VNNpOwzFyOdyMQBGiAqjAj67lHwraoCAZqCjg?e=txu7Rd)

## Consecutive Wet Days

The number of consecutive wet days (CWD) is similar to the above CDD, the largest number of consecutive days with daily precipitation amount more than 1 mm (or depend on the rain days criteria of the country), within a certain time. Usually the process counts the number of days in the past 90 days to measure the wet level.

**How it works**

Calculate the number of rain days based on the threshold and calculate the count of the most recent days since a dry day or the most recent consecutive string of days that meet the threshold criteria is summed.

Threshold criteria: 1, 2.5, 5, 10 and 20 milimeters of rainfall

```
IF previousCWD == null THEN previousCWD == 0
ELSEIF todayRAIN < 1 AND previousCWD == 0 THEN previousCWD + 1
```

CWD derived from IMERG data

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Displays daily CWD  |
| Variable  | CWD  |
| Geographic coverage  | Global 60N-60S, 180W-180E |
| Spatial resolution  | 0.1 degree ~ 11.1 km at equator  |
| Temporal resolution  | Daily  |
| Format  | GeoTIFF  |
| Unit  | Number of day  |

**Symbology**

The threshold and the symbology for the CWD can follow below color codes and image.

| Class  | Threshold  | Hex  | RGB  |
|---|---|---|---|
| No Rainfall  | 0  | `#cccccc` ![#cccccc](https://via.placeholder.com/15/cccccc/000000?text=+)  | rgb(204, 204, 204)  |
| Very Short  | 1 - 5  | `#ffffcc` ![#ffffcc](https://via.placeholder.com/15/ffffcc/000000?text=+)  | rgb(255, 255, 204)  |
| Short  | 6 - 10  | `#c6e8b3` ![#c6e8b3](https://via.placeholder.com/15/c6e8b3/000000?text=+)  | rgb(198, 232, 179)  |
| Moderate  | 11 - 20  | `#7eccba` ![#7eccba](https://via.placeholder.com/15/7eccba/000000?text=+)  | rgb(126, 204, 186)  |
| Long  | 21 - 30  | `#41b7c4` ![#41b7c4](https://via.placeholder.com/15/41b7c4/000000?text=+)  | rgb(65, 183, 196)  |
| Very Long  | 31 - 60  | `#2c80b8` ![#2c80b8](https://via.placeholder.com/15/2c80b8/000000?text=+)  | rgb(44, 128, 184)  |
| Extreme Wet  | +60  | `#253494` ![#253494](https://via.placeholder.com/15/253494/000000?text=+)  | rgb(37, 52, 148)  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    CWD 1mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EjiT4M6-GIROhvBMxdkBpPcB5gueMsvXaNllxT6VrSnMug?e=NjHSZH](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EjiT4M6-GIROhvBMxdkBpPcB5gueMsvXaNllxT6VrSnMug?e=NjHSZH)<br>
    CWD 2.5mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EiGqQ2ZIQtpLpjF5ONj2COQBuNdzKZG_UNsi7_3wvyy9wg?e=TvA4Yi](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EiGqQ2ZIQtpLpjF5ONj2COQBuNdzKZG_UNsi7_3wvyy9wg?e=TvA4Yi)<br>
    CWD 5mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EpSu0uZKAgJBmVx2MVoonhMBVE4WUn_arEfBEL8FpE0wmw?e=qgkYL4](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EpSu0uZKAgJBmVx2MVoonhMBVE4WUn_arEfBEL8FpE0wmw?e=qgkYL4)<br>
    CWD 10mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/ErWvXdqPYUJBuTgydsD9O_4BVpRgpY-na9wAKjImnx7O7A?e=53EorH](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/ErWvXdqPYUJBuTgydsD9O_4BVpRgpY-na9wAKjImnx7O7A?e=53EorH)<br>
    CWD 20mm: [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EkS8CKLEDBpBlfin1WDzwNsBSdjAxpa1AbARgGPteqn5FQ?e=ffsIXV](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EkS8CKLEDBpBlfin1WDzwNsBSdjAxpa1AbARgGPteqn5FQ?e=ffsIXV)
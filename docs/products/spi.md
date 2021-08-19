# Standardized Precipitation Index

The Standardized Precipitation Index (SPI) is a normalized index representing the probability of occurrence of an observed rainfall amount when compared with the rainfall climatology over a long-term period. This long-term record is fitted to a probability distribution, which is then transformed into a normal distribution so that the mean SPI for the location and desired period is zero.

Negative SPI values represent rainfall deficit and less than median precipitation (Dry), starts when the SPI value is equal or below -1.0. Whereas positive SPI values indicate rainfall surplus and greater than median precipitation (Wet), starts when the SPI value is equal or above 1.0, and ends when the value becomes negative.

**How it works**
- Precipitation is normalized using a probability distribution function so that values of SPI are actually seen as standard deviations from the median.
- A normalized distribution allows for estimation of both dry and wet periods.
- Accumulated values can be used to analyse drought severity (magnitude).
- At least 30 years of continuous monthly precipitation data are needed but longer-term records would be preferable.
- SPI timescale intervals shorter than 1 month and longer than 24 months may be unreliable.
- It is spatially invariant in its interpretation.
- Its probability-based nature (probability of observed precipitation transformed into an index) makes it well suited to risk management and triggers for decision-making.

Python packages [climate-indices](https://pypi.org/project/climate-indices/) developed by [U.S. Drought Portal](https://www.drought.gov/drought/python-climate-indices) used to calculate the index.

**Symbology**

The threshold and the symbology for the SPI can follow below color codes and image.

| Class  | Threshold  | Hex  | RGB  |
|---|---|---|---|
| Exceptionally Dry  | -2.00 and below  | `#760005` ![#760005](https://via.placeholder.com/15/760005/000000?text=+)  | rgb(118, 0, 5)  |
| Extremely Dry  | -2.00 to -1.50  | `#ec0013` ![#ec0013](https://via.placeholder.com/15/ec0013/000000?text=+)  | rgb(236, 0, 19)  |
| Severely Dry  | -1.50 to -1.20  | `#ffa938` ![#ffa938](https://via.placeholder.com/15/ffa938/000000?text=+)  | rgb(255, 169, 56)  |
| Moderately Dry  | -1.20 to -0.70  | `#fdd28a` ![#fdd28a](https://via.placeholder.com/15/fdd28a/000000?text=+)  | rgb(253, 210, 138)  |
| Abnormally Dry  | -0.70 to -0.50  | `#fefe53` ![#fefe53](https://via.placeholder.com/15/fefe53/000000?text=+)  | rgb(254, 254, 83)  |
| Near Normal  | -0.50 to +0.50  | `#ffffff` ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)  | rgb(255, 255, 255)  |
| Abnormally Moist  | +0.50 to +0.70  | `#a2fd6e` ![#a2fd6e](https://via.placeholder.com/15/a2fd6e/000000?text=+)  | rgb(162, 253, 110)  |
| Moderately Moist  | +0.70 to +1.20  | `#00b44a` ![#00b44a](https://via.placeholder.com/15/00b44a/000000?text=+)  | rgb(0, 180, 74)  |
| Very Moist  | +1.20 to +1.50  | `#008180` ![#008180](https://via.placeholder.com/15/008180/000000?text=+)  | rgb(0, 129, 128)  |
| Extremely Moist  | +1.50 to +2.00  | `#2a23eb` ![#2a23eb](https://via.placeholder.com/15/2a23eb/000000?text=+)  | rgb(42, 35, 235)  |
| Exceptionally Moist  | +2.00 and above  | `#a21fec` ![#a21fec](https://via.placeholder.com/15/a21fec/000000?text=+)  | rgb(162, 31, 236)  |


## CHIRPS

SPI derived from CHIRPS data

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Display SPI-1, SPI-2, SPI-3, SPI-6, SPI-9, SPI-12 and SPI-24  |
| Variable  | SPI  |
| Geographic coverage  | Regional 50N-23.5S, 60E-180E |
| Spatial resolution  | 0.05 degree ~ 5.6 km at equator  |
| Temporal resolution  | 1-month, 3-month, 6-month, 9-month, 12-month and 24-month, rolling by dekad.  |
| Format  | GeoTIFF  |
| Unit  | n/a  |

**Downloads**

!!! info "**Location**"

    **Sharepoint:**
    
    - SPI-1months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/En18Uspd_uVNnp6CzpGy9loBIPqFbF0KF26im0w32Qdiog?e=lPrRna](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/En18Uspd_uVNnp6CzpGy9loBIPqFbF0KF26im0w32Qdiog?e=lPrRna)
    - SPI-2months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Er81geARQmVMudwYzHaAslABRTyUVEvlNa6v9lm_mPIUjA?e=Xp6Zi4](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Er81geARQmVMudwYzHaAslABRTyUVEvlNa6v9lm_mPIUjA?e=Xp6Zi4)
    - SPI-3months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Ejgi4zBXE75ArRkcfTUCeNABT4_ILGKP2O008M7mTWMWUg?e=sJhHnX](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Ejgi4zBXE75ArRkcfTUCeNABT4_ILGKP2O008M7mTWMWUg?e=sJhHnX)
    - SPI-6months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EgQ5Wf6Q7ZFOlFMvffM90qEBkNJ32-T3Wakzcm7LZu64ZA?e=ygDhqA](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EgQ5Wf6Q7ZFOlFMvffM90qEBkNJ32-T3Wakzcm7LZu64ZA?e=ygDhqA)
    - SPI-9months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EvqZTr5YGVhEm4q6ZcdjAksBGrfi-7g6w1UWChygdmIM8g?e=0PSW16](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EvqZTr5YGVhEm4q6ZcdjAksBGrfi-7g6w1UWChygdmIM8g?e=0PSW16)
    - SPI-12months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EtQqXbrqLG5Pmw_wtsjQ1AUBY7nGgr_fUr6ymCy0cCz4vQ?e=20aGaK](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EtQqXbrqLG5Pmw_wtsjQ1AUBY7nGgr_fUr6ymCy0cCz4vQ?e=20aGaK)
    - SPI-24months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Eju54f1Nv8hDg-CsluhdugcBa3O01tEMPGHb1kl6ptb8jQ?e=lt9J06](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/Eju54f1Nv8hDg-CsluhdugcBa3O01tEMPGHb1kl6ptb8jQ?e=lt9J06)
    - SPI-36months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/ErFo0nHqJxVPoqaq7UpKgKABrFP1y_jqohSolNYZdH-bCw?e=eb4J4c](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/ErFo0nHqJxVPoqaq7UpKgKABrFP1y_jqohSolNYZdH-bCw?e=eb4J4c)
    - SPI-48months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/ErBfsp4fxLtBnXfRBgazuzsBXR-REliOa2v23fS5s7MWZg?e=oqGcju](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/ErBfsp4fxLtBnXfRBgazuzsBXR-REliOa2v23fS5s7MWZg?e=oqGcju)
    - SPI-60months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EvsJZhnI8RRBh0QEoxkaIlgBzVupAGA3g-87MGRwMwwmzQ?e=XzzrP2](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EvsJZhnI8RRBh0QEoxkaIlgBzVupAGA3g-87MGRwMwwmzQ?e=XzzrP2)
    - SPI-72months [https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EgM6coKbClpAvQfaQ_IRjPkBTUeQlNNe6MeA_qY0kP_U_w?e=hpxRCi](https://wfp.sharepoint.com/:f:/s/RBBGISEO-3/EgM6coKbClpAvQfaQ_IRjPkBTUeQlNNe6MeA_qY0kP_U_w?e=hpxRCi)


## IMERG

SPI derived from IMERG data

**About the data**

| Characteristic  | Description  |
|---|---|
| Function  | Display SPI-1, SPI-2, SPI-3, SPI-6, SPI-9, SPI-12 and SPI-24  |
| Variable  | SPI  |
| Geographic coverage  | Global 60N-60S, 180W-180E |
| Spatial resolution  | 0.1 degree ~ 11.1 km at equator  |
| Temporal resolution  | 1-month, 3-month, 6-month, 9-month, 12-month and 24-month, rolling by dekad.  |
| Format  | GeoTIFF  |
| Unit  | n/a  |

**Downloads**

!!! info "**Location**"

	**Google Drive**
    
    - SPI-1months [https://drive.google.com/drive/folders/1gyMDaJo6xtliEHyOY5K5cQceimZwTQrf?usp=sharing](https://drive.google.com/drive/folders/1gyMDaJo6xtliEHyOY5K5cQceimZwTQrf?usp=sharing)
    - SPI-2months [https://drive.google.com/drive/folders/1eo5cevEUSDPWKpwenj86qnUgTg4-jIZF?usp=sharing](https://drive.google.com/drive/folders/1eo5cevEUSDPWKpwenj86qnUgTg4-jIZF?usp=sharing)
    - SPI-3months [https://drive.google.com/drive/folders/1Ek_m07bxHa1irVsCtG2ySzKjdyZ8adpF?usp=sharing](https://drive.google.com/drive/folders/1Ek_m07bxHa1irVsCtG2ySzKjdyZ8adpF?usp=sharing)
    - SPI-6months [https://drive.google.com/drive/folders/1d2R6Vqoaj2coXfkOvW68YuM25x0HvXb_?usp=sharing](https://drive.google.com/drive/folders/1d2R6Vqoaj2coXfkOvW68YuM25x0HvXb_?usp=sharing)
    - SPI-9months [https://drive.google.com/drive/folders/1-X2Z95JZQ-mNpeZ9WnR2MMUXwgP69BE2?usp=sharing](https://drive.google.com/drive/folders/1-X2Z95JZQ-mNpeZ9WnR2MMUXwgP69BE2?usp=sharing)
    - SPI-12months [https://drive.google.com/drive/folders/1t13UCN90MOmMZATXcQAUAzL27F2FlWu5?usp=sharing](https://drive.google.com/drive/folders/1t13UCN90MOmMZATXcQAUAzL27F2FlWu5?usp=sharing)
    - SPI-24months [https://drive.google.com/drive/folders/1MaOMh4JFyzLSiQruaT198SYqvSzDUyqB?usp=sharing](https://drive.google.com/drive/folders/1MaOMh4JFyzLSiQruaT198SYqvSzDUyqB?usp=sharing)
    - SPI-36months [https://drive.google.com/drive/folders/19jJAC28qkLZZEDRM6QMB4Wc1dZREVDa9?usp=sharing](https://drive.google.com/drive/folders/19jJAC28qkLZZEDRM6QMB4Wc1dZREVDa9?usp=sharing)
    - SPI-48months [https://drive.google.com/drive/folders/1cRtmMiFPGDHJ4ekpOsuj7KImSgaad5dI?usp=sharing](https://drive.google.com/drive/folders/1cRtmMiFPGDHJ4ekpOsuj7KImSgaad5dI?usp=sharing)
    - SPI-60months [https://drive.google.com/drive/folders/1-YTVpxjovuQuq3XA8f-uLQVjL4mIUpG7?usp=sharing](https://drive.google.com/drive/folders/1-YTVpxjovuQuq3XA8f-uLQVjL4mIUpG7?usp=sharing)
    - SPI-72months [https://drive.google.com/drive/folders/1chfnv5xR0ah_vIF-ee9UVKD9OYw9SmuU?usp=sharing](https://drive.google.com/drive/folders/1chfnv5xR0ah_vIF-ee9UVKD9OYw9SmuU?usp=sharing)
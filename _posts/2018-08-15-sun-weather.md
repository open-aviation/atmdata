---
layout: dataset
title: Weather field reconstruction using aircraft surveillance data
author: Junzi Sun
date: 2018-08-15
tags: dataset
link: https://doi.org/10.6084/m9.figshare.6970403.v1
doi: 10.6084/m9.figshare.6970403.v1
---

This dataset contains the source data used for the experiments of the paper titled "Weather field reconstruction using aircraft surveillance data and a novel meteo-particle model".



## Dataset structure

- `modes_weather_obs_201801_01-10.zip` contains weather (wind and temperature) extracted from Mode-S and ADS-B data, from 2018-01-01 to 2018-01-10, at +/-30 minutes around 00h, 06h, 12h, and 18h of each day.
- `gfs_201801_01-10.zip` contains the wind and temperature data extracted from GFS reanalysis data with at 00h, 06h, 12h, and 18h each day.
- `ecmwf_201801_01-10-10.zip` contains the wind and temperature data extracted from ECMWF ERA5 reanalysis data with 00h, 06h, 12h, and 18h each day.
- `modes_raw_data_20180101_0900_1000.zip` contains the raw Mode-S data collected on 2018-01-01 from 09h to 10h.
- `modes_weather_obs_20180101_0900.csv` and `modes_weather_obs_20180101_0930.csv` are decoded weather information based on previous raw data.


## CSV column definitions

- `ts`: Unix time stamp
- `icao`: aircraft ICAO Mode-S transponder identifier
- `lat`: latitude
- `lon`: longitude
- `alt`: altitude (ft)
- `wx`: wind speed at x axis (u component of wind) (m/s)
- `wy`: wind speed at y axis (v component of wind) (m/s)
- `temp`: temperature (K)
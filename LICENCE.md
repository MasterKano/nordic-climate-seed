# Licence and attribution

These monthly CSV files are derived weather data. They are 72-point daily
extracts (latitudes 55, 57, …, 71; longitudes 4, 8, …, 32) for wind at 100 m,
2 m temperature, and precipitation, built from the Open-Meteo Historical
Weather API with `models=era5`. They are not Copernicus’ original GRIB or
NetCDF files, and they are not the compact grid-mean series published in
`MasterKano/emmi-data` under `nordic-climate/`.

## Open-Meteo data licence

The data obtained through the Open-Meteo API are offered under
[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
(CC BY 4.0). You may share and adapt the data, including for commercial use
of the data itself, provided you give attribution.

Attribution: weather data by [Open-Meteo.com](https://open-meteo.com/).

Source: https://open-meteo.com/en/license (read 25 Nov 2026).

## Open-Meteo free API terms are separate

CC BY 4.0 is the licence on the numbers. It is not permission to call the
free API. Open-Meteo’s terms of use say the free API is for non-commercial
use, with limits of 10,000 calls per day, 5,000 per hour and 600 per minute.
Commercial calling of the API requires a paid plan.

Source: https://open-meteo.com/en/terms (read 25 Nov 2026).

This repository redistributes data already retrieved. It does not include an
API key and it does not grant anyone the right to call the free API for a
commercial product.

## Copernicus ERA5

ERA5 is a product of the Copernicus Climate Change Service, produced by
ECMWF. The Copernicus licence allows reproduction and distribution with
attribution, and requires a note when the product has been modified.

Attribution: Generated using Copernicus Climate Change Service information
2026. This dataset was adapted: daily values at the 72 Nordic points above
were taken from ERA5 via Open-Meteo and stored as monthly CSV files.

## What is not in this repository

Hourly API responses, the old 10 m cache, calibration coefficients, and
workbook files are not included.

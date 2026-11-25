# Nordic climate seed

Private monthly point extracts for the emmi-data Nordic climate rebuild.
This repository is private. It is not a public data release.

The restore step in `MasterKano/emmi-data` downloads one release asset:

- tag `nordic-climate-seed-20261125`
- `nordic-climate-seed-20261125.tar.gz`
- `nordic-climate-seed-20261125.sha256`

The tarball contains only `cache/openmeteo100m/om_YYYY_MM.csv` (1,042 files,
1940-01 through 2026-10). It does not contain hourly responses, the retired
10 m cache, calibration files, or the five published compact products.

`LICENCE.md` states the Open-Meteo and Copernicus terms that apply to these
files.

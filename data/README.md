# Data Access Instructions

Due to size constraints, the full dataset (≈15 GB) is not hosted in this repository.

Allresults can be reproduced using the publicly available sources:
- NASA FIRMS / MODIS: https://firms.modaps.eosdis.nasa.gov/
- NOAA Weather: https://www.ncdc.noaa.gov/
- Local sensor data (optional): https://registry.opendata.aws/noaa-ghcn/

### Sample
A small synthetic example (`sample_data.csv`) is included for testing pipeline functionality.

To use the full dataset, download it into:
data/
├── modis/
├── noaa_weather/
└── sensors/

and update `configs/config.yaml` accordingly.


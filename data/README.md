# Data

This pipeline uses the **Electric Vehicle Population Data** published by the Washington State Department of Licensing.

- Full dataset (~9 MB JSON, ~22,000 records): https://catalog.data.gov/dataset/electric-vehicle-population-data
- A small sample (`sample/ElectricVehiclePopulationData_sample.json`) is included in this repo so the structure can be inspected without downloading the full file. It contains the complete `meta` section and the first 100 data rows.

To run the full pipeline, download the JSON export from the link above, place it in this folder as `ElectricVehiclePopulationData.json`, and upload it to the `raw/` prefix of your S3 bucket (see the main README).

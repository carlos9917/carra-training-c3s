# Tutorials for the Copernicus Arctic Reanalysis project (CARRA)
This tutorial includes the following examples

1. Getting CARRA data (`CARRA_get_T2m.ipynb`)
2. Plotting 2m temperature using CARRA data (`CARRA_T2m_mean.ipynb`)
3. Plotting ERA5 and CARRA data (`CARRA_plot_CARRA_ERA5_maps.ipynb`)
4. Plotting time series anomalies for 2m temperature using CARRA and ERA5 data (`CARRA_ERA5_time_series_anomaly.ipynb`)
5. Plotting total precipitation and monthly sums over Greenland using CARRA and ERA5 data (`CARRA_ERA5_total_precipitation.ipynb`)

## conda installation
Use the provided yml file and use
```
conda env create --file=./data_viz.yml

```

### TODO
- Add CDS commands for climate means in `CARRA_ERA5_time_series_anomaly.ipynb` when they are available in CDS

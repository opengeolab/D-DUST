# D-DUST

### Notebook description
- [Model Variables Request](https://github.com/opengeolab/D-DUST/blob/WP2/Model%20Variables%20Request.ipynb) : Access to [Copernicus Atmosphere Monitoring Service](https://atmosphere.copernicus.eu/data) API and allows to export NetCDF files to be used as input in the grid_processing notebook.
- [ARPA API Data Request](https://github.com/opengeolab/D-DUST/blob/WP2/ARPA_API_ground_sensors.ipynb) : Access to ARPA Ground Sensors for both meteorological and air quality stations. It allows to export a geopackage file for each sensor type. It is possible to download data directly from the API for the current year. For previous years .csv files from [Open Data Regione Lombardia](https://www.dati.lombardia.it/) are used.
- [Google Earth Engine API Data Request](https://github.com/opengeolab/D-DUST/blob/WP2/GEE_API.ipynb) : Access to [Google Earth Engine API](https://developers.google.com/earth-engine/datasets) using [geemap](https://geemap.org/) library to retrieve satellite data. It allows to export .tif files for each selected variable.
- [ESA Air Quality Sensor Data Request](https://github.com/opengeolab/D-DUST/blob/WP2/AQ_ESA_Stations.ipynb) : access to ESA Air Quality stations API and downloads data for each station in the time range.
- [Data processing](https://github.com/opengeolab/D-DUST/blob/WP2/grid_processing.ipynb) : it allows to calculate the mean value in each cell for all the selected variables.


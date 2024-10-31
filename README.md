# AAGI Environmental Data Tools List

A simple repo sharing a list of environmental data (*e.g.*, climate and soils) acquisition tools 

## R Packages

### Weather Data

- [{ag5tools}](https://agrdatasci.github.io/ag5Tools/) R toolbox to download and extract data from the "Agrometeorological indicators from 1979 to present derived from reanalysis" (AgERA5) dataset [daily]
- [{climenv}](https://github.com/jamestsakalos/climenv) Download, extract and visualise climatic and elevation data (*e.g.*, CHELSA) [monthly and daily]
- [{ecmwfr}](https://github.com/bluegreen-labs/ecmwfr) Interface to the public ECMWF API Web Services via Copernicus Climate Data Store (CDS) [monthly and daily]
- [{geodata}](https://github.com/rspatial/geodata) Download geographic data, including:
  - [CMIP6 Data](https://geodata.ucdavis.edu/cmip6/) [monthly]
  - WorldClim
    - [Historical](https://www.worldclim.org/data/worldclim21.html) [monthly]
    - [Future](https://www.worldclim.org/data/cmip6/cmip6climate.html) [monthly]
- [{GSODR}](https://docs.ropensci.org/GSODR/) - API Client for Global Surface Summary of the Day (GSOD) Weather Data Client in R [daily data]
- [{nasapower}](https://docs.ropensci.org/nasapower/) - API Client for NASA POWER Global Meteorology, Surface Solar Energy and Climatology in R [annual, monthly and daily data]
- [{weatherOz}](https://docs.ropensci.org/weatherOz/) - An API Client for Australian Weather and Climate Data Resources [annual, monthly, daily, sub-daily (DPIRD only), daily (SILO) data]
- [{weathervane}](https://biometryhub.github.io/weathervane/) - Functions to Download Australian Weather Data [daily data]
 
### Soil Data

- [{SLGACloud}](https://github.com/AusSoilsDSM/SLGACloud) - Access to TERN Landscapes Cloud Optimised GeoTiffs
- [{read.abares}](https://codeberg.org/adamhsparks/read.abares) - Simple downloading and importing of ABARES Data
  - Specifically: [Soil Thickness Data](https://adamhsparks.codeberg.page/read.abares/reference/get_soil_thickness.html)
 
### Miscellaneous

- [{extractOz}](https://dpird-fsi.github.io/extractOz/) - Get local attribute information from GPS points for Australian agricultural research (includes GRDC Agroecozones, Major Soil Orders and SILO Weather Data)
- [{dataharvester}](https://sydney-informatics-hub.github.io/dataharvester/) - Preprocess, aggregate, visualise and download geospatial data from a range of Australian (and international) data sources

## Python Packages

### Weather Data

- [cdsapi](https://github.com/ecmwf/cdsapi) - Python API to access the Copernicus Climate Data Store (CDS)2 [monthly and daily data data]
- [latlon_utils](https://github.com/Chilipp/latlon-utils) - Retrieve WorldClim climate and other information for lat-lon grid cells [monthly and daily data]
- [pynasapower](https://pynasapower.readthedocs.io/en/latest/) - Download meteorological data from NASA POWER using a simple Python API client (<https://power.larc.nasa.gov/>) [annual, monthly and daily data]

### Miscellaneous

- [geodata-harvester](https://github.com/Sydney-Informatics-Hub/geodata-harvester) - Comprehensive tool developed by AgReFed for automatic downloading from a wide range of geospatial/environment datasets (including SLGA, SILO, National DEM, DEA Earth Observations, Radiometric data and Google Earth Engine)

## Julia Packages

### Weather Data

- [CDSAPI.jl](https://github.com/JuliaClimate/CDSAPI.jl) - Julia API to the Climate Data Store (a.k.a. CDS) [monthly and daily data]
- [RasterDataSources.jl](https://github.com/EcoJulia/RasterDataSources.jl) - Easily download and use raster data sets in Julia (*e.g.*, WorldClim, CHELSA)
  - WorldClim [monthly data]
  - CHELSA (Climatologies at high resolution for the earth’s land surface areas) [monthly and daily data]

## Remote Sensing

### Satellite Data

- [TERN AET CMRSET](https://portal.tern.org.au/metadata/TERN/9fefa68b-dbed-4c20-88db-a9429fb4ba97) - TERN’s AET data provides Australia-wide coverage at a 30m resolution every month (continuous with no gaps due to clouds) using the CSIRO MODIS Reflectance-based Scaling EvapoTranspiration (CMRSET) algorithm 
- [Google Earth Engine TERN AET CMRSET](https://developers.google.com/earth-engine/datasets/catalog/TERN_AET_CMRSET_LANDSAT_V2_2) - Actual Evapotranspiration for Australia (CMRSET Landsat V2.2) from TERN also downloadable from GEE

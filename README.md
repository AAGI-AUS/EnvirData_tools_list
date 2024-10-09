# AAGI Environmental Data Tools List

A simple repo sharing a list of environmental data (*e.g.*, climate and soils) acquisition tools 

## R Packages

### Weather Data

- [{climenv}](https://github.com/jamestsakalos/climenv) Download, extract and visualise climatic and elevation data (*e.g.*, CHELSA) [monthly and daily]
- [{ecmwfr}](https://github.com/bluegreen-labs/ecmwfr) Interface to the public ECMWF API Web Services via Copernicus Climate Data Store (CDS) [monthly and daily]
- [{geodata}](https://github.com/rspatial/geodata) Download geographic data (Hijmans et al. 2023), including:
  - [CMIP6 Data](https://geodata.ucdavis.edu/cmip6/) [monthly]
  - WorldClim
    - [Historical](https://www.worldclim.org/data/worldclim21.html) [monthly]
    - [Future](https://www.worldclim.org/data/cmip6/cmip6climate.html) [monthly]
- [{GSODR}](https://docs.ropensci.org/GSODR/) - API Client for Global Surface Summary of the Day (GSOD) Weather Data Client in R [daily data]
- [{nasapower}](https://docs.ropensci.org/nasapower/) - API Client for NASA POWER Global Meteorology, Surface Solar Energy and Climatology in R [annual, monthly and daily data]
- [{weatherOz}](https://docs.ropensci.org/weatherOz/) - An API Client for Australian Weather and Climate Data Resources [annual, monthly, daily data, sub-daily (DPIRD only)]
- [{weathervane}](https://biometryhub.github.io/weathervane/) - Functions to Download Australian Weather Data [daily data]
 
### Soil Data

- [{SLGACloud}](https://github.com/AusSoilsDSM/SLGACloud) - Access to TERN Landscapes Cloud Optimised GeoTiffs
- [{read.abares}](https://codeberg.org/adamhsparks/read.abares) - Simple downloading and importing of ABARES Data
  - [Soil Thickness Data](https://adamhsparks.codeberg.page/read.abares/reference/get_soil_thickness.html)

## Python Packages

### Weather Data

- [cdsapi](https://github.com/ecmwf/cdsapi) Python API to access the Copernicus Climate Data Store (CDS)2 [monthly and daily data data]
- [latlon_utils](https://github.com/Chilipp/latlon-utils) Retrieve WorldClim climate and other information for lat-lon grid cells [monthly and daily data]
- [pynasapower](https://pynasapower.readthedocs.io/en/latest/) - Download meteorological data from NASA POWER using a simple Python API client (<https://power.larc.nasa.gov/>) [annual, monthly and daily data]

## Julia Packages

### Weather Data

- [CDSAPI.jl](https://github.com/JuliaClimate/CDSAPI.jl) Julia API to the Climate Data Store (a.k.a. CDS)1 [monthly and daily data]
- [RasterDataSources.jl](https://github.com/EcoJulia/RasterDataSources.jl) Easily download and use raster data sets in Julia (*e.g.*, WorldClim, CHELSA)
  - WorldClim [monthly data]
  - CHELSA (Climatologies at high resolution for the earth’s land surface areas) [monthly and daily data]

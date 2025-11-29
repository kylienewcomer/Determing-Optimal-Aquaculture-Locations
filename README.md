# Determing Optimal Aquaculture Locations

## Author: Kylie Newcomer
### Date Published: 11/29/2025

This repository contains the materials for the 'Prioritizing Potential Aquaculture' homework assignment for **EDS 223 Geospatial Analysis and Remote Sensing**. Materials for this assignment can be found on the [course website](https://eds-223-geospatial.github.io/). This project uses species temperature and depth ranges to determine optimal locations for aquaculture across the west coast

## Repository Structure
```text
├── .gitignore
│   └── data
│       ├── average_annual_sst_2008.tif
│       ├── average_annual_sst_2009.tif
│       ├── average_annual_sst_2010.tif
│       ├── average_annual_sst_2011.tif
│       ├── average_annual_sst_2012.tif
│       ├── depth.tif
│       ├── wc_regions_clean.dbf
│       ├── wc_regions_clean.prj
│       ├── wc_regions_clean.shp
│       └── wc_regions_clean.shx
├── Determing-Optimal-Aquaculture-Locations.Rproj
├── EEZsforaquaculture.qmd
└── README.md
```
## Data
### Suitable growing conditions
Information for both Oysters and Red Abalone temperature and depth ranges come from [SeaLifeBase](https://www.sealifebase.ca/search.php). 

### Sea Surface Temperature
To determine the average seat surface temperature across the west coast an average from 2008-2012 data was calculated. Rasters were created by NOAA using satellite data from [Coral Reef Watch](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).

### Bathymetry
Depth data comes from [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area)

### Exclusive Economic Zones
The West Coast Exclusive Economic Zone data is maritime boundaries come [marineregions.org](https://www.marineregions.org/downloads.php)


## References and Acknowledgements
Flanders Marine Institute (2025): MarineRegions.org. Available online at www.marineregions.org. Consulted on 2025-11-29.

NOAA Coral Reef Watch. 2019, updated daily. NOAA Coral Reef Watch Version 3.1 Daily 5km Satellite Regional Virtual Station Time Series Data for Southeast Florida, Mar. 12, 2013-Mar. 11, 2014. College Park, Maryland, USA: NOAA Coral Reef Watch. Data set accessed 2020-02-05 at https://coralreefwatch.noaa.gov/product/vs/data.php.

Palomares, M.L.D. and D. Pauly. Editors. 2025. SeaLifeBase. World Wide Web electronic publication. www.sealifebase.org, version (04/2025). [Accessed Novemeber 29, 2025]

Bathymetry data was obtained through open access on November 29, 2025 from the GEBCO Grid

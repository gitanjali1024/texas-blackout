# Identifying Homes in Houston That Lost Power During the February 2021 Winter Storms

This repository estimates the number of homes in the Houston metropolitan area that lost power during the February 2021 Texas winter storms. Using NASA VIIRS night light satellite data from before (February 7) and after (February 16) the storms, this analysis identifies areas where night light intensity dropped by more than 200 nW cm⁻² sr⁻¹, excludes areas within 200 m of highways, and combines the resulting blackout areas with OpenStreetMap building data to map and count affected homes.

EDS-223-HW3
├── data
│   └── VNP46A1
│   └── gis_osm_buildings_a_free_1.gpkg
│   └── gis_osm_roads_free_1.gpkg
├── texas-blackout.qmd
└── README.md

## Data Access

This data is housed in the data folder of the repo

## Author

Gitanjali Sharma

## References

The night lights data comes from NASA's VIIRS Black Marble product (VNP46A1), distributed through the Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC). It can be found here. Imagery around the storm dates can be explored using NASA's Worldview here.

The roads and buildings data come from OpenStreetMap and were downloaded through Geofabrik. They can be found here.
# Cloud Native Geospatial for Earth Observation Workshop

This repository contains workshop materials to that introduce
cloud native methods of working with Earth observation data products.

The repository focusses on the use case of measuring land productivity
as a subindicator of Sustainable Development Goal indicator 15.3.1:
Proportion of land that is degraded over total land area. For more infromation
please see the
[Satellite Data Requirements for SDGIndicator 15.3.1](https://ceos.org/sdg/files/supportsheets/SDG_15.3.1_EO_Satellite_Data_Requirements_31Aug2022.pdf)
document.

The selected application area is a forested region in Capão Bonito, 
a municipality in the state of São Paulo in Brazil. 

## Quickstart

### Tutorial PDF

Along with a completed notebook, we provide a [step-by-step PDF document](https://drive.google.com/file/d/1z_DO1xEDNmEwLTfk7HyhBe_z9ZzRGX1p/view?usp=sharing).
This was used to run the tutorial at SatSummit 2024.

### Start the Codespace

The easiest way to get started running through this workshop is to
launch a GitHub Codespace, which includes a VS Code web environment that
includes the ability to run and edit Jupyter Notebooks.

1. Click the green Code button
2. Click the Codespaces tab
3. Click Create codespace on main

![The required buttons for launching a Codespace](images/launch_codespace.png "Tabs for launching a Codespace in this Repository")

### Sign into NASA's Earthdata portal and create an access token

Sign up for EarthData: [https://urs.earthdata.nasa.gov/](https://urs.earthdata.nasa.gov/) if you don't have an account already.

The notebook uses the [`earthaccess`](https://github.com/nsidc/earthaccess) library for authenticating with NASA's Earthdata system.

`earthaccess.login()` prompts you for your Earthdata username and password. Once authenticated, you will have access to credentials for both HTTP and S3 access to Earthdata collections.

### Run the demonstration notebook

Open the `Cloud_Native_Land_Productivity_For_SDG15.ipynb`
notebook and work through the cells.

## Authorship and sponsorship

This notebook was written by Alex Leith and Caitlin Adams, with
financial support from the
[Committee on Earth Observation Satellites](https://ceos.org/)
and advice from members of the [GEO Land Degradation Neutrality Flagship](https://geo-ldn.org/).

## Further resources

### Digital Earth Australia's Sentinel-2 prodcut

* [Product overview](https://knowledge.dea.ga.gov.au/notebooks/DEA_products/DEA_Sentinel2_Surface_Reflectance/)
* STAC catalog URL: [https://explorer.dea.ga.gov.au/stac](https://explorer.dea.ga.gov.au/stac)

### NASA's Harmonized Landsat Sentinel-2 product

* [Product overvivew](https://hls.gsfc.nasa.gov/)
* [User guide](https://lpdaac.usgs.gov/documents/1698/HLS_User_Guide_V2.pdf)
* STAC catalog URL: [https://cmr.earthdata.nasa.gov/cloudstac/LPCLOUD/](https://cmr.earthdata.nasa.gov/cloudstac/LPCLOUD/)

### SDG indicator 15.3.1

There are multiple valuable resources related to measurment of land degredation through SDG indicator 15.3.1:

* [Good practice guidance. SDG indicator 15.3.1, Proportion of land that is degraded over total land area. Version 2.0.](https://www.unccd.int/resources/manuals-and-guides/good-practice-guidance-sdg-indicator-1531-proportion-land-degraded)
* [Satellite Data Requirements for SDGIndicator 15.3.1](https://ceos.org/sdg/files/supportsheets/SDG_15.3.1_EO_Satellite_Data_Requirements_31Aug2022.pdf)
* [TRENDS.EARTH: tracking land change](https://maps.trends.earth/map?tab=layers&zoom=7&center=lat%3D-8.477805461808186%26lng%3D-67.87353515625001&layers=%5B%5D&basemap=satellite)

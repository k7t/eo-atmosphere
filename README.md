# LTPy - Learning tool for Python on Atmospheric Composition Data

**LTPy - Learning tool for Python on Atmospheric Composition Data** is a 
Python-based training course on Atmospheric Composition Data. The training 
course covers modules on `10 - DATA ACCESS`, `20 - DATA DISCOVERY`, 
`30 - CASE STUDIES` as well as `40 - EXERCISE` of satellite- and model-based data 
on Atmospheric Composition.

The course is based on [Jupyter notebooks](https://jupyter.org/), which allow
a high-level of interactive learning, as code, text description and visualisation 
is combined in one place. If you have not worked with `Jupyter Notebooks` before, 
you can look at the module [01 - Python and Project Jupyter 101](./01_Python_and_Jupyter_101.ipynb) 
to get a short introduction to Jupyter notebooks and their benefits.

## Data on Atmospheric Composition
This course features the following data:

This course features the following data:
* `AC SAF GOME-2 Level-2` data onboard of Metop-A and Metop-B satellites
* `AC SAF GOME-2 Level-3` reprocessed and regridded data
<br>

* `GOME-2 Level-2 Polar Multi-Sensor Aerosol Optical Properties (PMAp)` data onboard of Metop-A and Metop-B satellites

* `IASI Level-2` data onboard of Metop-A and Metop-B satellites

<br>

* `Copernicus Sentinel-5P` data
* `Copernicus Sentinel-3 OLCI` data
* `Copernicus Sentinel-3 SLSTR NRT FRP` data
* `Copernicus Atmosphere Monitoring Service (CAMS)` data


## Course material
The course follows a modular approach and offers the following modules:

* **[0 - Introduction to Python and Project Jupyter](./01_ltpy_Intro_to_Python_and_Jupyter.ipynb)** *(optional)*

<br>

* **1 - Overview of data and data access systems**
  * [11 - Atmospheric Composition data overview and acccess](./11_ltpy_atmospheric_composition_overview.ipynb)
  * [12 - WEkEO Harmonized Data Access API](./12_ltpy_WEkEO_harmonized_data_access_api.ipynb)

<br>

* **2 - Load, browse and pre-process data**
  * [2.1.1 - AC SAF GOME-2 - Level 2 - Load and browse](./211_ltpy_AC_SAF_GOME-2_L2_load_browse.ipynb)
  * [2.1.2 - AC SAF GOME-2 - Level 2 - Pre-process](./212_ltpy_AC_SAF_GOME-2_L2_preprocess.ipynb)
  * [2.1.3 - AC SAF GOME-2 - Level 2 - Produce gridded dataset (L3)](./213_ltpy_AC_SAF_GOME-2_L2_produce_gridded_dataset_L3.ipynb)
  * [2.1.4 - AC SAF GOME-2 - Level 3](./214_ltpy_AC_SAF_GOME-2_L3.ipynb)
  * [2.1.5 - AC SAF GOME-2 - Level 3 - Aerosol Absorbing Index](./215_ltpy_AC_SAF_GOME-2_L3_AAI.ipynb) 
  * [2.2 - GOME-2 - Polar Multi-Sensor Aerosol Optical Properties - Load and browse](./22_ltpy_GOME-2_PMAp_load_browse.ipynb)
  * [2.3 - IASI - Level 2 - Load and browse](./23_ltpy_IASI_L2_load_browse.ipynb)
  * [2.4 - Sentinel-5p - Level 2](./24_ltpy_Sentinel5p_L2_data.ipynb)
  * [2.5 - Copernicus Atmosphere Monitoring Service (CAMS)](./25_ltpy_Copernicus_Atmosphere_Monitoring_Service_data.ipynb)
  * [2.6 - Sentinel-3 OLCI - Level 1](./26_ltpy_Sentinel3_OLCI_L1.ipynb)
  * [2.7.1 - Sentinel-3 SLSTR NRT - Fire Radiative Power (FRP) - Australian Fires](./271_ltpy_Sentinel3_slstr_nrt_frp_Australian_fires.ipynb)
  * [2.7.2 - Sentinel-3 SLSTR NRT - Fire Radiative Power (FRP) - Chernobyl Fires](./272_ltpy_Sentinel3_slstr_nrt_frp_Chernobyl_fires.ipynb)
  * [2.8.1 - Global ECMWF Fire Forecast - Data Overview](./281_ltpy_GEFF_fire_forecast_data_overview.ipynb)
  * [2.8.2 - Global ECMWF Fire Forecast - Harmonized Danger Classes](./282_ltpy_GEFF_fire_forecast_harmonized_danger_classes.ipynb)
  * [2.8.3 - Global ECMWF Fire Forecast - Custom Danger Classes](./283_ltpy_GEFF_fire_forecast_custom_danger_classes.ipynb)

<br>

* **3 - Data workflows and case studies**
  * [3.1 - Case study - AC SAF GOME-2 - Level 2 data](./31_ltpy_case_study_AC_SAF_GOME-2_L2.ipynb)
  * [3.2 - Case study - AC SAF GOME-2 - Level 3 data](./32_ltpy_case_study_AC_SAF_GOME-2_L3.ipynb)
  * [3.3 - Case study - Siberian Fires - Summer 2019](./33_ltpy_case_study_Siberian_Fires_summer_2019.ipynb)
  * [3.4.1 - Case study - Antarctic ozone hole anomaly - Summer 2019](./341_ltpy_case_study_Ozone_hole_anomaly.ipynb)
  * [3.4.2 - Case study - Antarctic ozone hole anomaly - Summer 2019 - CAMS Animation](./342_ltpy_case_study_Ozone_hole_anomaly_2019_cams_animation.ipynb)
  * [3.5.1 - Case study - Covid-19 - GOME-2 anomaly map](./351_ltpy_case_study_covid-19_GOME2_anomaly_map.ipynb)
  * [3.5.2 - Case study - Covid-19 - GOME-2 time-series analysis](./352_ltpy_case_study_covid-19_GOME2_time-series.ipynb)
  * [3.5.3 - Case study - Covid-19 - Sentinel-5p anomaly map](./353_ltpy_case_study_covid-19_sentinel5p_maps.ipynb)
  * [3.5.4 - Case study - Covid-19 - Sentinel-5p time-series analysis](./354_ltpy_case_study_covid-19_sentinel5p_time-series.ipynb)
<br>

**NOTE:** Throughout the course, general functions to `load`, `re-shape`, `process` and `visualize` the datasets are defined. These functions are re-used when applicable. The [LTPy functions notebook](./ltpy_functions.ipynb) gives you an overview of all the functions defined and used for the course.

The notebook [12 - WEkEO Harmonized Data Access API](./12_ltpy_WEkEO_harmonized_data_access_api.ipynb) makes use of functions defined in the [LTPy HDA API functions notebook](./ltpy_hda_api_functions.ipynb).



## Learning outcomes
The course is designed for `medium-level users`, who have basic Python knowledge 
and understanding of `Atmospheric composition data`.

After the course, you should have:

* an idea about the different datasets on Atmospheric Composition data,
* knowledge about the most useful Python packages to handle, process and 
visualise large volumes of Earth Observation data
* an idea about different data application areas

## How to use this course material
This course material is made available via EUMETSAT's EUMETlab training space on
GitLab. While GitLab offers integrated rendering of Jupyter Notebooks, it's 
rendering capabilities is limited. Thus, the notebooks, if directly rendered on
GitLab, might appear not in a nice format, which make the learning process
difficult.

There are several ways how to use these modules:
1. **[nbviewer](https://nbviewer.jupyter.org/)** - Static rendering of the 
notebooks. Copy paste the link to the notebook [00_index_ltpy.ipynb](./00_index_ltpy.ipynb) 
into nbviewer.
2. **Clone this repo** and run the notebooks on your local Jupyter notebook
server. If you prefer this solution, you have to reproduce the settings. The following
section provides you more information on how to reproduce the set up on your 
local machine.
3. **LTPy JupyterHub** - You can create an 
account [here](http://wekeo-login.services.meeo.it/) and then log into the
[LTPy Jupyterhub](https://ltpy.adamplatform.eu).

## Reproduce LTPy on Atmospheric Compostion data locally
In case you wish to reproduce the course modules on your local setup, the 
following Python version and Python packages will be required:

* Python version: **Python3**
* Python packages:
  * [xarray 0.14.1](http://xarray.pydata.org/en/stable/index.html)
  * [netCDF4 1.5.3](https://unidata.github.io/netcdf4-python/netCDF4/index.html)
  * [numpy 1.17.3](https://numpy.org/)
  * [matplotlib 3.1.2](https://matplotlib.org/)
  * [Cartopy 0.17.0](https://scitools.org.uk/cartopy/docs/latest/)

Python packages can be installed with `conda install <python_package_name>` or 
`pip install <python_pacakage_name>`. 


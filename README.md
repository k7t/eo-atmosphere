# LTPy - Learning tool for Python on Atmospheric Composition Data

**LTPy - Learning tool for Python on Atmospheric Composition Data** is a Python-based training course on Atmospheric Composition Data. The training course covers [10 - DATA ACCESS](#data_access), [20 - DATA DISCOVERY](#data_discovery), [30 - CASE STUDIES](#case_studies) and [40 - EXERCISES](#exercises) of satellite- and model-based data on Atmospheric Composition.

The course is based on [Jupyter notebooks](https://jupyter.org/), which allow for a high-level of interactive learning, as code, text description and visualisation is combined in one place. If you have not worked with `Jupyter Notebooks` before, you can look at the module [01 - Python and Project Jupyter 101](./01_Python_and_Jupyter_101.ipynb) to get a short introduction to Jupyter notebooks and their benefits.


## Data on Atmospheric Composition
This course features the following **satellite** data:
* `AC SAF GOME-2 Level-2` data onboard of Metop-A and Metop-B satellites
* `AC SAF GOME-2 Level-3` reprocessed and regridded data
* `GOME-2 Level-2 Polar Multi-Sensor Aerosol Optical Properties (PMAp)` data onboard of Metop-A and Metop-B satellites
* `IASI Level-2` data onboard of Metop-A and Metop-B satellites
* `Copernicus Sentinel-5P` data
* `Copernicus Sentinel-3 OLCI` data
* `Copernicus Sentinel-3 SLSTR NRT FRP` data
* `Copernicus Sentinel-3 SLSTR NRT AOD` data

And the following **model-based** data:
* `Copernicus Atmosphere Monitoring Service (CAMS)` data
* `Global ECMWF Fire Forecast (GEFF)` data



## Course material
The course follows a modular approach and offers modules on:
- [10 - DATA ACCESS](#data_access)
- [20 - DATA DISCOVERY](#data_discovery)
- [30 - CASE STUDIES](#case_studies)
- [40 - EXERCISES](#exercises)


### <a id='data_acces'></a>10 - DATA ACCESS

 * [11 - Atmospheric Composition data overview and acccess](./10_data_access/11_ac_data_access_overview.ipynb)
 * [12 - WEkEO Harmonized Data Access API](./10_data_access/12_WEkEO_harmonized_data_access_api.ipynb)


### <a id='data_discovery'></a>20 - DATA DISCOVERY

##### *AC SAF GOME-2 Level 2 and Level 3 data*
   * [211 - AC SAF GOME-2 - Level 2 - Load and browse](./20_data_discovery/211_AC_SAF_GOME-2_L2_load_browse.ipynb)
   * [212 - AC SAF GOME-2 - Level 2 - Pre-process](./20_data_discovery/212_AC_SAF_GOME-2_L2_preprocess.ipynb)
   * [213 - AC SAF GOME-2 - Level 3 - Load and browse](./20_data_discovery/213_AC_SAF_GOME-2_L3_load_browse.ipynb)
   * [214 - AC SAF GOME-2 - Level 3 - Aerosol Absorbing Index (AAI)](./20_data_discovery/214_AC_SAF_GOME-2_L3_AAI_load_browse.ipynb)

#### *GOME-2 Polar Multi-Sensor Aerosol Optical Properties (PMAp) data*
   * [221 - GOME-2 - Polar Multi-Sensor Aerosol Optical Properties (PMAp) - Load and browse](./20_data_discovery/221_GOME-2_PMAp_load_browse.ipynb)

#### *IASI Level 2 data*
   * [231 - IASI - Level 2 - Load and browse](./20_data_discovery/23_IASI_L2_load_browse.ipynb)

#### *Sentinel-5P Level 2 data*
   * [241 - Sentinel-5P - Level 2 - Load and browse](./20_data_discovery/241_Sentinel-5P_L2_load_browse.ipynb)

#### *Sentinel-3 data*
   * [251 - Sentinel-3 OLCI - Level 1 - Load and browse](./20_data_discovery/251_Sentinel-3_OLCI_L1_load_browse.ipynb)
   * [252 - Sentinel-3 SLSTR NRT - Fire Radiative Power (FRP) - Load and browse](./20_data_discovery/252_Sentinel-3_SLSTR_NRT_FRP_load_browse.ipynb)
   * [253 - Sentinel-3 SLSTR NRT - Aerosol Optical Depth (AOD) - Load and browse](./20_data_discovery/253_Sentinel-3_SLSTR_NRT_AOD_load_browse.ipynb)

#### *Copernicus Atmosphere Monitoring Service (CAMS) data*
   * [261 - CAMS - EAC4  Load and browse](./20_data_discovery/261_CAMS_eac4_load_browse.ipynb)
   * [262 - CAMS - GFAS - Load and browse](./20_data_discovery/262_CAMS_gfas_load_browse.ipynb)

#### *Global ECMWF Fire Forecast (GEFF) data*
   * [271 - Global ECMWF Fire Forecast - Load and browse](./20_data_discovery/271_GEFF_fire_forecast_load_browse.ipynb)
   * [272 - Global ECMWF Fire Forecast - Harmonized Danger Classes](./20_data_discovery/272_GEFF_fire_forecast_harmonized_danger_classes.ipynb)
   * [273 - Global ECMWF Fire Forecast - Custom Danger Classes](./20_data_discovery/273_GEFF_fire_forecast_custom_danger_classes.ipynb)


### <a id='case_studies'></a>30 - CASE STUDIES

#### *AC SAF GOME-2 Level 2 and Level 3 data*
   * [311 - AC SAF GOME-2 - Level 2 - Case study](./30_case_studies/311_AC_SAF_GOME-2_L2_case_study.ipynb)
   * [312 - AC SAF GOME-2 - Level 3 - Case study](./30_case_studies/312_AC_SAF_GOME-2_L3_case_study.ipynb)
   * [313 - AC SAF GOME-2 - Level 2 - Produce gridded dataset - Workflow](./30_case_studies/313_AC_SAF_GOME-2_L2_produce_gridded_dataset_workflow.ipynb)

#### *Fire events - Case studies*   
   * [321 - Siberian Fires - Summer 2019 - Case study](./30_case_studies/321_Siberian_fires_summer_2019_case_study.ipynb)
   * [322 - Californian Fires - Summer 2020 - Case study](./30_case_studies/322_Californian_fires_summer_2020_case_study.ipynb)

#### *Sentinel-3 SLSTR NRT data - Case studies*
   * [331 - Sentinel-3 SLSTR NRT FRP - Chernobyl fires - Case study](./30_case_studies/331_Sentinel-3_SLSTR_NRT_FRP_Chernobyl_fires_case_study.ipynb)
   * [332 - Sentinel-3 SLSTR NRT FRP - Californian fires - Case study](./30_case_studies/332_Sentinel-3_SLSTR_NRT_FRP_Californian_fires_case_study.ipynb)
   * [333 - Sentinel-3 SLSTR NRT AOD - Californian fires - Case study](./30_case_studies/333_Sentinel-3_SLSTR_NRT_AOD_Californian_fires_case_study.ipynb)

#### *Antarctic ozone hole anomaly - Summer 2019*
   * [341 - Antarctic ozone hole anomaly - Summer 2019 - Case study](./30_case_studies/341_Ozone_hole_anomaly_case_study.ipynb)
   * [342 - Antarctic ozone hole anomaly - Summer 2019 - CAMS Animation - Case study](./30_case_studies/342_Ozone_hole_anomaly_2019_case_study_cams_animation.ipynb)

#### *COVID-19 case study - GOME-2 and Sentinel-5p anomaly maps and time-series analysis*
   * [351 - COVID-19 - GOME-2 anomaly map](./30_case_studies/351_COVID-19_case_study_GOME-2_anomaly_map.ipynb)
   * [352 - COVID-19 - GOME-2 time-series analysis](./30_case_studies/352_COVID-19_case_study_GOME-2_time_series.ipynb)
   * [353 - COVID-19 - Sentinel-5P anomaly map](./30_case_studies/353_COVID-19_case_study_Sentinel-5P_anomaly_map.ipynb)
   * [354 - COVID-19 - Sentinel-5P time-series analysis](./30_case_studies/354_COVID-19_case_study_Sentinel-5P_time_series.ipynb)


<br>

### <a id='exercises'></a>40 - EXERCISES

#### *Sentinel-5P - Exercises*
   * [411 - Sentinel-5P Level 2 - Exercise](./40_exercises/411_Sentinel-5P_L2_exercise.ipynb)

#### *Sentinel-3 - Exercises*
   * [421 - Sentinel-3 OLCI Level 1 - Exercise](./40_exercises/421_Sentinel-3_OLCI_L1_exercise.ipynb)
   * [422 - Sentinel-3 SLSTR NRT FRP - Exercise](./40_exercises/422_Sentinel-3_SLSTR_NRT_FRP_exercise.ipynb)
   * [423 - Sentinel-3 SLSTR NRT AOD - Exercise](./40_exercises/423_Sentinel-3_SLSTR_NRT_AOD_exercise.ipynb)

#### *Copernicus Atmosphere Monitoring Service - Exercises*
   * [431 - CAMS EAC4 - Exercise](./40_exercises/431_CAMS_EAC4_exercise.ipynb)

<br>


**NOTE:** Throughout the course, general functions to `load`, `re-shape`, `process` and `visualize` the datasets are defined. These functions are re-used when applicable. The [functions notebook](./functions.ipynb) gives you an overview of all the functions defined and used for the course.

If a notebook makes use of these functions, they are loaded as **helper functions** at the beginning of the notebook. With `?function_name`, you can load the function's docstring to see what it does and which keyword arguments the function requires.
See the example to load the docstring of the function [visualize_pcolormesh](./functions.ipynb#visualize_pcolormesh):

`%run ./functions.ipynb`<br>
`?visualize_pcolomesh`


## Learning outcomes
The course is designed for `medium-level users`, who have basic Python knowledge and understanding of Atmospheric composition data.

After the course, you should have:
* an idea about the **different datasets on Atmospheric Composition data**,
* knowledge about the most useful **Python packages** to handle, process and visualise large volumes of Earth Observation data
* an idea about different **data application areas**

## How to use this course material
This course material is made available via EUMETSAT's EUMETlab training space on
GitLab. While GitLab offers integrated rendering of Jupyter Notebooks, it's 
rendering capabilities is limited. Thus, the notebooks, if directly rendered on
GitLab, might appear not in a nice format, which make the learning process
difficult.

There are several ways how to use these modules:
1. **[nbviewer](https://nbviewer.jupyter.org/)** - Static rendering of the 
notebooks. Follow this [link](https://nbviewer.jupyter.org/urls/gitlab.eumetsat.int/eumetlab/atmosphere/atmosphere/raw/master/00_index.ipynb) 
into nbviewer.
2. **Clone this repo** and run the notebooks on your local Jupyter notebook
server. If you prefer this solution, you have to reproduce the settings. The following
section provides you more information on how to reproduce the set up on your 
local machine.
3. **LTPy JupyterHub** - You can create an 
account [here](https://login.ltpy.adamplatform.eu/) and then log into the
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


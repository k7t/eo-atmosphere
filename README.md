# LTPy - Learning tool for Python on Atmospheric Composition Data

**LTPy - Learning tool for Python on Atmospheric Composition Data** is a Python-based training course on Atmospheric Composition Data. The training course covers [10 - DATA ACCESS](./10_data_access/), [20 - DATA DISCOVERY](./20_data_discovery/), [30 - CASE STUDIES](./30_case_studies/) and [40 - EXERCISES](./40_exercises/) of satellite- and model-based data on Atmospheric Composition.

The course is based on [Jupyter notebooks](https://jupyter.org/), which allow for a high-level of interactive learning, as code, text description and visualisation is combined in one place. If you have not worked with `Jupyter Notebooks` before, you can look at the module [01 - Python and Project Jupyter 101](./01_Python_and_Jupyter_101.ipynb) to get a short introduction to Jupyter notebooks and their benefits.


## Data on Atmospheric Composition
This course features the following **satellite** data:
* `Metop-A/B GOME-2 Level 2` data
* `Metop-A/B GOME-2 Level 3` reprocessed and regridded data
* `Polar Multi-Sensor Aerosol Optical Properties (PMAp) Level 2` data
* `Metop-A/B IASI Level 2` data
* `Copernicus Sentinel-5P TROPOMI Level 2` data
* `Copernicus Sentinel-3 OLCI Level 1B` data
* `Copernicus Sentinel-3 SLSTR NRT FRP Level 2` data
* `Copernicus Sentinel-3 SLSTR NRT AOD Level 2` data

And the following **model-based** data:
* `Copernicus Atmosphere Monitoring Service (CAMS) Global Reanalysis (EAC4)` data
* `Copernicus Atmosphere Monitoring Service (CAMS) Global Fire Assimilation System (GFAS)` data
* `Coperncus Emergency Management Service (CEMS) Global ECMWF Fire Forecast (GEFF)` data



## Course material
The course follows a modular approach and offers modules on:

### <a id='data_acces'></a>10 - DATA ACCESS

 * [11 - Atmospheric Composition data overview and acccess](./10_data_access/11_ac_data_access_overview.ipynb)
 * [12 - WEkEO Harmonized Data Access API](./10_data_access/12_WEkEO_harmonized_data_access_api.ipynb)


### <a id='data_discovery'></a>20 - DATA DISCOVERY

##### *Metop-A/B/C GOME-2 Level 2 and Level 3 data*
   * [211 - Metop-A GOME-2 - Tropospheric NO<sub>2</sub> - Level 2 - Load and browse](./20_data_discovery/211_Metop-A_GOME-2_NO2Tropo_L2_load_browse.ipynb)
   * [212 - Metop-A/B GOME-2 - Tropospheric NO<sub>2</sub> - Level 2 - Pre-process](./20_data_discovery/212_Metop-AB_GOME-2_NO2Tropo_L2_preprocess.ipynb)
   * [213 - Metop-A/B GOME-2 - Tropospheric NO<sub>2</sub> - Level 3 - Load and browse](./20_data_discovery/213_Metop-AB_GOME-2_NO2Tropo_L3_load_browse.ipynb)
   * [214 - Metop-A/B/C GOME-2 - Absorbing Aerosol Index - Level 3 - Load and browse](./20_data_discovery/214_Metop-ABC_GOME-2_AAI_L3_load_browse.ipynb)

##### *Polar Multi-Sensor Aerosol Optical Properties (PMAp) Level 2 data*
   * [221 - Polar Multi-Sensor Aerosol Optical Properties (PMAp) - Aerosol Optical Depth - Level 2 - Load and browse](./20_data_discovery/221_PMAp_AOD_L2_load_browse.ipynb)

##### *Metop-A/B IASI Level 2 data*
   * [231 - Metop-A/B IASI - Ammonia (NH<sub>3</sub>) - Level 2 - Load and browse](./20_data_discovery/231_Metop-AB_IASI_NH3_L2_load_browse.ipynb)

##### *Sentinel-5P TROPOMI Level 2 data*
   * [241 - Sentinel-5P TROPOMI - Carbon Monoxide - Level 2 - Load and browse](./20_data_discovery/241_Sentinel-5P_TROPOMI_CO_L2_load_browse.ipynb)

##### *Sentinel-3 data*
   * [251 - Sentinel-3 OLCI - Radiances - Level 1 - Load and browse](./20_data_discovery/251_Sentinel-3_OLCI_radiance_L1_load_browse.ipynb)
   * [252 - Sentinel-3 SLSTR NRT - Fire Radiative Power (FRP) - Level 2 - Load and browse](./20_data_discovery/252_Sentinel-3_SLSTR_NRT_FRP_L2_load_browse.ipynb)
   * [253 - Sentinel-3 SLSTR NRT - Aerosol Optical Depth (AOD) - Level 2 - Load and browse](./20_data_discovery/253_Sentinel-3_SLSTR_NRT_AOD_L2_load_browse.ipynb)

##### *Copernicus Atmosphere Monitoring Service (CAMS) data*
   * [261 - CAMS Global reanalysis (EAC4) - Organic Matter Aerosol Optical Depth - Load and browse](./20_data_discovery/261_CAMS_EAC4_OMAOD_load_browse.ipynb)
   * [262 - CAMS Global Fire Assimilation System (GFAS) - Fire Radiative Power - Load and browse](./20_data_discovery/262_CAMS_GFAS_FRPFIRE_load_browse.ipynb)

##### *Copernicus Emergency Management Service (CEMS) data*
   * [271 - CEMS Global ECMWF Fire Forecast - Fire Weather Index - Load and browse](./20_data_discovery/271_CEMS_GEFF_FWI_load_browse.ipynb)
   * [272 - CEMS Global ECMWF Fire Forecast - Fire Weather Index - Harmonized Danger Classes](./20_data_discovery/272_CEMS_GEFF_FWI_harmonized_danger_classes.ipynb)
   * [273 - CEMS Global ECMWF Fire Forecast - Fire Weather Index - Custom Danger Classes](./20_data_discovery/273_CEMS_GEFF_FWI_custom_danger_classes.ipynb)


### <a id='case_studies'></a>30 - CASE STUDIES

##### *Fires*
   * [311 - Amazon fires 2019](./30_case_studies/311_fire_amazon_2019.ipynb)
   * [312 - Siberian fires 2019](./30_case_studies/312_fire_siberia_2019.ipynb)
   * [313 - Californian fires 2020](./30_case_studies/313_fire_california_2020.ipynb)
   * [314 - Chernobly fires 2020 - Sentinel-3 SLSTR NRT - Fire Radiative Power](./30_case_studies/314_fire_chernobyl_2020_Sentinel-3_SLSTR_NRT_FRP_L2.ipynb)
   * [315 - Californian fires 2020 - Sentinel-3 SLSTR NRT - Fire Radiative Power](./30_case_studies/315_fire_california_2020_Sentinel-3_SLSTR_NRT_FRP_L2.ipynb)
   * [316 - Californian fires 2020 - Sentinel-3 SLSTR NRT - Aerosol Optical Depth](./30_case_studies/316_fire_california_2020_Sentinel-3_SLSTR_NRT_AOD_L2.ipynb)

##### *Air pollution*   
   * [321 - Map and time-series analysis - Metop-A/B GOME-2 - Tropospheric NO<sub>2</sub>](./30_case_studies/321_air_pollution_map_time-series_Metop-AB_GOME-2_NO2Tropo_L3.ipynb)
   * [322 - Produce gridded dataset - Metop-A/B GOME-2 - Tropospheric NO<sub>2</sub>](./30_case_studies/322_air_pollution_produce_gridded_Metop-AB_GOME-2_NO2Tropo_L2.ipynb)
   * [323 - Create an anomaly map - Europe - Metop-A/B GOME-2 - Tropospheric NO<sub>2</sub>](./30_case_studies/323_air_pollution_map_europe_2020_Metop-AB_GOME-2_NO2Tropo_L2.ipynb)
   * [324 - Time-series analysis - Europe - Metop-A/B GOME-2 - Tropospheric NO<sub>2</sub>](./30_case_studies/324_air_pollution_time-series_europe_2020_Metop-AB_GOME-2_NO2Tropo_L2.ipynb)
   * [325 - Create an anomaly map - Europe - Sentinel-5P TROPOMI - Tropospheric NO<sub>2</sub>](./30_case_studies/325_air_pollution_map_europe_2020_Sentinel-5P_TROPOMI_NO2Tropo_L2.ipynb)
   * [326 - Time-series analysis - Europe - Sentinel-5P TROPOMI - Tropospheric NO<sub>2</sub>](./30_case_studies/326_air_pollution_time-series_europe_2020_Sentinel-5P_TROPOMI_NO2Tropo_L2.ipynb)

##### *Stratospheric Ozone*
   * [331 - Antarctic ozone hole - Summer 2019](./30_case_studies/331_stratospheric_ozone_2019.ipynb)
   * [332 - Antarctic ozone hole - CAMS animation - Summer 2019](./30_case_studies/332_stratospheric_ozone_animation_2019.ipynb)


### <a id='exercises'></a>40 - EXERCISES

##### *Sentinel-5P TROPOMI*
   * [411 - Sentinel-5P TROPOMI - Carbon Monoxide - Level 2](./40_exercises/411_Sentinel-5P_TROPOMI_CO_L2_exercise.ipynb)

##### *Sentinel-3*
   * [421 - Sentinel-3 OLCI - Radiances - Level 1](./40_exercises/421_Sentinel-3_OLCI_radiance_L1_exercise.ipynb)
   * [422 - Sentinel-3 SLSTR NRT - Fire Radiative Power](./40_exercises/422_Sentinel-3_SLSTR_NRT_FRP_L2_exercise.ipynb)
   * [423 - Sentinel-3 SLSTR NRT - Aerosol Optical Depth](./40_exercises/423_Sentinel-3_SLSTR_NRT_AOD_L2_exercise.ipynb)

##### *Copernicus Atmosphere Monitoring Service*
   * [431 - CAMS Global Reanalysis (EAC4) - Total Column Carbon Monoxide](./40_exercises/431_CAMS_EAC4_tcco_exercise.ipynb)

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

## Reproduce LTPy on Atmospheric Composition data locally
In case you wish to reproduce the course modules on your local setup, the 
following Python version and Python packages will be required:

* Python version: **Python3.8**
* Python packages: see [requirements.txt](./requirements.txt)

Python packages can be installed with:
`pip install -r requirements.txt`. 

The `eodata` folder with all the data required for the training course can be accessed and downloaded from [https://sftp.eumetsat.int](https://sftp.eumetsat.int/login). Find the user name and password in order to be able to login [here](./sftp_login.txt).


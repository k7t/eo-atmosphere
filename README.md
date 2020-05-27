# LTPy - Learning tool for Python on Atmospheric Composition Data

**LTPy - Learning tool for Python on Atmospheric Composition Data** is a 
Python-based training course on Atmospheric Composition Data. The training 
course covers modules on `data access`, `data handling and processing`, 
`data visualisation` as well as `case studies` of satellite- and model-based data 
on Atmospheric Composition.

The course is based on [Jupyter notebooks](https://jupyter.org/), which allow
a high-level of interactive learning, as code, text description and visualisation 
is combined in one place. If you have not worked with `Jupyter Notebooks` before, 
you can look at the module [01 - Introduction to Python and Project Jupyter](./01_ltpy_Intro_to_Python_and_Jupyter.ipynb) 
to get a short introduction to Jupyter notebooks and their benefits.

## Data on Atmospheric Composition
This course features the following data:

* [AC SAF GOME-2 Level-2](./11_ltpy_atmospheric_composition_overview.ipynb#ac_saf) data onboard of Metop-A and Metop-B satellites
* [AC SAF GOME-2 Level-3](./11_ltpy_atmospheric_composition_overview.ipynb#records) reprocessed and regridded data
* [IASI Level-2](./11_ltpy_atmospheric_composition_overview.ipynb#ac_saf) data onboard of Metop-A and Metop-B satellites
* [Copernicus Sentinel-5P](./11_ltpy_atmospheric_composition_overview.ipynb#sentinel_5p) data
* [Copernicus Sentinel-3 OLCI](./11_ltpy_atmospheric_composition_overview.ipynb#sentinel3) data
* [Copernicus Atmosphere Monitoring Service (CAMS)](./11_ltpy_atmospheric_composition_overview.ipynb#cams) data


## Course material
The course follows a modular approach and offers the following modules:

***01 - [Introduction to Python and Project Jupyter](./01_ltpy_Intro_to_Python_and_Jupyter.ipynb)*** *(optional)*

**1 - Overview of data and data access systems**
 * [11 - Atmospheric Composition data overview and acccess](./11_ltpy_atmospheric_composition_overview.ipynb)
 * [12 - WEkEO Harmonized Data Access API](./12_ltpy_WEkEO_harmonized_data_access_api.ipynb)

**2 - Load, browse and pre-process data**
 * [2.1.1 - AC SAF GOME-2 - Level 2 data - Load and browse](./211_ltpy_AC_SAF_GOME-2_L2_load_browse.ipynb)
 * [2.1.2 - AC SAF GOME-2 - Level 2 data - Pre-process](./212_ltpy_AC_SAF_GOME-2_L2_preprocess.ipynb)
 * [2.1.3 - IASI - Level 2 data - Load and browse](./213_ltpy_IASI_L2_load_browse.ipynb)
 * [2.2 - AC SAF GOME-2 - Level 3 data](./22_ltpy_AC_SAF_GOME-2_L3.ipynb)
 * [2.3 - Sentinel-5p Level 2 data](./23_ltpy_Sentinel5p_L2_data.ipynb)
 * [2.4 - Copernicus Atmosphere Monitoring Service (CAMS) data](./24_ltpy_CAMS_data.ipynb)
 * [2.5 - Sentinel-3 OLCI Level 2 data](./25_ltpy_Sentinel3_OLCI_L1.ipynb)

**3 - Data workflows and case studies**
 * [3.1 - AC SAF GOME-2 - Level 2 data - Case studies](./31_ltpy_AC_SAF_GOME-2_L2_case_study.ipynb)
 * [3.2 - AC SAF GOME-2 - Level 3 data - Workflow examples](./32_ltpy_AC_SAF_GOME-2_L3_case_study.ipynb)
 * [3.3 - Siberian Fires Summer 2019 - Case Study](./33_ltpy_Siberian_Fires_case_study.ipynb)
 * [3.4.1 - Antarctic ozone hole - Summer 2019 - Case Study](./341_ltpy_Ozone_hole_case_study.ipynb)
 * [3.4.2 - Antarctic ozone hole - Summer 2019 - Animation](./342_ltpy_Ozone_hole_case_study_cams_animation.ipynb)


**NOTE:** Throughout the course, general functions to `load`, `re-shape`, `process` and `visualize` 
the datasets are defined. These functions are re-used when applicable. 
The [LTPy functions notebook](./ltpy_functions.ipynb) gives you an overview of 
all the functions defined and used for the course.

The notebook [12 - WEkEO Harmonized Data Access API](./12_ltpy_WEkEO_harmonized_data_access_api.ipynb) 
makes use of functions defined in the [LTPy HDA API functions notebook](./ltpy_hda_api_functions.ipynb).


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


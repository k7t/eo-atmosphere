---
title: 'LTPy - Learning tool for Python on Atmospheric Composition'
tags:
  - Python
  - Jupyter notebooks
  - atmospheric composition
  - Copernicus
  - open data
authors:
  - name: Julia Wagemann
    orcid: 0000-0002-3075-2559
    affiliation: 1
  - name: Simone Mantovani
    orcid: 0000-0003-3979-3645
    affiliation: 2
    - name: Federico Fierli
    orcid: 0000-0001-9975-2883
    affiliation: 3
affiliations:
 - name: Philipps University of Marburg
   index: 1
 - name: Meteorological Environmental Earth Observation (MEEO)
   index: 2
 - name: European Organisation for the Exploitation of Meteorological Satellites (EUMETSAT)
   index: 3
date: 20 January 2021
bibliography: paper.bib

---

# Summary
Learning tool for Python (LTPy) is a Python-based series of modules on different open satellite- and model-based data on atmospheric pollution and climate . LTPy features eleven different datasets of the principal European missions including the Copernicus satellites Sentinel-3 and Sentinel-5, as well as from European Polar Satellite with GOME-2 and IASI instruments operated by the European Organisation for the Exploitation of Meteorological Satellites (EUMETSAT). 
The course has the aim to facilitate the uptake and use of atmospheric composition data as well as showcasing possible application areas.
LTPy is based on Jupyter notebooks, which allow for a high-level of interactive learning, as code, text description and visualisation is combined in one place. The structure of the course is aligned with a typical data analysis workflow and includes modules on data access, data discovery, case studies and exercises.
LTPy consists of a total of 37 Jupyter-based modules which are available on a [Gitlab repository](https://gitlab.eumetsat.int/eumetlab/atmosphere/atmosphere) as well as on a dedicated [LTPy training platform](https://ltpy.adamplatform.eu).

# Statement of need
The field of Earth Observations (EO) has experienced a series of disruptive changes. First, the adoption of open data policies in 2008 has led to an exponential growth in data uptake by users [@Zhu:2019]. Second, technological advancements and new satellite constellations have led to an increase in data volume and variety. One main driver for this is Copernicus, the European Commission’s Earth Observation programme. For instance, in 2019, Copernicus published over 18 Terabytes of Earth Observation data on a daily basis under a full, free and open data policy [@European Space Agency:2020]. This trend is expected to further increase with the upcoming new generation of European programs managed by the European Organisation for the Exploitation of Meteorological Satellites (EUMETSAT). 
These disruptive changes lead naturally to an increase in number of users, but at the same time a much larger community of diverse users is interested in understanding and using the data [@Overpeck:2011; @EuropeanCommission:2019]. In the past, scientists and researchers have been the main users of EO data, whereas now the data attracts non EO experts alike, coming from varied application domains [@Sudmanns:2018]. This holds true especially for data on atmospheric composition, as the data is of interest for users working in different fields, such as fire monitoring, air quality and atmospheric composition monitoring and forecasting, modelling, climate assessment and dust monitoring. 
With the shift from EO expert users to multi-disciplined non-expert users three main challenges arise: (i) users are unaware of the existence of specific data and data products, (ii) users fail to make use of the data due to the diverse ways of data structures, data formats and dissemination channels and (iii) users do not know potential application areas. 
These challenges require data organisations and agencies in charge of data production and dissemination, to develop new training strategies in order to support users to find and make use of the data. There is a growing need for the following requirements: 
* need to address different types of users, such as expert, intermediate and end users
* need to cover a wide range of know-how on EO: general knowledge of EO datasets, detailed data structure, basic analysis and visualization and application examples
* need to combine documentation, concepts and practical coding 
* need to provide technical capabilities / a training platform (including the need to minimize the required bandwidth for users) with access to data to conduct the training, so that learners can focus on the training 
* need to accommodate for different types of training events: in-person training, on-line, synchronous and asynchronous. 

We aimed to address these requirements by creating a Jupyter-based training course with modules on data access, data discovery, case studies and exercises for different types of atmospheric composition data. The modules lead learners step-by-step through a typical data analysis workflow, including data loading, processing and visualization. The systematic use of the same Python libraries and a set of defined functions makes the course accessible to learners with basic and more advanced programming skills alike. Additionally, the training course is available through a [Jupyterhub-based training platform](https://ltpy.adamplatform.eu), where the required Python environment and data is already available. Instead of struggling with preparing the environment on their local machines, learners are able to directly start with the content-based training on atmospheric composition data.

# Learning Objectives and Instructional Design
The learning objectives of the Learning Tool for Python on Atmospheric Composition are threefold. First, it aims to provide a general overview of different satellite data on atmospheric composition in order to facilitate data uptake and use. Second, it aims to provide code examples and step-by-step guides on how to load, process and visualize these data and third, it aims to provide example applications these data can be used for. 

Several design elements support the learner to easily navigate through the training modules and each notebook. Learners are invited to start with the 00_index.ipynb notebook, which introduces the training content and a proposed structure based on the four sections: 10 - Data Access, 20 - Data Discovery, 30 - Case Studies and 40 - Exercises. Each notebook has a navigation pane and a module overview, which allow learners to easily go to individual sections within a notebook and to navigate between notebooks. Further, any module prerequisites or additional content on the same data type are cross-referenced at the beginning of the notebook.

The course is designed for learners who have a basic understanding of geospatial data analysis in a programmatic way and accommodates learners with different levels of Python and coding literacy. An essential part of the LTPy course is a ‘functions’ library, which is a collection of 14 pre-defined functions that support the learner with data loading, pre-processing and visualization. Learners with basic Python knowledge learn Python by applying these functions, where only keyword arguments have to be provided. Learners with more Python experience can examine the functions in a separate notebook or build their own functions.

# Course Content
The  course features training modules for 16 different data sets, divided in eight satellite-based and three model-based data products. See Table 1 for an overview of data products covered. 
The course is organised in four main parts: (i) data access, (ii) data discovery, (iii) case studies and (iv) exercises. The proposed structure reflects a typical data analysis workflow and each part consists of several Jupyter notebooks.

10 - Data Access
Data access modules are in the folder 10_data_access/ and provide an overview of different data access systems and an example how different atmospheric composition data products can be accessed. The data access systems range from pure download services to cloud-based services where data is accessed in a programmatic way.

20 - Data Discovery
Data discovery modules are in the folder 20_data_disovery/. These modules are organised per data product and aim at ‘discovering’ the respective dataset, including its file structure and internal organisation. The modules provide a step-by-step guide to load, pre-process and visualize each dataset.

30 - Case Studies
Case study modules are in the folder 30_case_studies/. These modules are more advanced and have the aim to provide several atmospheric composition application examples. Case study modules often feature several atmospheric composition data types and may focus on different application areas, such as monitoring of fires, the analysis of the Ozone hole anomaly in 2019 or the analysis of Covid-19 impacts in different regions. However, a case study can also feature a technical workflow, showcasing e.g. how to generate gridded climate records (Level 3 products) from Level 2 data.

40 - Exercises
Exercise modules are in the folder 40_exercises/. These modules provide the learner an opportunity to actively practice the learned content. Exercise workbooks contain two types of exercises: (i) coding assignments and (ii) questions. Coding assignments ask to fill in an empty code cell based on the given instructions. Questions ask the learner to reflect on an output and shall encourage the learner to understand the results of code blocks. Exercise workbooks are based upon data discovery modules and learners are advised to go through the respective data discovery module before.

|Data provider|Satellite|Instrument|Product|
|:---|:---|:---|:---|
|EUMETSAT|Metop-A/B/C|GOME-2|- Ozone<br>- Absorbing Aerosol Index<br>- Nitrogen Dioxide|
|EUMETSAT|Metop-A/B/C|IASI|- Ammonia<br>- Carbon Monoxide<br>- Ozone|
|EUMETSAT|Metop-A/B/C|Multi-Instrument|- Polar Multi-Sensor Aerosol Optical Depth (PMAp)|
|Copernicus|Sentinel-5P|TROPOMI|- Carbon Monoxide<br>- Nitrogen Dioxide|
|Copernicus|Sentinel-3|OLCI|- Level 1B RGB|
|Copernicus|Sentinel-3|SLSTR|- Fire Radiative Power (FRP) Near-Real-Time<br>- Absorbing Aerosol Index (AOD) Near-Real-Time|
|Copernicus Atmosphere Monitoring Service (CAMS)|N/A|N/A|- EAC4 reanalysis<br>- Global Fire Assimilation System (GFAS)|
|Copernicus Emergency Management Service (CEMS)|N/A|N/A|- Global ECMWF Fire Forecasts (GEFF)|

# Teaching Experience
We started the training with LTPy in mid 2019 and since then, the modules have been used in around ten [EUMETSAT training activities](https://training.eumetsat.int/) (in-person and virtual). Training events range from short courses spanning only several hours up to a week-long training school and have on average between 50 to 100 learners. By now, more than 500 learners have registered on the LTPy training platform in total and around 50 learners are using it on a regular monthly basis. The training modules have been used during in-person and online training events with an instructor, but are also developed in a way that they can be followed in a self-paced manner. 

Each event included a survey on the usefulness, clarity and ease of access of the training modules and platform. The general feedback is very positive, with gradings in the higher range (very good) and no negative ratings confirming a clear appreciation of the approach. Most recurrent suggestions and specific requests address the need for availability of the material on longer-term, the reproducibility and the possibility to use a shared platform on a continuous basis. The approach has proven to satisfy new training requirements, especially to meet the emerging need to move learning activities online since March 2020.

# Acknowledgements
LTPy has been supported by the Copernicus Programme through EUMETSAT.
We acknowledge contributions from Julien Chimot (EUMETSAT), Claudia Vitolo (ECMWF) and Miha Razinger (ECMWF).


# References
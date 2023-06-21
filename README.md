<a align="left" href="https://github.com/nasa-openscapes/2023-nasa-champions/"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="35px"></a>

# 2023 NASA Openscapes Champions Cohort 

Welcome to the 2023 NASA Openscapes Champions Cohort! This is a Cohort for research teams using NASA Earthdata to learn open science practices and spend time experimenting and planning what their analytical workflows with NASA Earthdata look like in the Cloud. This is part of NASA Openscapes: <https://nasa-openscapes.github.io>. Learn more about Openscapes and the Champions Program: <https://openscapes.org>. 


<img align="right" src="horst-champions-trailhead.png" width="450">  

## Cohort Agendas

We will meet as a Cohort via Zoom five times over two months for 1.5 hours on five Wednesdays starting April 19, 2023:

- **Dates: April 19, May 3, 17, 31, June 14** 
- **Times: 10:00 - 11:30am PT**
- **Location: Remotely, via Zoom**

Agendas are accessible to Cohort participants in our [Cohort Google Drive Folder](https://drive.google.com/drive/folders/1hAge8k2z9OvXB7c2nEg_BQA36Fc1cRLk?usp=sharing); they are also an archive of our live google-docing. Please see <https://openscapes.org/series> to view blank versions of the agendas. 

Date | Cohort Call Topics          | Series Chapters |      Guest Teachers
----| ------------------|----------------------|--------------------------------
04/19 | 1. Openscapes mindset, Better science in less time | [mindset](https://openscapes.github.io/series/mindset), [better science in less time](https://openscapes.github.io/series/better-science.html) | [Jinbo Wang](https://science.jpl.nasa.gov/people/jwang2/), Caltech/JPL; [Allan Just](https://profiles.mountsinai.org/allan-just), Mount Sinai
05/03 | 2. Team culture and data strategies for future us | [team culture](https://openscapes.github.io/series/team-culture), [data strategies for cloud](https://nsidc.github.io/data_strategies_for_future_us/data_strategies_slides#/title-slide) | [Andy Barrett](https://nsidc.org/about/our-people/Andrew_Barrett), NSIDC
05/17 | 3. Open communities and coding strategies for future us | [open communities](https://openscapes.github.io/series/communities), coding strategies for cloud | [Amy Steiker](https://www.linkedin.com/in/amy-steiker-04088448), [Luis Lopez](https://www.linkedin.com/in/betolink/), NSIDC
05/31 | 4. NASA Earthdata Cloud Clinic, hands-on lesson from NASA Mentors |  | [Amy Steiker](https://www.linkedin.com/in/amy-steiker-04088448), NSIDC
06/14 | 5. Pathways share | [Earthdata Cloud Cookbook](https://nasa-openscapes.github.io/earthdata-cloud-cookbook/)  | [Cassie Nickles](https://scienceandtechnology.jpl.nasa.gov/cassandra-nickles), PO.DAAC 

**Cohort Call Digests** are posted as [Discussions](https://github.com/NASA-Openscapes/2023-nasa-champions/discussions) in this repo.


## Coworking times (optional)

Coworking sessions are where we work at the same time together. Sometimes, this means quiet work with check-ins to break up focused work and get feedback, and sometimes this involves asking questions and screensharing to learn and problem solve. Coworking in the weeks between Cohort Calls - May 11, 25, June 8. 10-11:30 PT - alternating Thursdays.


## Participating teams

**CLIMCAPS Team** We use a number of NASA products in [CLIMCAPS](https://airs.jpl.nasa.gov/data/products/climcaps-L2-L3/) to stabilize and improve the retrieval of atmospheric profiles from hyperspectral infrared measurements. These include (i) MERRA-2 and (ii) the MEASURES CAMEL dataset. We distribute CLIMCAPS as Level 2 and Level 3 files to a range of different users. Our research focuses on maintaining/improving the CLIMCAPS algorithm and collaborating with users to improve and tailor CLIMCAPS data products. Since releasing the CLIMCAPS record via GES DISC in 2020 (2002–present), we have seen our user base grow. We have had the chance to collaborate with many groups. This gave us the opportunity to address their questions, clarify the product and help prepare custom Level 3 files that are tailored to target applications. The CLIMCAPS Level 2 product contains many different types of uncertainty metrics that can be used to filter and refine data usage. We would absolutely love the opportunity to make these workflows, that we've helped develop for users, more widely available. I have no doubt that other communities will find it useful also, and we want, in turn, to learn from others. Experience is teaching us that good science happens when developers and scientists collaborate together. And this is why I think cloud-based workflows is one of the most exciting technology advances in recent years.

**HEAT (HydroEnergy Analytics Team)** There is an increasing global demand for food, water and energy mainly driven by rapid urbanization, rising population, economic growth and regional conflicts. As water, energy and food are interconnected and are part of a system, we will adopt an integrated Water-Energy-Food Nexus (W-E-F) approach to examine the interdependence of water, energy and food and the impacts of climate change on water, energy, and food consumption in Nepal. Nepal, a country located in Southeast Asia, presents a unique case, where the datasets are either sparse, extremely challenging to obtain, or unavailable.  Assessing W-E-F Nexus is particularly challenging due to gaps in datasets and lack of long-term observations. NASA’s Earth Observation data can be used to overcome these obstacles by providing ongoing long-term observations of the planet at various spatial and temporal resolutions, effectively  filling in the gaps in the data. Our approach involves utilizing data-driven techniques to analyze the W-E-F nexus at watershed level in Nepal. Specifically, we plan to combine NASA’s Earth Observation data with hydropower generation, agricultural production and socioeconomic data in Nepal to gain a more comprehensive understanding of the W-E-F nexus in the region. We have identified several potential datasets, and will address two major questions in the cohort: 1) How has water availability, hydropower generation and consumption, demographics, crop yield changed in Nepal over the last 20 years? 2) What is the relationship between change in hydropower generation with respect to changes in hydrometeorology and demographics? Outcome: We will develop a Jupyter Notebook that outlines a comprehensive method for generating outputs from data acquisition using a cloud environment. This end-to-end process will be clearly described in the notebook, providing an intuitive and efficient workflow that can be replicated by others adhering to the open science principles. Through this effort, we aim to facilitate the use of cloud computing in data analysis and dissemination, streamlining the research process and enabling more efficient collaboration among researchers.  The final Jupyter Notebook will be shared in the collaborative space (GitHub). The pain points encountered from an interdisciplinary user’s perspective will be documented.

**LASERS Team** Our team has expertise in assessing vegetation biophysical parameters using data from all platforms, terrestrial, airborne and spaceborne. We have experience in using the Google Earth Engine and [ICESat-2](https://icesat-2.gsfc.nasa.gov/) data to produce gridded-maps of canopy height and canopy cover and we have produced open science software tools for displaying and labeling ICESat-2 photons, e.g., PhotonLabeler, or Waveformlidar, both available on GitHub. Our research efforts of producing Landsat-resolution gridded maps of canopy height, canopy cover, and biomass, are limited in scale by using local computing and data download-intensive approaches. Educational accounts on cloud-based platforms, such as GEE, have limitations for data availability, data volume and modeling options, and the learning curve and cost for migrating to platforms like AWS, have their own challenges. As such, we hope that by joining NASA’s Openscapes we’ll remove barriers to producing timely vegetation products at continental and global scales to better answer pressing questions in ecology while empowering students and young scientists to use cloud-computing and open science tools. We use ICESat-2 data, Landsat, and derived data to characterize vegetation structure and estimate biophysical parameters, such as height, cover, biomass. For producing gridded maps of vegetation parameters at scales larger than regional, e.g., continental and global, the volume of data download and processing time are hampering the workflow, therefore we intend to migrate the process to the cloud.

**Geoweaver Team** Our group has a lot of interests and collaboration history with DAACs and the Earth science community, and we are dedicated to developing [Geoweaver](https://github.com/ESIPFed/Geoweaver) to support Earth science teams as well as DAAC staff (data pipeline, ingestion, migration, analytics) to be productive, and their work are tangible and FAIR for other scientists to reproduce. We use NASA data as input variables to AI models to train the models with the ability to discover Earth insights in time and be actionable. We are very interested in migrating the workflow into the cloud because that is where the data is and there are data retrieval and I/O steps in our workflows which are slow if they are executed outside the cloud. By migrating workflows into cloud, we want to experiment and showcase that: (1) scientists can easily switch from their personal computing environments to cloud environment seamlessly and effortlessly using Geoweaver; (2) the hybrid collaboration environment provided by NASA and researchers' home institution, including their laptops, can work together for one single workflow (/purpose) without under-using (wasting) resources; (3) make the building-testing-debugging iteration more quick, useful, transparent, and of course FAIR (Geoweaver records everything people did no matter where) and help scientists get serious about workflow run history sharing in a single zip file; (4) show that Geoweaver is a click-button solution if scientists want to deploy their AI workflows into operational services to run periodically like every day.

**S-MODE Team** Our group has a diversity of professional experience, ranging from graduate students to PI’s. Everyone in our group is interested in exploring open-source workflows on the cloud and building machinery to analyze a variety of data from [S-MODE](https://espo.nasa.gov/s-mode/content/S-MODE) (Sub-Mesoscale Ocean Dynamics Experiment). Our collaboration will benefit the general S-MODE community as we plan on sharing our findings. Our overall goal is to foster a data analysis community for S-MODE by creating machinery that can be used by many research groups. From Mackenzie: “I work with NASA funded saildrone data to investigate submesoscale dynamics of the upper ocean and air-sea interactions. Specifically, I am working with saildrone datasets from the Atlantic Tradewind Ocean Atmosphere Interaction Campaign (ATOMIC) and S-MODE. I analyze the saildrone data using python and Jupyter notebooks. Additionally, I use satellite data from SMAP, Aquarius, and SWOT to provide environmental context on where the saildrone data was collected. I currently download most of the datasets and keep them on my university’s HPC system. I use open-source software to analyze the data, which includes python packages such as Xarray, numpy, matplotlib, cartopy, and pandas.”

**Wen Team** We are highly motivated to migrate our ground validation workflow for the [NASA GPM - Global Precipitation Measurement](https://gpm.nasa.gov/) product to the cloud. With over a decade of experience working with ground weather radar products and developing comprehensive workflows for ground validation work, we are eager to streamline and optimize our process. We use NASA data in three areas. First, we conduct cross-validation between NASA GPM products and NOAA ground weather radar products. Second, we create synergy of multiple NASA remote sensing measurements to achieve better precipitation product. Third, we apply NASA remote sensing data to monitor and forecast natural hazards such as flash flooding, drought, tornado, etc. Our team recognizes the numerous benefits that cloud computing resources can provide. Firstly, cloud services are highly scalable and can easily accommodate changes in demand from other scientists. Secondly, by migrating our workflow to the cloud, we can automate many tasks and improve efficiency while reducing the risk of errors or delays. Thirdly, cloud computing resources are accessible from anywhere with an internet connection, making it easier to collaborate with other scientists. Lastly, cloud services can be integrated with other tools and services, such as machine learning or data analytics platforms, enhancing the overall capabilities of the workflow. We strongly believe that ground validation efforts require a global approach, and migrating our ground validation workflow to the cloud can greatly enhance our ability to collaborate with other scientists and improve our work on a global scale.

**Hepplewhite** We conduct sensor calibration, mission support and support data applications. I work in the [GESTAR2](https://gestar2.umbc.edu/) group (Goddard Earth Sciences Technology and Research II) at UMBC (University of Maryland, Baltimore County). Our team, lead by Dr. Strow with us has been responsible for the development of the CHIRP (Climate Hyperspectral Radiance Product) now being hosted on GESDISC DAAC and intimately concerned with the Aqua AIRS, NOAA CrIS MetOP IASI sensors so that their data can be used for climate studies. We are heavily invested in Matlab with C and Fortran libraries. We deal with 10s of TB data almost daily using the HPC at UMBC - a fantastic resource. There is an interest and growing incentive to migrate to the cloud, but for us the capital (of effort) to 're-locate' is very significant. We need to understand the cost/benefit in our situation. There is a very steep learning curve and very little time available and there isn't a one solution to fit all.


## NASA Openscapes team

**Erin Robinson** (@erinmr), NASA-Openscapes

**Julie Lowndes** (@jules32), NASA-Openscapes

**Stefanie Butland** (@stefaniebutland), Openscapes

**NASA Openscapes Mentors** assisting:

- Amy Steiker, NSIDC DAAC
- Andy Barrett, NSIDC DAAC
- Alexis Hunzinger, GES DISC
- Bri Lind, LP DAAC
- Cassie Nickles, PODAAC
- Catalina Oaida Taglialatela, PODAAC
- Celia Ou, PODAAC
- Chris Battisto, GES DISC
- Jess Welch, ORNL DAAC
- Michele Thornton, ORNL DAAC
- Sargent Shriver, ASF DAAC

## More about Openscapes and the Champions program:

* **[Our path to better science in less time using open data science tools](https://www.nature.com/articles/s41559-017-0160)** (Lowndes et al 2017, _Nature Ecology & Evolution_) - this paper greatly influences the whole Champions program and we’ll ask that everyone participating reads it before our first Cohort Call on JUNE 30. 
* **[Openscapes: Better Science for Future Us](https://docs.google.com/presentation/d/1HGw4P095-lblHiGQHXYidHiVysjrPxuojxTxKtE13vk/edit#slide=id.ge2b7c2f974_0_2017)** - 2021 plenary talk at the Society for Open, Reliable, and Transparent Ecology and Evolutionary biology (SORTEE) inaugural conference 
* **[Openscapes embraces kindness and inclusion in open science](https://sparcopen.org/impact-story/openscapes-embraces-kindness-and-inclusion-of-open-science/)** - 2021 article about Openscapes
* **[openscapes.org](https://openscapes.org/)**


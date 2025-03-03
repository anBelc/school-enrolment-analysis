# UNESCO Primary and Secondary Education Enrolment Analysis

## Overview

This repository contains the data processing scripts for analyzing the UNESCO dataset of primary and secondary education enrolment worldwide combined with the dataset of official languages per country. The goal is to identify which languages should be prioritized in the development of an educational app based on enrolment data.

Since the enrolment data is provided on a per-country basis and not by individual official languages, we split the data by the share of the population speaking each language. Some of the data was sourced from Wikipedia and similar sites, while other data points were estimated based on educated guesses considering various factors.

This repository focuses on **data cleaning**, **joining datasets**, and **preparing the data for Tableau** visualization. The cleaned and prepared data can be further analyzed and visualized to make informed decisions regarding language prioritization in education initiatives.

## Key Features

- **Data Cleaning**: This involves preparing raw data, handling missing values, and ensuring consistency across various datasets.
- **Data Joining**: Merging multiple datasets from different sources to create a unified dataset that can be used for analysis.
- **Data Preparation for Tableau**: Transforming the data into a format suitable for visual exploration and analysis in Tableau.

## Tableau Visualizations

Once the data is cleaned and prepared, it is visualized in Tableau. You can view the visualizations using the link below:

[Primary/Secondary Education Enrolment](https://public.tableau.com/views/PrimarySecondaryEducationEnrolment/Sheet4?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Data Sources

- UNESCO dataset for primary and secondary education enrolment worldwide: [UNESCO Education Data](https://databrowser.uis.unesco.org/view#=UIS-EducationOPRI%3A0%3ASAP.1%2CUIS-EducationOPRI%3A0%3ASAP.1.GLAST%2CUIS-EducationOPRI%3A0%3ASAP.2T3%2CUIS-EducationOPRI%3A0%3ASAP.3%2CUIS-EducationOPRI%3A0%3ASAP.2&geoMode=countries&geoUnits=&browsePath=EDUCATION%2FUIS-EducationOPRI%2Fschool-age-pop&timeMode=range&view=table&chartMode=multiple&chartHighlightSeries=&chartHighlightEnabled=true&indicatorPaths=UIS-EducationOPRI%3A0%3A40035%2CUIS-EducationOPRI%3A0%3A20063%2CUIS-EducationOPRI%3A0%3A20083%2CUIS-EducationOPRI%3A0%3A40044)
- Dataset for official languages per country: [Official Languages Dataset](https://restcountries.com/v3.1/name/india)
- Share of population speaking each language: 
    - Wikipedia
    - Estimated data based on educated guesses and other related datasets.

## License

This repository is provided under an open-source license. Please feel free to use, modify, and contribute to the project.

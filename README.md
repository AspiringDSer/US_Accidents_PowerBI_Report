# US Accidents - PowerBI Report

# Preface 

This README document provides an overview of the **US Accidents Power BI report**, showcasing the data in a meaningful and interactive way. Users are able to slice and dice the data to gain insights, make informed decisions, and craft compelling data-driven narratives. The Power BI report is designed for anyone interested in exploring the `US Accident Dataset` further.

The `US Accidents Dataset` can be used for numerous applications, such as real-time car accident prediction, studying car accident hotspot locations, casualty analysis, extracting cause and effect rules to predict car accidents, and studying the impact of precipitation or other environmental stimuli on accident occurrence. The most recent release of the dataset can also be useful for studying the impact of COVID-19 on traffic behavior and accidents.

# Table of Content 
1. [Motivation](#Motivation)
2. [About the Project](#About-the-Project)
3. [Future Developments](#Future)

# Motivation <a name='Motivation'></a>
With the increasing importance of data cleaning and analysis, I aim to demonstrate my proficiency in Power BI by analyzing the `US Accident Dataset`.

# About the Project <a name='About-the-Project'></a>

![US Accidents - Pic 1](https://github.com/AspiringDSer/US_Accidents_PowerBI_Report/assets/79289892/beb8cacf-5076-48be-8d43-c7643a479e66)

![US Accidents - Pic 2](https://github.com/AspiringDSer/US_Accidents_PowerBI_Report/assets/79289892/dd0a880b-81e5-41a0-b8ce-89d002811481)

![US Accidents - Pic 3](https://github.com/AspiringDSer/US_Accidents_PowerBI_Report/assets/79289892/489091b0-46c9-44e6-8e95-60369d87563d)

Recruiters, please contact me at jzqmah@gmail.com or message me on LinkedIn if you'd like to access the Power BI (.pbix) file or request a live walkthrough. Please note that GitHub has a file size limit of 100 MB.

# The README is currently under construction 

Stay tuned for updates!

## Data Sources

The project's visualizations and analyses are based on [US Accidents (2016-2023) Kaggle Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). 
This is a countrywide car accident dataset that covers **49 states of the USA**. The accident data were collected from **February 2016 to March 2023**, using multiple APIs that provide streaming traffic incident (or event) data. These APIs broadcast traffic data captured by various entities, including the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road networks. The dataset currently contains approximately **7.7 million** accident records. For more information about this dataset, please visit [here](https://smoosavi.org/datasets/us_accidents).

## Data Modelling 

I have utilized **dimensional modeling** to structure the US Accidents dataset, employing the **star schema** to construct both Fact and Dimension Tables. Please refer to `Data Modeling for US Accident Dataset.ipynb` file. I plan to develop the data model in PostgreSQL or MySQL database eventually and integrate it into to the PowerBI Report. 

**Fact Table** 
* `FactAccidents` - FactAccidents.csv

**Dimension Tables**
* `DimWeather` - DimWeather.csv
* `DimTimeofDay` - DimTimeofDay.csv
* `DimLocation` - DimLocation.csv
* `DimBinaryFlag` - DimBinaryFlag.csv
* `DimDate` - Use PowerQuery 

## Screenshots 

## Insights

This section will contain key insights and findings from the analysis of the US Accident dataset. 

# Future Developments <a name='Future'></a>
The US Accidents Power BI report is undergoing further refinement. I plan to continue development in the following areas:
* `Data Modeling`: Develop a data model in PostgreSQL or MySQL database 
* `Dimension Tables`: Add insights regarding Time of Day 

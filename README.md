# Factors related to the accident

Traffic Accident Analysis (2019–2021)


## Introduction

Every year, the National Highway Traffic Safety Administration (NHTSA) publishes the Fatality Analysis Reporting System (FARS), a census of all vehicle collision deaths on public roads. This data collection effort is a partnership between the states and the NHTSA, providing comprehensive information to help address traffic safety issues, assess motor vehicle safety regulations, and measure overall highway safety.

FARS covers collisions that involve a motor vehicle operating on roads normally accessible to the public and result in the death of one or more individuals—either non-motorists or vehicle occupants—within 30 days of the collision. This project uses FARS data for 2019, 2020, and 2021 to explore the relationships between traffic accidents and factors such as gender, age, location, time period, and types of harm.


## Project Objectives

This project analyzes traffic accident data from 2019, 2020, and 2021 with a focus on deriving meaningful insights and providing actionable recommendations to improve traffic safety. The project is structured into the following key components:
	
 1.	Data Collection
	
 •	Gather comprehensive traffic accident data for the years 2019, 2020, and 2021.
	
 •	Include details such as individuals’ gender, age, accident locations (addresses), accident statuses, and time of occurrence.
	
 2.	Data Cleaning and Preparation
	
 •	Standardize and clean the data to ensure consistency.
	
 •	Handle missing values, correct data entry errors, and format data for analysis.
	
 3.	Exploratory Data Analysis (EDA)
	
 •	Descriptive Analysis: Generate statistics on accident characteristics, including total number of accidents per year, distribution by gender and age, and geographic distribution.
	
 •	Temporal Analysis: Examine trends over time, such as daily peaks, changes in accident frequency, and comparisons between daytime and nighttime.
	
 4.	Correlation Analysis
	
 •	Gender Analysis: Investigate how gender influences the likelihood or severity of accidents.
	
 •	Age Analysis: Identify if specific age groups are more prone to traffic accidents.
	
 •	Geospatial Analysis:
	
 •	Use the spData library for geospatial data.
	
 •	Merge the us_states shapefile with aggregated accident data to visualize accident hotspots across the U.S., with a focus on New Jersey.
	
 •	Use faceted visualizations to compare geospatial trends for New Jersey versus other states.
	
 •	Temporal Analysis: Analyze relationships between time periods (e.g., hours of the day, quarters of the year) and accident rates.
	
 •	Type Analysis: Evaluate the frequency of specific accident types and how they differ over the three years.
	
 5.	Insights and Recommendations
	
 •	Derive insights from the analysis, such as demographic risk factors or high-risk times and locations.
	
 •	Develop recommendations to improve traffic safety and design targeted safety campaigns.
	
 6.	Reporting and Visualization
	
 •	Present findings through detailed reports and data visualizations, such as charts, graphs, heatmaps, and faceted geospatial maps using the us_states dataset.
	
 •	Use faceted maps to showcase how accident rates vary across states and time periods.


## Key Findings
	
 1.	Gender Differences in Accidents
	
 •	Males account for a larger proportion of accidents (65.84%), followed by females (32.01%), and unknown gender (2.15%).
	
 •	Females have a higher survival rate in accidents.
	
 2.	Age Group Analysis
	
 •	The 20–29 age group has the highest concentration of accidents in both New Jersey and the U.S., with similar average ages of those involved.
	
 •	Suggests that this trend is widespread, likely requiring systemic interventions.
	
 3.	Peak Accident Hours
	
 •	Peak hours: 4:00 PM–7:59 PM and 8:00 PM–11:59 PM, indicating high activity or risk during these times.
	
 •	Lower counts in the morning, likely due to lower activity or risk.
	
 4.	Seasonal Variations in Traffic Accidents
	
 •	Accidents peak during the third quarter (July–September) and fourth quarter (October–December).
	
 •	Trends may be attributed to increased summer travel and poor weather conditions during the holiday season.
	
 •	Recommendations include enhanced enforcement and public safety initiatives during these periods.
	
 5.	Geospatial Insights
	
 •	Geospatial analysis highlights accident hotspots in New Jersey and across the U.S. using the us_states dataset.
	
 •	Faceted map visualizations provide a detailed comparison of accident rates across states and time periods, making it easier to identify high-risk locations.
	
 6.	Annual Trends in Accident Types
	
 •	Certain crash types, such as rollovers, remain persistently high, highlighting systemic issues.
	
 •	Strategic interventions, such as reviewing vehicle safety standards and road designs, may be required.
	
 7.	Data-Driven Decision-Making
	
 •	Clear visualizations of accident data enable policymakers to identify and prioritize safety issues quickly.
	
 •	Insights into crash timing and nature can help develop predictive models, improve resource allocation, and enhance emergency response plans.


## Tools and Technologies
	
 •	Programming Languages: R.
	
 •	Libraries and Datasets:
	
 •	R: spData (for us_states shapefile dataset).
	
 •	Geospatial Analysis:
	
 •	Used us_states to merge shapefiles with aggregated accident data for map visualizations.
	
 •	Faceted visualizations highlight trends across states and time periods.
	
 •	Data Sources: FARS dataset (2019–2021).


## Future Directions
	
 •	Expand the analysis to include data from additional years for long-term trends.
	
 •	Develop advanced faceted visualizations for more granular geospatial insights.
	
 •	Incorporate machine learning models for predictive accident risk analysis.
	
 •	Conduct deeper analyses on specific accident types or contributing factors (e.g., weather conditions, vehicle types).


## Citation
	
 •	National Highway Traffic Safety Administration (NHTSA).
	
 •	Matthew & Ernani (2022).
	
 •	DOT/NHTSA (n.d.).

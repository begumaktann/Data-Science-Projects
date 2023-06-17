# WiDS Datathon 2022 

## Description
This repository contains the data analysis notebook for the WiDS Datathon 2022, an annual data science competition focused on social impact. The competition is organized by the Women in Data Science (WiDS) Worldwide team, Stanford University, Harvard University IACS, and the WiDS Datathon Committee. The challenge for this year's datathon revolves around addressing the impact of climate change through energy efficiency.


## Dataset and Challenge
The WiDS Datathon 2022 focuses on a prediction task involving approximately 100,000 observations of building energy usage records collected over 7 years across various states in the United States. The dataset consists of building characteristics, weather data, and the energy usage for each building in a given year, measured as Site Energy Usage Intensity (Site EUI). Participants are tasked with predicting the Site EUI for each row, based on the building characteristics and weather data.

The dataset provided includes two files:
- **Train Dataset**: Contains observed values of Site EUI for each row, used for model training.
- **Test Dataset**: Withholds the observed values of Site EUI for each row, to be used for evaluation and submission of predictions.

## External Data Usage
While the competition can be tackled without the use of external data, participants have the option to incorporate additional external data for building predictive models. However, due to anonymization, joining external data to the competition data may be challenging.

## Data Dictionary
The dataset consists of the following covariates:

- `id`: Building ID
- `Year_Factor`: Anonymized year of weather and energy usage factors observation
- `State_Factor`: Anonymized state where the building is located
- `building_class`: Building classification
- `facility_type`: Building usage type
- `floor_area`: Floor area (in square feet) of the building
- `year_built`: Year of construction of the building
- `energy_star_rating`: Energy star rating of the building
- `ELEVATION`: Elevation of the building location
- `january_min_temp`: Minimum temperature in January (in Fahrenheit) at the building location
- `january_avg_temp`: Average temperature in January (in Fahrenheit) at the building location
- `january_max_temp`: Maximum temperature in January (in Fahrenheit) at the building location
- `cooling_degree_days`: Cooling degree days, indicating the number of degrees where the daily average temperature exceeds 65 degrees Fahrenheit, summed for each month
- `heating_degree_days`: Heating degree days, indicating the number of degrees where the daily average temperature falls under 65 degrees Fahrenheit, summed for each month
- `precipitation_inches`: Annual precipitation in inches at the building location
- `snowfall_inches`: Annual snowfall in inches at the building location
- `snowdepth_inches`: Annual snow depth in inches at the building location
- `avg_temp`: Average temperature over a year at the building location
- `days_below_30F`: Total number of days below 30 degrees Fahrenheit at the building location
- `days_below_20F`: Total number of days below 20 degrees Fahrenheit at the building location
- `days_below_10F`: Total number of days below 10 degrees Fahrenheit at the building location
- `days_below_0F`: Total number of days below 0 degrees Fahrenheit at the building location
- `days_above_80F`: Total number of days above 80 degrees Fahrenheit at the building location
- `days_above_90F`: Total number of days above 90 degrees Fahrenheit at the building location
- `days_above_100F`: Total number
- and Target: `site_eui`: Site Energy Usage Intensity is the amount of heat and electricity consumed by a building as reflected in utility bills
For more information, please visit the [WiDS Datathon 2022 website](https://www.widsconference.org/datathon.html).

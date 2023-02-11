# Tanzania Water Wells Project
![Life Needs Water](https://lifeneedswater.org/wp-content/uploads/2019/03/Brunnenprojekt-Sinja-Tansania-Afrika-01_Life-needs-Water.jpg)
## Project Overview
The goal of this project is to analyze the data provided and advise the Tanzanian Government on the functionality of the wells, which wells to repair and come up with a format or pattern to build new ones.

## Data Features
The following features are included in the data set:

amount_tsh - Total static head (amount water available to waterpoint)
date_recorded - The date the row was entered
funder - Who funded the well
gps_height - Altitude of the well
installer - Organization that installed the well
longitude - GPS coordinate
latitude - GPS coordinate
wpt_name - Name of the waterpoint if there is one
num_private -
basin - Geographic water basin
subvillage - Geographic location
region - Geographic location
region_code - Geographic location (coded)
district_code - Geographic location (coded)
lga - Geographic location
ward - Geographic location
population - Population around the well
public_meeting - True/False
recorded_by - Group entering this row of data
scheme_management - Who operates the waterpoint
scheme_name - Who operates the waterpoint
permit - If the waterpoint is permitted
construction_year - Year the waterpoint was constructed
extraction_type - The kind of extraction the waterpoint uses
extraction_type_group - The kind of extraction the waterpoint uses
extraction_type_class - The kind of extraction the waterpoint uses
management - How the waterpoint is managed
management_group - How the waterpoint is managed
payment - What the water costs
payment_type - What the water costs
water_quality - The quality of the water
quality_group - The quality of the water
quantity - The quantity of water
quantity_group - The quantity of water
source - The source of the water
source_type - The source of the water
source_class - The source of the water
waterpoint_type - The kind of waterpoint
waterpoint_type_group - The kind of waterpoint

## Data Analysis
The first step in analyzing the data is to clean and preprocess the data. This involves handling missing values, converting categorical variables into numerical ones, and dealing with any outliers or inconsistencies in the data.

Next, statistical methods such as regression analysis and decision trees will be used to predict the functionality of the wells. This information will then be used to recommend which wells should be repaired and which new wells should be constructed.

It is important to keep in mind that the decisions made based on the analysis should be practical and feasible for the Tanzanian government to implement. It is also crucial to ensure that the privacy of the data is protected and that any sensitive information is not disclosed.

## Conclusion
From the above models, it is safe to pick the random forests model as it has the highest accuracy scores of the three.

This in turn suggests that most wells are functional and well managed. We can conclude that there are also quite a huge number of non-functional wells that need repair

## Recomendations
The government to increase the number of wells within the country
More funding is required to build, operate and maintain new wells the Tanzanian government in making informed decisions about the repair and construction of new wells.



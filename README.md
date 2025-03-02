# Lowe's Location Analysis
![Introductory Picture](Lowes_Logo.png)
This project is conducted to analyze the location data of Lowe's home improvement stores. The purpose of this project is to determine which variables will influence the number of Lowe's stores built in a location.

## Problem Statement
This project uses data regarding the location of Lowes stores and census data to help determine what variables are most important in determining the location of Lowe's stores. This data may be used to help determine future location of Lowe's stores.

## Skills Demonstrated
* Python
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Histograms
* Bar Chart
* Scatter Plot
* Correlation Matrix
* Linear Regression
* Tableau
* Dashboard

## Data Sourcing
The data used for this analysis is provided by Eric Schulman. The dataset includes location data for Lowe's and Home Depot stores, census data, and location for Lowe's and Home Depot warehouses. A copy of the data is located in [this website](https://www.kaggle.com/datasets/erichschulman/home-improvement-stores/). The dataset used in this project is entry_loc2.csv and consists of 70 columns.
* Unnamed - Contains index numbers.
* Unnamed: 0 - Contains index numbers.
* city - The name of the city or town the store is located in.
* state - A number used to represent a state.
* HD - The number of Home Depot stores located in an area.
* LOW - The number of Lowe's stores located in an area.
* population - The population of the city or town.
* income_per_caita - The average income per person.
* under44_1 - People ages 18-24.
* under44_2 - People ages 25-34.
* under44_3 - People ages 35-44.
* under65_1 - People over 65 (age range unknown).
* under_65_2 - People over 65 (age range unknown).
* STUSAB - State abbreviation.
* STATE_NAME - Name of State.
* STATENS - An ID given to states for census purposes.
* lat - The latitude of the city or town.
* lon - The longitude of the city or town.
* low_dist - Straight line distance to the Lowe's headquarters.
* hd_dist - Straight line distance to the Home Depot headquarters.
* lat_long - The latitude and longitude of the city or town.
* Columns 22 to 68 show the distance to a specific warehouse. For example, the columm labeled LOW - Mount Vernon shows the distance to the Lowe's warehouse in Mount Vernon.
* low warehouse distance - The distance to the nearest Lowe's warehouse.
* hd warehouse distance - The distance to the nearest Home Depot warehouse.

## Project Results
This project was conducted on Kaggle.com. [Click here](https://www.kaggle.com/code/jameschunweber/lowe-s-location-analysis-python-and-tableau) to be taken to the notebook which contains the full details of the project, including findings, and conclusions.

A dashboard was created to summarize relevant findings from this project using Tableau. [Click here](https://public.tableau.com/views/LowesLocationAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) to be taken to the dashboard. A copy of the dashboard is included in this repository under the file name: Lowes_Dashboard.png.

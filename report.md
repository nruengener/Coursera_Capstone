# Coursera_Capstone
applied data science capstone

## Introduction/Business Problem
### Problem Description
This project investigates where in Toronto an investment in apartments or real estate would be most sensible.
The apartments should have a high standard and be rented to wealthy customers. For this an environment 
characterised by low crime rates, high social status and sufficient cultural and entertainment opportunities 
is suitable.  
To identify these locations, the neighborhoods of Toronto are analyzed using different datasets containing information 
about the above mentioned characteristics.  

### Target Audience
The target group of this project are private and commercial investors who think about buying buy real estate in Toronto.
The investigations made in this project help the target group to find suitable locations and objects for investments.

## Data
Different data sources are used to get enough information for decision building. These sources include:

* Toronto Crime Data:  
Major Crime Indicators (MCI) from the years 2014 to 2018 (downloaded from http://data.torontopolice.on.ca). This dataset
includes information of all recorded crime incidents of the categories Assault, Break and Enter, Robbery, Auto Theft an Theft Over.
Each incidents also includes coordinates (latitude and longitude), date, neighborhood and others.  
To simplify the process, all crimes in a neighborhood will be summed up and only the total crime rate will be considered.
But this value will provide sufficient information about the security of a district or neighborhood.

* Demographic Data:  
This dataset contains demographic information about the neighborhoods in Toronto and is loaded 
from https://en.wikipedia.org/wiki/Demographics_of_Toronto_neighbourhoods.
Data like population, average income, density (people/km²) or transit commuting is provided.  
Interesting for a high-quality living ambiance are especially the average income and the density of the neighborhoods.

* Venue Data:  
The Foursquare API (https://developer.foursquare.com) is used to explore information about available venues in the 
neighborhoods provided by the other datasets.
For each neighborhood in Toronto details about available venues including their names, categories and locations are fetched.
 
Before continuing the datasets are cleaned, e. g. not all venue categories are considered. After that the different sets
are combined into one dataset for further processing and analysis steps.

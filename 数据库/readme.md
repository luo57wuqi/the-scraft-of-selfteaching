# Human Development Index - Data package

This data package contains the data that powers the chart ["Human Development Index"](https://ourworldindata.org/grapher/human-development-index?tab=chart&time=1993..2022&showSelectionOnlyInTable=1&country=~CHN&v=1&csvType=filtered&useColumnShortNames=false) on the Our World in Data website. It was downloaded on March 28, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:
country: , CHN
tab: chart
time: 1993..2022
showSelectionOnlyInTable: 1

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Human Development Index
The HDI is a summary measure of key dimensions of human development: a long and healthy life, a good education, and a decent standard of living. Higher values indicate higher human development.
Last updated: April 9, 2024  
Next update: April 2025  
Date range: 1990–2022  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
UNDP, Human Development Report (2024) – with minor processing by Our World in Data

#### Full citation
UNDP, Human Development Report (2024) – with minor processing by Our World in Data. “Human Development Index – UNDP” [dataset]. UNDP, Human Development Report, “Human Development Report 2023-2024” [original data].
Source: UNDP, Human Development Report (2024) – with minor processing by Our World In Data

### What you should know about this data
* Each of the dimensions of the HDI is measured with four indicators: a long and healthy life is measured by _life expectancy at birth_, good education (knowledge) is measured by two indicators, _expected_ and _mean_ _years of schooling_; and a decent standard of living is measured by _Gross National Income (GNI) per capita_, logarithmized to reflect that incomes become less important as they increase.
* The index is then calculated by normalizing and aggregating the indicators. First, the indicators are brought onto the same scale, ranging from 0 to 1. This is done by setting minimum and maximum values for each indicator, and a country at or below the minimum value receiving a score of 0, and a country at or above the maximum value receiving a score of 1.
* The minimum and maximum values for each indicator are defined as follows: _Life expectancy at birth_ ranges between 20 and 85 years; _expected years of schooling_ between 0 and 18 years; _mean years of schooling_, between 0 and 15 years; and _GNI per capita_ between 100 and 75,000 international-$ at 2017 prices.
* The HDI is then estimated as the geometric mean of these indices, or _HDI = (Health index * Education index * Income index)^(1/3)_. The education index is the arithmetic mean (average) of the mean years of schooling and expected years of schooling.

### How is this data described by its producer - UNDP, Human Development Report (2024)?
The Human Development Index (HDI) is a summary measure of average achievement in key dimensions of human development: a long and healthy life, being knowledgeable and having a decent standard of living. The HDI is the geometric mean of normalized indices for each of the three dimensions.

The health dimension is assessed by life expectancy at birth, the education dimension is measured by mean of years of schooling for adults aged 25 years and more and expected years of schooling for children of school entering age. The standard of living dimension is measured by gross national income per capita. The HDI uses the logarithm of income, to reflect the diminishing importance of income with increasing GNI. The scores for the three HDI dimension indices are then aggregated into a composite index using geometric mean. Refer to Technical notes for more details.

The HDI can be used to question national policy choices, asking how two countries with the same level of GNI per capita can end up with different human development outcomes. These contrasts can stimulate debate about government policy priorities.

The HDI simplifies and captures only part of what human development entails. It does not reflect on inequalities, poverty, human security, empowerment, etc. The HDRO provides other composite indices as broader proxy on some of the key issues of human development, inequality, gender disparity and poverty.

A fuller picture of a country's level of human development requires analysis of other indicators and information presented in the HDR statistical annex.

### Source

#### UNDP, Human Development Report – Human Development Report
Retrieved on: 2024-04-09  
Retrieved from: https://hdr.undp.org/  

#### Notes on our processing step for this indicator
We calculated averages over continents and income groups by taking the population-weighted average of the countries in each group. If less than 80% of countries in an area report data for a given year, we do not calculate the average for that area.


    
# project_j

## AIR TRAVEL ANALYSIS IN AUSTRALIA	
____________________________________

## Module 1

## International Travel Analysis: Australia (2000-2022)

This module contains the analysis of international travel trends to and from Australia between the years 2000 and 2022. The analysis focuses on understanding top destinations, seasonal patterns, and identifying popular Australian ports.

## Contributor:
Joanna Kozak (Asha)

## Table of Contents:
- Module 1 file with the main script
- Output folder with 5 charts and csv file with the cleaned DataSet
- Resources folder with the original DataSet


## Data Overview
The dataset used for this analysis covers the years 2000 to 2022. It includes the following columns:
- Month: The month of travel.
- Year: The year of travel.
- AustralianPort: The port in Australia.
- Country: The destination country.
- ForeignPort: The port in the destination country.
- Passengers_In: The number of passengers traveling to Australia.
- Passengers_Out: The number of passengers traveling from Australia.

_________________________________________________________________________________________


## Module 2

## International Passenger Airline Analysis: Australia (2003 - September 2022)

This module contains an analysis on international airlines to and from Australia between 2003 and September 2022. The analysis focuses on identifying top passenger airlines operating in and out of Australia over years, seat utilization on flights to various country ports, their correlation with popular ports if any, finding popular international port cities by total number of flights, finding country ports with consistent high seat utilization, and potential opportunity for increasing number of flights on analysed routes. 

## Contributor:
Jyotsna Jayaraman

## Table of Contents:
* Module 2 file with the main script, observations and analysis
* Output folder with 13 charts and an image of a map
* Resources folder with the original data sets:
    *  international_airline_activity_opfltsseats.csv
    *  city_pairs.csv
    *  airline_portcountry.csv

## Data sources:
* Uploaded and maintained by Bureau of Infrastructure and Transport Research Economics from https://data.gov.au/
    * Dataset from Scheduled operations of international airlines operating to and from Australia. Data on Passengers, freight and mail carried by airline by uplift/discharge country within single flight number services - https://data.gov.au/dataset/ds-dga-ad89b4ff-541a-4729-b93c-4d2f5682e4c8/details?q=airline
    * Dataset from Scheduled operations of international airlines operating to and from Australia. Data on passengers, freight and mail carried between city pairs connected by a single flight number service - https://data.gov.au/dataset/ds-dga-d9fbffaa-836f-4f52-80e8-324249ff269f/details?q=airline
    * Dataset from Scheduled services operated by international airlines to and from Australia. Covers operated flights and seats by city, airline, route, country and region - https://data.gov.au/dataset/ds-dga-e82787e4-a480-4189-b963-1d0b6088103e/details?q=airline
* Geoapify: Maps, APIs and components | Geoapify Location Platform

## References:
-	[List of busiest airports by international passenger traffic - Wikipedia ](https://en.wikipedia.org/wiki/List_of_busiest_airports_by_international_passenger_traffic)
-	[python - Remove decimal from year value in a data frame - Stack Overflow](https://stackoverflow.com/questions/64678708/remove-decimal-from-year-value-in-a-data-frame)
-	[Tiles — HoloViews v1.16.2](https://holoviews.org/reference/elements/bokeh/Tiles.html)
-	[Python savefig: how to save the figure in a given path using savefig from matplotlib - Stack Overflow](https://stackoverflow.com/questions/42986694/python-savefig-how-to-save-the-figure-in-a-given-path-using-savefig-from-matplo)
-	[Full List of Named Colors in Pandas and Python (datascientyst.com)](https://datascientyst.com/full-list-named-colors-pandas-python-matplotlib/)
-	[python - Annotate bars with values on Pandas bar plots - Stack Overflow](https://stackoverflow.com/questions/25447700/annotate-bars-with-values-on-pandas-bar-plots)

  _________________________________________________________________________________________


## Module 3

## Comparative analysis between Domestic and International travel within Australia from 2000-2022

This module contains the analysis of Domestic and International passenger visits throughout 8 Australian Airports between the years of 2000 and 2022. 
The analysis focuses on comparing the total number of passengers,most frequented Airports and the monthly peaks of Airports between Domestic and International passengers.

## Contributor:
Jorge Chicas

## Table of Contents:
- Module 3 file with main script
- Module 3 analysis 
- Output folder containing 5 graphs
- Resources folder containing 9 csv files with the cleaned DataSet

## Data Overview
The dataset used for this analysis includes the years 2000 to 2022(upto August), which includes the following columns:

- Airport:Airport destination
- Year:Year of visit
- Month:Month of visit
- DOMESTIC_IN:Total number of Domestic passengers who visited
- INTERNATIONAL_IN:Total number of International passengers who visited

## Data sources:
- Airport Passenger Movements by Month-20 Major Airports- https://data.gov.au/data/dataset/cc5d888f-5850-47f3-815d-08289b22f5a8/resource/38bdc971-cb22-4894-b19a-814afc4e8164/download/mon_pax_web.csv
- OpenWeatherMap: meteorological data,coordinates and APIs | Weather Data platform

_________________________________________________________________________________________

## Module 4

## Seasonal Trends in International Travel to Australia (2000 – 2022)

The dataset includes information on monthly international movement of travellers to Australia from 2000 – 2022. The analysis focuses on determining the busiest season on international travellers to Australia, most visited local cities, and busiest season of top local cities.

## Contributor:
Jancel Adiong

## Table of Contents:
- Module 4 with the main script
- Module 4 analysis
- Output folder with 4 charts
- Resources folder with original data set
  * internationalport_country.csv
  * localcity_australia.csv

## Data Overview
The dataset used for this analysis covers the years 2000 – 2022 with following columns:
- Month_num: month of travel
- Year: year of travel
- Passengers_In: international passengers to Australia
- AustralianPort: local city destination in Australia

_________________________________________________________________________________________

## High level Summary of Findings:
-	The top five countries with the highest number of passengers both "to" and "from" Australia in years 2000-2022 are: New Zealand, Singapore, USA, United Arab Emirates and Hong Kong.
-	The most popular months to visit Australia are January, July, and October.
-	The most popular months for passengers to leave Australia are December and January.
-	The decline of international travellers from 2020 can be significantly attributed to Covid 19, with the closure of international border.
-	It was observed that in both total number of domestic and international passengers that the most frequented airports were Sydney, Melbourne and Brisbane
-	Total number of Domestic passengers significantly exceeds the total number of International passengers who frequented all Australian Airports
-	Cairns and Darwin were the only airports that demonstrated a similar trend of monthly average peaks in the winter months of Australia (June-August) in domestic and international passengers. 
-	Quantas followed by Singapore airlines were the most popular airlines between 2003 and September 2022
-	Quantas followed by Air New Zealand were the most popular airlines by total number of flights between 2003 and September 2022.
-	In 2021 ( covid year) Qatar airlines entered the top 5 list for Australia.
-	Singapore airline’s % contribution in top 5 has constantly improved and Emirates has been very consistent.
-	There could be a potential opportunity to increase direct flights to India due to consistently high seat utilization% – this could be a candidate for a deeper analysis.

## Disclaimer:
- This project is created by students for a university assignment hence may not be used for any official purposes.
- The data used is from https://data.gov.au/ - uploaded and maintained by Bureau of Infrastructure and Transport Research Economics and all notes on using the data and limittions associated with them on the site hold true for this project.








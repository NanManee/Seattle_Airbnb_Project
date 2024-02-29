# Seattle_Airbnb_Project
Last dataset updated: December 20, 2023

Data Source: Inside Airbnb.com, the place that gather data and advocate for awareness regarding how Airbnb affects neighborhoods where people live.
Inside Airbnb.com goal is to empower communities by providing them with data and information. This way, Seattle communities can better understand, make decisions about, and manage the practice of renting residential properties to tourists.

## Project Overview

In this project, I cleaned, analyzed and visualized Seattle airbnb listing to Identify how much money is spent on daily activities and feeding using Microsoft excel.
![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/60c0824a-7337-44fc-bd48-70b6f2b3c42f)

## Methodology

Data from Excel tables is first cleaned up using Power Query. Then, it is put into Excel Power Pivot to organize it. From there, I make charts and PivotTables to show the information.

## This project aims to answer the following questions for Airbnb investors in Seattle:

- What are the top three locations for Airbnb rentals?
- What are the most popular months of the year for rentals?
- Which types of bedrooms generate the highest revenue per year?

## Inspecting dataset

- The dataset contains 18 columns and 6,883 rows including column names.
- I copy this raw file for backup purposes.
  
## Data Cleaning
![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/f9a55467-dedd-4ff2-8692-22ae00ec57cf)

![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/314fb483-5afb-4399-9a7b-dc0880e12150)

## Column Checking

- I add filters to all columns instead of formatting this data in a table, which would have taken me more time.

## Check and Remove Duplicates

- I select the whole table and check for duplicate values.
![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/170b2e0a-dbee-4b9f-90de-4d8786e8d23e)

## Check and Remove Null Values

- 

## Find and Replace values
Fix column "Name"
![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/053ac48a-4d43-4372-9972-cf06e6be0752)


![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/459350a8-fd93-4a16-9333-330130baa46e)

- Clean data and create new columns
![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/a1dbdbbb-48dc-4a63-8d10-2c631e97b76f)

## Standardize text
- Using Proper function

  ![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/4031629e-c6ee-404b-b179-e4e2a54a598f)

- Using Upper function

  ![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/256e821c-3223-49e4-ae89-c3df9f9cc7ef)


## Find and Replace
- I replaced 'Studio' with '0' to represent a specific type of studio and a different category altogether compared to '1', which represents 'One bedroom' in this analysis
  ![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/0a76d023-f17a-4437-85d4-e31a183b38a4)

## Trim function to make sre that there's no extra space the entire column

![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/2bdeed4e-37c2-447b-8a08-eed02e0fb02f)

Manually fix wrong column data 
![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/bd493dd9-eed8-48ef-8a30-326df8521c7f)

![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/9ab36750-f3b2-4826-8fcf-dbb79133b986)

![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/a010835c-2259-4129-a41c-a1d213aa31d7)

- change home in seattle to Home
  ![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/4232b6df-0c10-4712-a28d-6f240b087401)


## Insights for Question #1:

All of the top three prime areas are located in Western Washington:
- 98134: The average nightly revenue for room rentals is $206. This area is situated on beautiful Elliott Bay and the Duwamish Waterway, next to downtown Seattle.
- 98119: The average nightly revenue for room rentals is $171. This area is located between Elliott Bay and Lake Union, very close to downtown.
- 98101: The average nightly revenue for room rentals is $167. This area is in downtown Seattle with easy access to Elliott Bay.
  

## Insights for question #2:

The most popular months of the year for rentals are:
- During May and June, it's late spring and early summer. During these months, temperatures in Seattle begin to warm up, and the city experiences longer daylight hours. It offers pleasant weather conditions, making it a popular time for outdoor activities, events, conferences, and tourism.
- During November and December, it's the holiday season, which sees increased shopping activity, tourism, and events, making them busy months for the city.
  

## Insights for question #3:

The average price per bedroom per night:
- 1 bedroom = $96
- 2 bedrooms = $175
- 3 bedrooms = $250
- 4 bedrooms = $315
- 5 bedrooms = $450
- 6 bedrooms = $565

The types of bedrooms that generate the highest revenue per year:
- 1 bedroom = Approximately $63 million
- 2 bedrooms = Approximately $31 million
- 3 bedrooms = Approximately $18 million
- 4 bedrooms = Approximately $6 million
- 5 bedrooms = Approximately $3 million
- 6 bedrooms = Approximately $1 million


## Recommendations:

I would recommend investing in a one-bedroom Airbnb rental. Although six-bedroom rentals generate the most revenue per night at $585, while one-bedroom rentals only earn $96 per night, the frequency of one-bedroom rentals significantly contributes to the highest revenue per year, approximately $63 million compared to the six-bedroom's $1 million per year. When considering the minimum room rental for a one-bedroom per year, it's about $1.5 million versus approximately $5,500 for a six-bedroom.

The best location would be the 98134 zip code, situated on Elliott Bay and the Duwamish Waterway, next to downtown Seattle. The average nightly revenue for room rentals is $206, the highest compared to other locations.

The prime time to maximize revenue is between May and June. During these months, Seattle's temperatures begin to warm up to the an average of 68 degrees, and the city experiences longer daylight hours, creating pleasant weather conditions that attract outdoor activities, events, conferences, and tourism. Additionally, November and December are optimal for renting out Airbnb properties due to the holiday season, which sees increased shopping activity, tourism, and events, making them busy months for the city.

## Data Source: http://insideairbnb.com/get-the-data
## Tableau Dashboard for Visualization: 
https://public.tableau.com/app/profile/nanthawan.maneethong/viz/SeattleAirBnB_17084464300200/Dashboard4

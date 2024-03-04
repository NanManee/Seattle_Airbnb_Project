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
- What are the most popular Airbnb type for rentals?
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


## Recommendations:

Findings and Recommendations:

Location to Invest:
Greenwood, Madrona, and Fremont: These neighborhoods have the highest average Airbnb prices, indicating strong demand from travelers. Greenwood and Fremont are commercial hubs, while Madrona is mostly residential. Consider investing in properties in these areas for potentially higher returns. (Reference chart 1)

View Ridge, Meadowbrook, and North Beacon Hill: These neighborhoods have the lowest vacancy rates, suggesting consistent demand. Despite having fewer listings, View Ridge and Meadowbrook exhibit low annual vacancy rates, making them attractive investment options. North Beacon Hill, with its higher number of listings, also maintains a low vacancy rate, indicating steady demand(Reference chart 6).

Location to Avoid:
South Lake Union, Yesler Terrace, and Eastlake: These neighborhoods have the highest vacancy rates, indicating lower demand or other factors affecting rental availability. It's recommended to avoid investing in properties in these areas for now 
(Reference chart 8).

Number of Bedrooms to Invest In:
One-bedroom units: These units generate the most revenue annually among different bedroom types, indicating strong demand. Consider investing in one-bedroom properties, which have an average price per night of $115 and can yield an average annual revenue at $360,000 (Reference chart 4). The average vacancy per year for one-bedroom listings is 176 days out of a total of 3,210 listings.(Reference chart 7). 

Two-bedroom and Three-bedroom units: These units also generate significant revenue, with two-bedroom units earning $280,000 a year and three-bedroom units bringing in $226,000 a year. Evaluate the demand and supply dynamics in your chosen location before investing in properties with these bedroom configurations. The average vacancy per year for two-bedroom listings is 164 days out of a total of 1,649 listings, and for three-bedroom listings, it is 174 days out of a total of 871 listings(Reference chart 7). 

Types of Airbnb to Invest In:
Entire homes or entire apartment: Most renters prioritize privacy and are willing to pay more to rent an entire property rather than a shared or private room. Properties with higher average daily rates, such as entire homes or apartments, can generate significant revenue, potentially over a million dollars a year(Reference chart 3).
Homes: are the most popular choice on Airbnb and also have the highest average prices at $201(Reference chart 2 and chart 5).

Additional Considerations:
Industrial District: Although not initially recommended due to limited data, consider conducting further research on this location. The Industrial District has the highest average Airbnb price due to its unique characteristics, such as limited listings and longer minimum stay requirements. Investigate the potential for investment opportunities in this area(Reference chart 1).


Before making any investment decisions, we need to do more research on the market conditions, regulations, and potential risks associated with each location. Additionally, consider factors such as property management, maintenance costs, and potential changes in travel trends that may impact your investment.
![image](https://github.com/NanManee/Seattle_Airbnb_Project/assets/156528525/fb848ba5-91f5-4f69-8e55-59bb65ff17a0)


## Data Source: http://insideairbnb.com/get-the-data
## Excel Dashboard for Visualization: 
https://1drv.ms/x/c/96c30430437a9e89/EU6Zdfyro1BFjqjg_SfHmdgBiDgO912XeMz1njWpNs0U2Q?e=R8iYi1d4

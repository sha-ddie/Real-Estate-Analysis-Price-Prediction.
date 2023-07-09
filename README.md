# Real Estate Analysis, King County.

![picture](data/real-estate.jpg)

## Business Understanding

### a) Overview
[King County](https://en.wikipedia.org/wiki/King_County,_Washington) is a populous county in Washington state, that is located in the northwestern region of USA. It include Seattle city which is the county seat, and comprises 29% of washington's population,outof the 39 counties in the state, with  56.72% of its population being home owners while 43.28% being. The county is the home various attractions, companies, amenities and opportunities among others. For more demographics and information of the county view this [link](https://www.point2homes.com/US/Neighborhood/WA/King-County-Demographics.html).

Real estate agencies, licensed professional organisations, are the bridge between buyers and sellers of real estate properties. They guide estate buyers and sellers by; providing unbiased insights and advice , manage negotiations on behalf of buyer / seller and keep documentations required for the estate transaction. Real estate agencies usually receive income from sales on commisions made from property sales, which generally rabges between 5-6% of the property's sale price.

### Problem Statement
Being part of a real estate agency that guides potential property owners / sellers on the marketing process of their property, through; comprehensive market research and analysis to determine the property's market price, identify the best places to invest resources in improvements, and identify the property's top selling points. 

We will be conducting an analysis of king county property sales data in order to be able to guide potential property owners on the best and most effective way to market their property. This can be achieved by identifying crucial areas for improvement and identifying the property's top selling points in order to acquire favorable and high market prices for their properties. This is aimed at improving the property transactions completion threshold for the agency, and in return increase sales revenues to the agency through commissions made for the property sales.

### Main Objective
To develop a predictive regression model that accurately predicts the sale price of a property while identifying crucial areas for improvement in order to increase property prices. As well as coming up with insights to well describe some property top selling points that are associated with high market prices.

### Metrics of Success
Accurately predicting the price of a property based on its feature and outlining key areas that can be acted upon to improve the overall sale price.

### Specific Objectives
* Identify house features that collectively correspond to high market prices.
* Develop a regression model to accurately predict the market price of a house based on its features/ properties.
* Evaluate the performance of the model in predicting market prices.
* From the model identify features that can be improved to increase the house price

## Data Understanding

The dataset used in this project, `kc_house_data.csv` data, contains information/ properties of houses sold in King county region within the year 2014 and 2015. It contains `21597rows` and `20 columns`, with the columns description as below;
* `id` - Unique identifier for a house
* `date` - Date house was sold
* `price` - Sale price (prediction target)
* `bedrooms` - Number of bedrooms
* `bathrooms` - Number of bathrooms
* `sqft_living` - Square footage of living space in the home
* `sqft_lot` - Square footage of the lot
* `floors` - Number of floors (levels) in house
* `waterfront` - Whether the house is on a waterfront
    * Includes Duwamish, Elliott Bay, Puget Sound, Lake Union, Ship Canal, Lake Washington, Lake Sammamish, other lake, and river/slough waterfronts
* `view` - Quality of view from house
    * Includes views of Mt. Rainier, Olympics, Cascades, Territorial, Seattle Skyline, Puget Sound, Lake Washington, Lake Sammamish, small lake / river / creek, and other
* `condition` - How good the overall condition of the house is. Related to maintenance of house.
    * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each condition code
* `grade` - Overall grade of the house. Related to the construction and design of the house.
    * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each building grade code
* `sqft_above` - Square footage of house apart from basement
* `sqft_basement` - Square footage of the basement
* `yr_built - Year` when house was built
* `yr_renovated` - Year when house was renovated
* `zipcode` - ZIP Code used by the United States Postal Service
* `lat` - Latitude coordinate
* `long` - Longitude coordinate
* `sqft_living15` - The square footage of interior housing living space for the nearest 15 neighbors
* `sqft_lot15` - The square footage of the land lots of the nearest 15 neighbors

The project also use `City Names.csv` dataset webscaped from the [Zipcode website ](https://www.zipcode.com.ng/2022/06/list-of-washington-zip-codes.html). `City Names.csv` dataset, contains zipcode names for king county zipcodes contained in the `kc_house_data.csv` dataset, . The dataset has `500 rows` and `4 columns` namely **City ,zipcode, County and State**.

## Data Preparation

The data was checked for missing values, duplicates and placeholders of missing data and the rows that contained missing values and duplicates were dropped. New columns were created from transforming existing columns and columns that were not in their appropriate data type were cleaned and converted into their appropriate data type. 

In this section, the two data sets were merged and all the unrelevant columns were dropped. The remainig columns underwend data cleaning to prepare them for analysis, the various data cleaning methods that are to be used will be;
 <p> &#9672 Converting columns into the requires data type </p>
<p> &#9672  Checking and removing duplicates</p> 
 <p> &#9672 Dealing with missing data and placeholders of missing data by dropping the rows </p>
 <p> &#9672 Removing outliers </p>

## Data Analysis


## Conclusions


## Recommendations

## Resources.
1: For the complete notebook analysis, here is the [Notebook](https://github.com/sha-ddie/Phase-2-Project/blob/main/student.ipynb)

2: The Presentation slides are found [here]()
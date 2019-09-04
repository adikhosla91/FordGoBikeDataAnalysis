# Ford GoBike Exploratory and Explanatory Analysis

## Packages Required
* Numpy
* Pandas
* Seaborn
* Matplotlib
* Datetime
* re
* BeautifulSoup
* Math(sin,cos,sqrt,atan2,radians)

## Software/System Requirement
* Anaconda Installed
* Python 3
* Ram : 2GB Ram
* Notebook: Jupyter Notebook

## Link to the File
* The files are stored in [s3 bucket](('https://s3.amazonaws.com/baywheels-data'))

## Introduction
With increasing traffic congestion in the bay area, the development of transportation infrastructure is vital. A strong transportation infrastructure connects employees to companies, travelers to tourist attractions, students to schools and much more. In particular, the Ford GoBike program offers a biking transportation infrastructure to connect the people of the bay area to numerous locations in SF, East Bay and San Jose. The Ford GoBike infrastructure involves having locations where people can rent bikes at any station and drop them off at any station. As a result, the consumers never have to pay for an actual bike, deal with maintenance of a bike, or worry about having a bike being stolen. Currently, Ford GoBike offers annual memberships, day passes, and single ride plans to use their bikes. As a result of annual membership plans offering the most consistent revenue and demand for Ford GoBike, encouraging subscription of customers will heavily determine the growth of their biking infrastructure. The data was stored in the s3 bucket link: https://s3.amazonaws.com/baywheels-data/index.html. It had data files from 2017 up till July-2019.

## Data Wrangling and Exploratory Analysis
We created to python files one for data wrangling and exploratory analysis; and the other one for explanatory analysis. The Data Wrangling step was divided into Programmatic Gathering of Data, Assessment and Cleaning. Then we performed Univariate, Bi-variate and Multi-variate exploratory analysis to understand the patterns and trends about different data variables

## Explanatory Analysis
In this python notebook I analyzed the trends of the variables for San Jose and some interesting findings shared below

### Information about data
The data had 3.8 million rows and 19 columns when downloaded 

Variables:
bike_id, bike_share_for_all_trip, duration_sec, end_station_idend_station_latitude,,end_station_longitude ,end_station_name ,end_time ,member_birth_year,member_gender ,start_station_id ,start_station_latitude ,start_station_longitude ,start_station_name ,start_time ,user_type


### Findings about  *San Jose*
* Users in San Jose on average travel six minutes to their destination
* We have more Male Users over the years and months. We can see that their number is increasing at a steady pace. The working days has highest number of bicycle riders unlike the weekends
* 20-40 year range has drastically increased. It shows good pattern for the company. The people in thier 30's to 50's should use the bicycle more. The company should focus on that age group to make it easier for the users of that age to use the bike in San Jose
* That's a good sign we can see that in San Jose all most of the Subscribers share their bikes for work. The customers don't share their Bikes for work. Most of the Bike Usage for Customers and Subscribers is between 17 to 18 hrs


```python

```

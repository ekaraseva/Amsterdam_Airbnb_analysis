# Airbnb analysis for Amsterdam city 
This project is a part of the Udacity's Data Scientist Nanodegree Program.

## 1. Project Descriptions
The project analyses Airbnb data for the Amsterdam city. The data set contains real Airbnb listings with its properties, locations and calendar information. The goal of this project is to answer the following questions:
- Which neighbourhood is the most reasonable to stay as a tourist?
- What is the average price in the city?
- Which factors influence accommodation options?
- What is the best time to visit the city?
- Shall I book the accommodation a long time in advance? Will I still find a lot of good options at the last moment?

The project folder contains the following files:
- Data folder – folder with Airbnb data for Amsterdam (listings, geodata and calendar)
- Amsterdam_airbnb_analysis.ipynb
- Amsterdam_airbnb_analysis.html

## 2. Installation
Clone or download the repository.
Prerequisites
- pandas
- numpy
- geopandas
- sklearn
- xgboost
For plotting:
- matplotlib
- seaborn

## 3. Conclusions
- If you plan only one night stay, better to book in advance, since amount of apartments for you search will be limited and priced on that type of apartment is a bit cheaper, thus it can be already booked.
- If you want a bit cheaper accommodation, go outside of city centre, there is a lot of nice residential areas in Amsterdam.
- There is clear seasonality. High season is from April to beginning of October. The most expensive dates are New Year eve, Kind's day and Amsterdam marathon. 
- Smart selection of additional features can improve predictions of prices.
- To improve prediction try different regression models.

Based on this analysis I wrote the article on [Medium.com](https://medium.com/@lena.karaseva/do-you-plan-to-visit-amsterdam-what-do-you-need-to-know-about-airbnb-in-amsterdam-28e52bd00d26)

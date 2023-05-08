# Citibike SQL Dashboard

Are you planning to go to NYC and include a bicycle adventure? or do you want to ride a bicycle and enjoy the landscape on your way to work? Some stations show that there are bicycles available when they are not, making tourists more confused, and employees in NYC get frustrated and decide to take the train instead and possibly be late for work. 

I used [BigQuery's NYC Citi Bike Stations and NYC Citi Bike Trips](https://console.cloud.google.com/marketplace/details/city-of-new-york/nyc-citi-bike?project=ny-citi-bikes) public datasets to create an interactive dashboard.

In this dashboard, I used SQL queries to pull some information and created plots on Google Looker Studio. The goal is to facilitate the analysis and agile/strategic decision-making process of employees and tourists. These analyses and visualizations are based on popular starting/ending stations by gender, top 5 starting/ending combination stations, popular times on weekdays/weekends, and capacity by station.

This dashboard provides insights about historical trips' data from April 12, 2017, to September 20, 2018, and real-time stations' data from January 26, 2023, to the present. 

It is a small visualization/tool to facilitate the decision-making process and experience of tourists and employees in NYC that could be integrated into the NYC Citi Bikes App or Lyft app to support internal business and operation and marketing systems. 

Click here to access this dashboard: [New York City Citibike Dashboard](https://lookerstudio.google.com/embed/reporting/8d31609f-a11d-4179-ac3a-3a1878053e7a/page/M3rFD). To access the SQL code used to pull data from BigQuery, check the attached PDF file. 


## Citibike Stations & Citibike Trips

One of the 2 datasets I used to build the dashboard and both found in BigQuery is the Citibike Stations and the other one is Citibike Trips. Here is some interesting information found in each dataset: 

Stations: 

* Station name 
* Station ID 
* Number of bikes available 
* Total capacity 
* Rental methods 

Trips: 

* Gender riding the bicicles (male, female)
* Start station name 
* End station name 
* Trip duration 
* Customer plan that determines the rate charged for the trip 


## Questions answered on the dashboard

1. What are the most popular starting stations by gender?
2. What are the most popular ending stations by gender?
3. What are the top 5 most popular stations to combine? 
4. What are the peak times on weekdays?
5. What are the peak times on weekends? 
6. From April 2017 to September 2018, which generation was the first to ride bicycles? 

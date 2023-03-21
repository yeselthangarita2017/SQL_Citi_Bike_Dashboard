# Citibike SQL Dashboard

This dashboard was created by pulling informacion from BigQuery public datasets with SQL. Some graphics have a specific SQL query extracting the information from BigQuery on real-time. 

Click here to access this dashboard: New York City Citibike Dashboard (link here). Access the SQL code by downloading the attached PDF file. 

## Citibike Stations & Citibike Trips

One of the 2 datasets I used to build the dashboard and both found in BigQuery is the Citibike Stations and the other one is Citibike trips. Here is some interesting information found in each dataset: 

Stations: 

* Station name 
* Station ID 
* Number of bikes available 
* Total capacity 
* Rental methods 

Trips: 

* Gender riding the bicicles (unknown, male, female)
* Start station name 
* End station name 
* Trip duration in seconds 
* Customer plan that determines the rate charged for the trip 


## Questions answered on the dashboard

1. What are the most popular stations by gender?
2. What are the top 5 most popular stations to combine? (SQL)
3. What are the peak times on weekdays? (SQL)
4. What is the capacity in what stations? 
5. What is the total number of stations and what is the total number of stations available?

# Citibike SQL Dashboard

This dashboard was created by pulling informacion from BigQuery public datasets with SQL. Some graphics have a specific SQL query extracting the information from BigQuery on real-time. 

Click here to access this dashboard: [New York City Citibike Dashboard](https://lookerstudio.google.com/embed/reporting/8d31609f-a11d-4179-ac3a-3a1878053e7a/page/M3rFD). Access the SQL code by downloading the attached PDF file. 

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
3. What are the top 5 most popular stations to combine? (SQL)
4. What are the peak times on weekdays? (SQL)
5. What are the peak times on weekends? (SQL)
6. From April 2017 to September 2018, which generation was the first to ride bicycles? (SQL)

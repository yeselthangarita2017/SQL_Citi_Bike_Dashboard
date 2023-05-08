# Citi Bike SQL Dashboard 

I used [BigQuery's NYC Citi Bike Stations and NYC Citi Bike Trips public datasets](https://console.cloud.google.com/marketplace/details/city-of-new-york/nyc-citi-bike?project=ny-citi-bikes) to create an interactive dashboard, and SQL queries to pull some information and create plots. 

My goal is to facilitate the analysis and agile/strategic decision-making process of employees and tourists in New York City. These analyses and visualizations are based on popular starting/ending stations by gender, top 5 starting/ending combination stations, popular times on weekdays/weekends, and capacity by station.

To access the dashboard, click here: [New York City Citi Bike Dashboard]( https://lookerstudio.google.com/embed/reporting/8d31609f-a11d-4179-ac3a-3a1878053e7a/page/M3rFD). To access the SQL code used to pull data from BigQuery, check the attached PDF file. 

## Citi Bike Stations & Citi Bike Trips 

The BigQuery NYC Citi Bike Trips dataset ranges from April 12, 2017, to September 20, 2018, with a monthly update frequency, and the BigQuery NYC Citi Bike Stations dataset ranges from January 26, 2023, to the present, with a daily expected update frequency. Following analytics principles, I analyzed the data separately as historical data and real-time data. Then, I connected the dots by looking at the challenge from three distinct yet linked perspectives: business, operations, and marketing. Here is some interesting information found in each dataset: 

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

I believe other interesting analyses can be done with this dataset.

## Analysis 

### Insight 1

Business (2017-2018): The popular times on weekdays were early in the morning and late afternoon, which suggests round trips to and from work. The popular times on weekends are late morning until late afternoon, suggesting people performing leisure activities. The reduction of traffic makes it easier and safer for clients to use the bicycles, and weekend events that attract more people lead to increased demand during the day.

### Insight 2

Operations (real-time): FDR Drive & E 35 St has the highest capacity and may need expansion since it is between Wall Street and Midtown Manhattan. It makes sense that it is highly visited by both males and females, who could be employees. The W 4 St & 7 Ave S has the lowest capacity and could be removed.

### Insight 3

Marketing (2017-2018): Millennials rode the bicycles the most. Pershing Square North was the popular starting and ending station for males, while W 21 St & 6 Ave was the popular starting station, and E 17 St & Broadway was the popular ending station for females. 

## Questions answered on the dashboard

1. What are the most popular starting stations by gender?
2. What are the most popular ending stations by gender?
3. What are the top 5 most popular stations to combine? 
4. What are the peak times on weekdays?
5. What are the peak times on weekends? 
6. From April 2017 to September 2018, which generation was the first to ride bicycles? 

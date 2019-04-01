## Explore Weather Trends
The goal of this project is to analyze local and global temperature data and compare the temperature trends where I live (San Francisco) to overall global temperature trends.\
This project is a part of Udacity Data Analyst Nanodegree program.

### Instructions
To create a visualization and prepare a write up describing the similarities and differences between global temperature trends 
and temperature trends in San Francisco, these were the steps that I followed.
- **Extract the data** from the database using SQL and export to CSV.
- **Open up the CSV** using Excel
- **Create a line chart** that compares San Francisco's temperatures with the global temperatures 
(plot the moving average rather than the yearly averages in order to smooth out the lines, making trends more observable)
- **Make observations** about the similarities and differences between the world averages and San Francisco's averages, as well as overall trends.

### The Database Schema
There are three tables in the database:
- city_list - This contains a list of cities and countries in the database. I used this database to find the city nearest to me.
- city_data - This contains the average temperatures for each city by year (ºC).
- global_data - This contains the average global temperatures by year (ºC).

### Submission
The project was submitted in PDF format which includes:
- An outline of steps taken to prepare the data to be visualized in the chart, such as:
  - The tools that I used for each step
  - How I calculate the moving average
  - My key considerations when deciding how to visualize the trends
- Line chart with local and global temperature trends
- Four observations about the similarities and/or differences in the trends

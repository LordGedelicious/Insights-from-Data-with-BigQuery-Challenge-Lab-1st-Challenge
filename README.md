# Insights-from-Data-with-BigQuery-Challenge-Lab-1st-Challenge

# This is the code needed to clear "Query 1: Total Confirmed Cases" in "Insights from Data with BigQuery: Challenge Lab" in Google Qwiklabs. The dataset used is from 'bigquery-public-data.covid19_open_data.covid19_open_data' dataset.

#standardSQL  
SELECT  
SUM(cumulative_confirmed) AS total_cases_worldwide  
FROM `bigquery-public-data.covid19_open_data.covid19_open_data`  
WHERE date='2020-04-15'  

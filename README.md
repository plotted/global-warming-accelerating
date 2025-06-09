# Global Warming Accelerating


This repository contains code in R to replicate the following graphic:

  

![Monthly global temperature compared with average for the 20th
century](source/monthly-global-temperature-against-20th-century.png)

## Source

- Title: **Earth Was Due for Another Year of Record Warmth. But This
  Warm?**

- Author(s): Raymong Zhong and Nadia Popovich

- Date: Dec. 26, 2023

- From: New York Times

- URL:
  <https://www.nytimes.com/2023/12/26/climate/global-warming-accelerating.html>

- PDF:
  [Earth-Was-Due-for-Another-Year-of-Record-Warmth-NYT.pdf](source/Earth-Was-Due-for-Another-Year-of-Record-Warmth-NYT.pdf)

## Data

The source of the data is NOAA Global Time Series

<https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series>

Time series 1850 - 2024 available in 3 formats: CSV, JSON, and XML. We
decided to keep it simple and work with the CSV file:

<https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/tavg/land_ocean/1/0/1850-2024/data.csv>

A local copy of this CSV file is in the `data/` folder of this github
repository.

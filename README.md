# Airline Delay and Cancellation Analysis

This project analyses large-scale U.S. airline flight data from 2009–2018 to identify patterns in flight delays and cancellations and to predict the likelihood of a flight being delayed.

The project uses **Apache Spark (PySpark)** to process and analyse more than **60 million flight records**, covering airlines, airports, seasonal trends, cancellation reasons, and delay types.

## Overview

The main objectives were to:

- Identify delay and cancellation patterns across airlines, airports, months, and years
- Explore seasonal and time-based trends in flight disruptions
- Analyse common cancellation causes, including weather, carrier issues, and National Airspace System (NAS) delays
- Compare delay behaviour across airlines and airports
- Build machine learning models using Spark MLlib to predict delayed flights

## Dataset 
[Airline Delay and Cancellation Data 2009–2018](https://www.kaggle.com/datasets/usdot/flight-delays)
[2015 Flight Delays and Cancellations](https://www.kaggle.com/datasets/usdot/flight-delays)

## Tech Stack

Python · PySpark · Spark SQL · Spark MLlib · Pandas · Matplotlib · Seaborn

## Results

Gradient-Boosted Trees achieved the best delay-prediction performance with an AUC of **0.821**, outperforming Random Forest (0.812) and Logistic Regression (0.706).

## Key Insights

- Weather was the leading cause of cancellations, especially in winter
- Delays increased throughout the day, peaking in the late afternoon and evening
- Major hub airports recorded the highest cancellation volumes

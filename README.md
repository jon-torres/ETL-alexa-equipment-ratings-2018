# ETL Project: Amazon Alexa Product Ratings

## Overview

This ETL (Extract, Transform, Load) project focuses on analyzing Amazon Alexa product ratings from 2018. The project aims to clean and structure the data, calculate average ratings for each product, and load the results into a SQLite database.

## Extract

- Data Source: [Amazon Alexa Reviews](https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews)
- Tools Used: Python, Pandas

In the extraction phase, we retrieved the dataset from a CSV file, which contained information about product ratings and variations.

## Transform

- Data Cleaning: We cleaned the dataset by mapping similar product variations to a common name (e.g., 'Black Dot' to 'Echo Dot').
- Data Aggregation: We calculated the average ratings for each product variation.
- Tools Used: Python, Pandas

## Load

- Database: SQLite
- Tools Used: Python, Pandas, SQLite

In the load phase, we created an SQLite database and a table to store the cleaned and transformed data. The data was then loaded into this table for further analysis.

## Results

- A table in the SQLite database containing product names, average ratings, and counts.
- Insights into product ratings and variations.

## Technologies Used

- Python
- Pandas
- SQLite

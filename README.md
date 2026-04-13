### Taxi Data Pipeline – NYC Trip Data Processing

This project implements a comprehensive data preprocessing and transformation pipeline on the New York City Taxi Trip Duration dataset. The primary objective is to convert raw, noisy transportation data into a clean, structured, and analytics-ready format suitable for downstream tasks such as visualization, statistical analysis, and machine learning modeling.

The dataset, sourced from the Kaggle competition "NYC Taxi Trip Duration", contains real-world trip records with inconsistencies, missing values, and anomalies that require systematic handling before meaningful insights can be derived.

Key Features and Processing Steps:

* Data Cleaning and Validation
  Identified and handled missing/null values across critical fields and ensured data type consistency.

* Outlier Detection and Removal
  Removed extreme and unrealistic values such as abnormal trip durations and invalid coordinate ranges.

* Geographic Filtering
  Restricted the dataset to valid New York City locations and removed out-of-bound latitude and longitude values.

* Exploratory Data Analysis (EDA)
  Performed statistical summaries and visual exploration to understand feature distributions and relationships.

* Feature Transformation
  Applied standardization to normalize feature scales and used log transformation to reduce skewness.

Outcome:

The final dataset is clean, consistent, and optimized for analytics, visualization, and machine learning applications.

Dataset Source:
https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data

### NYC Yellow Taxi Trips 2024 EDA
## Project Overview

This project focuses on Exploratory Data Analysis of NYC Yellow Taxi trip data for the year 2024.

The analysis explores taxi trip patterns, passenger behavior, payment methods, trip distances, fare amounts, trip durations, and relationships between different variables. The project also uses data visualization to present important patterns in the dataset.

## Dataset

The dataset used for this project is the **NYC Yellow Taxi Trips 2024** dataset from Kaggle.

**Dataset source:**
https://www.kaggle.com/datasets/mohamedsalamh/nyc-yellow-taxi-trips-2024-aggregated-dataset

The dataset contains aggregated NYC Yellow Taxi trip data for 2024, including information about trip count, passenger count, payment type, pickup and drop-off boroughs, trip distance, duration, fare amount, tip amount, and total amount.

## Objectives

Understand the structure and characteristics of the dataset
Analyze taxi trips based on different hours and pickup locations
Analyze passenger count and payment methods
Study trip distance, fare amount, and trip duration
Create useful features such as average fare and average tip
Identify variations and potential outliers
Study relationships between numerical variables
Visualize important findings using Python
Data Cleaning

The dataset was checked for:

Missing values
Duplicate records
Data types
Unique values
Basic statistical information
Feature Extraction

Two additional features were created:

Average Fare: Fare amount generated per taxi trip
Average Tip: Tip amount received per taxi trip
Exploratory Data Analysis

The following analyses were performed:

Basic Dataset Exploration
Dataset shape
Column names
Data types
Statistical summary
Missing value check
Duplicate value check
Unique value analysis
Passenger and Payment Analysis
Distribution of passenger count
Distribution of payment types
Taxi trips by payment type
Average fare by payment type
Trip distance by payment type
Trip Analysis
Total taxi trips by pickup borough
Total taxi trips by hour
Top date based on total number of trips
Top records based on trip distance
Filtering trips based on trip distance and fare amount
Fare and Tip Analysis
Average fare calculation
Average tip calculation
Average fare by pickup borough
Distribution of average tip
Fare amount analysis

## Outlier Analysis

Boxplots were used to identify variations and potential outliers in:

Trip distance
Fare amount
Trip distance across payment types

## Distribution Analysis

Histograms were used to study:

Trip count distribution
Average tip distribution

##Relationship Analysis

Scatter plots were used to analyze relationships between:

Trip distance and fare amount
Trip distance and trip duration

## Tools and Technologies

Python
Pandas
NumPy
Matplotlib
Seaborn

## Key Insights

Taxi trip activity varies across different hours of the day.
Pickup activity is not evenly distributed across the NYC boroughs.
Payment methods show different usage patterns.
Certain passenger group sizes are more common than others.
Trip distance and fare amount show a relationship.
Trip distance and trip duration also show a relationship.
Boxplot analysis shows variation and potential outliers in trip distance and fare amounts.
Average fare and average tip provide additional information about the amount generated per trip.

## Conclusion

This project provided practical experience in exploring and analyzing real-world taxi trip data. The analysis helped in understanding taxi usage patterns, passenger behavior, payment preferences, trip characteristics, and fare patterns in NYC during 2024.

The project also strengthened practical skills in Python, Pandas, Matplotlib, and Seaborn for data analysis and visualization.

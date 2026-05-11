# NYC Airbnb Data Cleaning & Analysis

## Project Overview

This project focuses on cleaning, preprocessing, and analyzing the New York City Airbnb Open Data dataset. The objective of the project is to improve data quality, handle inconsistencies, and extract meaningful insights related to Airbnb listings, pricing, room types, host activity, and neighborhood trends.

The project demonstrates industry-level data cleaning techniques using Python and includes exploratory data analysis (EDA) to better understand the Airbnb market in New York City.

---

# Dataset Information

Dataset Used: NYC Airbnb Open Data

Source: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

The dataset contains Airbnb listing information such as:
- Listing ID
- Host Name
- Neighborhood Group
- Neighborhood
- Latitude & Longitude
- Room Type
- Price
- Minimum Nights
- Number of Reviews
- Availability
- Reviews Per Month

---

# Objectives

The main goals of this project are:

- Perform data cleaning and preprocessing
- Handle missing and inconsistent values
- Remove duplicate records
- Detect and manage outliers
- Standardize dataset formatting
- Create meaningful derived features
- Perform exploratory data analysis (EDA)
- Prepare cleaned data for dashboarding and visualization

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

---

# Project Workflow

## 1. Data Collection

- Downloaded dataset from Kaggle
- Imported CSV dataset into Jupyter Notebook

---

## 2. Data Cleaning

The following cleaning steps were performed:

### Missing Value Handling
- Filled missing review-related values
- Removed rows with missing critical information

### Duplicate Removal
- Identified and removed duplicate records

### Data Type Conversion
- Converted date-related columns into proper datetime format

### Invalid Data Removal
- Removed records containing invalid prices and minimum night values

### Text Standardization
- Standardized categorical text columns for consistency

### Outlier Detection
- Used IQR (Interquartile Range) method to detect and handle price outliers

### Feature Engineering
Created additional useful columns such as:
- Price Category
- Availability Classification
- Review Activity Groups

---

# Exploratory Data Analysis (EDA)

The following analyses were performed:

- Distribution of Airbnb prices
- Room type analysis
- Neighborhood-wise listing distribution
- Availability trends
- Review activity analysis
- Price comparison across boroughs
- Correlation analysis between numerical features

---

# Key Insights

- Manhattan listings generally have the highest prices
- Entire homes/apartments are more expensive than private rooms
- Some neighborhoods have significantly higher listing density
- Price distributions are highly skewed due to luxury listings
- Availability patterns vary across different boroughs

---

# Data Cleaning Techniques Used

| Technique | Purpose |
|---|---|
| Missing Value Handling | Improve data completeness |
| Duplicate Removal | Maintain data uniqueness |
| Datetime Conversion | Enable time analysis |
| Outlier Handling | Reduce skewness |
| Standardization | Maintain consistency |
| Feature Engineering | Improve analytical capability |

---

# Project Structure

```text
airbnb-project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│
├── visuals/
│
├── dashboard/
│
├── README.md
│
└── requirements.txt
```

---

# Sample Visualizations

The project includes:
- Boxplots
- Histograms
- Heatmaps
- Scatter plots
- Bar charts
- Correlation matrices

---

# Dashboard

An interactive Power BI dashboard was created to visualize:
- Total Listings
- Average Price
- Room Type Distribution
- Neighborhood Analysis
- Availability Trends
- Host Activity Analysis

---

# Conclusion

This project demonstrates the importance of data cleaning in the analytics pipeline. By handling missing values, duplicates, inconsistent formatting, and outliers, the dataset became more reliable for analysis and visualization.

The cleaned dataset and insights generated can support further analytics, dashboarding, and machine learning applications.

---

# Future Improvements

Possible future enhancements include:
- Predictive price modeling
- Geospatial analysis using maps
- Sentiment analysis on reviews
- Time-series trend analysis
- Recommendation system for listings

---

# Author

Khushi Kumari

---

# License

This project is intended for educational and portfolio purposes.

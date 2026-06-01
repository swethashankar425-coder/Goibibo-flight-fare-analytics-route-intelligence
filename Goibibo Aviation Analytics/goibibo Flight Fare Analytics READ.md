# Flight Fare Analytics & Route Intelligence Dashboard

## Project Overview

This project analyzes flight fare data to uncover pricing trends, route performance, airline behavior, and anomalous fare patterns. The solution combines data analytics, machine learning, and business intelligence to transform raw flight records into actionable insights.

The project includes data cleaning, feature engineering, exploratory data analysis (EDA), KPI development, route segmentation using K-Means Clustering, anomaly detection using Isolation Forest, and an interactive Power BI dashboard.

---

## Objectives

* Analyze airline pricing patterns and fare trends.
* Evaluate route-level performance and travel characteristics.
* Identify abnormal fare behavior using anomaly detection.
* Segment routes into meaningful business categories.
* Build an interactive dashboard for decision-making.

---

## Dataset Features

The dataset contains flight-related information including:

* Airline
* Source City
* Destination City
* Route
* Class
* Duration
* Number of Stops
* Flight Date
* Fare Price

Additional engineered features:

* Duration Minutes
* Month
* Day Name
* Weekend Indicator
* Departure Slot
* Duration Category
* Cluster Labels
* Anomaly Labels

---

## Project Workflow

### 1. Data Cleaning

* Removed null values and inconsistencies.
* Standardized data formats.
* Converted duration values into minutes.

### 2. Feature Engineering

Created additional analytical features:

* Route
* Month
* Day Name
* Is Weekend
* Departure Slot
* Duration Category

### 3. Exploratory Data Analysis

Performed:

* Airline-wise fare analysis
* Route-wise analysis
* Duration analysis
* Class comparison
* Fare distribution analysis

### 4. KPI Development

Key business metrics:

* Total Flights
* Average Fare
* Average Duration
* Total Routes
* Total Airlines
* Anomaly Count

### 5. Route Segmentation

Implemented K-Means Clustering using:

* Fare Price
* Duration Minutes
* Number of Stops

Cluster quality was evaluated using Silhouette Score.

### 6. Anomaly Detection

Implemented Isolation Forest to identify unusual fare patterns and pricing outliers.

### 7. Power BI Dashboard

Developed a multi-page dashboard containing:

#### Executive Summary

* KPI Cards
* Fare Trend Analysis
* Airline Market Share
* Departure Slot Analysis

#### Airline Analytics

* Airline Performance
* Fare Comparison
* Flight Distribution

#### Route Analytics

* Costliest Routes
* Cheapest Routes
* Route Distribution

#### Anomaly Detection

* Fare Outlier Analysis
* Airline-wise Anomalies
* Price vs Duration Analysis

#### Route Segmentation

* Cluster Distribution
* Cluster Comparison
* Route Category Analysis

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Power BI

---

## Machine Learning Techniques

### K-Means Clustering

Used to segment routes into distinct business categories based on fare, duration, and stops.

### Isolation Forest

Used to identify abnormal flight fare behavior and potential pricing anomalies.

---

## Key Insights

* Significant fare differences exist across airlines and routes.
* Flight duration and stop count influence pricing behavior.
* Distinct route segments can be identified using clustering techniques.
* Anomaly detection highlights unusual fare patterns and outlier flights.
* Interactive dashboards improve business visibility and decision-making.

---

## Business Value

This project demonstrates how analytics and machine learning can be used to understand airline pricing behavior, optimize route analysis, detect anomalies, and support data-driven decision-making through interactive dashboards.

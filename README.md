# NYC Taxi Fare Data Preparation and Analysis

## 📁 Project Overview
This project was completed as part of the Google Advanced Data Analytics Professional Certificate. It simulates a real-world consulting scenario where I joined a fictional firm, Automatidata, to help the New York City Taxi & Limousine Commission (TLC) prepare their data for predictive modeling.

### The dataset includes 22,699 records of taxi trips made in NYC during 2017. The primary goal was to clean and prepare the dataset to build a regression model that could estimate taxi fares before a trip.

## 🧠 Objectives
- Import and inspect the raw dataset using Python
- Identify and address anomalies, outliers, and invalid data
- Engineer relevant features for modeling
- Communicate findings in an executive summary
- Apply the PACE framework (Plan, Analyze, Construct, Execute)

## 🛠️ Tools & Libraries
- Python
- pandas
- NumPy
- Jupyter Notebook

## 🗂️ Dataset Summary
- Source: 2017 Yellow Taxi Trip Data (Simulated TLC Data)
- Rows: 22,699 
- Columns: 18

- Key columns include:
  - trip_distance
  - fare_amount
  - tip_amount
  - total_amount
  - payment_type
  - RatecodeID
  - tpep_pickup_datetime
  - tpep_dropoff_datetime

## 🔍 Key Insights:

- ✅ No missing values across all columns
- 🚩 Anomalies found: negative and unusually high values in fare_amount and total_amount
- 🔁 Zero-distance trips with high fares suggest possible data entry errors or canceled trips
- 💳 Tip bias: Only credit card tips are recorded; cash trips show $0 tips
- ❌ Invalid RatecodeID values (99) found
- ⏱ Datetime fields were stored as strings and required conversion

## ✅ Tasks Completed
- Loaded and explored the dataset with .info() and .describe()
- Sorted and flagged extreme values
- Filtered credit card trips to analyze tip behavior
- Engineered features from datetime and payment fields
- Produced a professional executive summary for stakeholders

## 📌 Key Variables for Modeling
- trip_distance: Strong linear correlation with fare
- payment_type: Impacts tipping behavior and fare structure

## 📈 Next Steps
- Clean or remove rows with negative/invalid values
- Engineer additional features (hour of day, weekday/weekend, trip duration)
- Augment with external data (weather, traffic, zones)
- Begin exploratory data analysis and regression modeling

## 📄 Deliverables
- Jupyter Notebook (code + markdown walkthrough)
- Executive Summary Document
- PACE Strategy Document

## 📬 Contact
- Feel free to connect with me:
  - Bheki Mogola
  - Email: [bpmogola](bpmogola@gmail.com🔗) 
  - LinkedIn Profile: [Bheki Mogola](linkedin.com/in/bheki-mogola-8481122b7)

# tesla-model-3-market-valuation-analysis


# Project Overview

This project analyzes the used Tesla Model 3 market using Excel and Tableau. I collected 70 vehicle listings directly from CARFAX to explore how model year, mileage, trim, and vehicle history relate to asking prices.

I also built an Excel-based valuation model to compare each vehicle's asking price with similar listings and created a simple risk scoring system to help identify vehicles that may need further review.

The goal of this project was to practice data cleaning, market analysis, Excel modeling, and data visualization using real-world data.


# Tools Used

Microsoft Excel: Data cleaning, formulas, PivotTables, valuation model, and risk analysis

Tableau Public: Interactive dashboard and data visualization


# Dataset

Source: CARFAX used vehicle listings

Location: Richardson, Texas (within a 50-mile search radius)

Collection Date: November 2026

Total Listings: 70

Model Years: 2019–2023

The dataset includes vehicle information such as model year, trim, mileage, asking price, accident history, and number of previous owners.


# What I Did

1. Data Cleaning and Market Analysis

I organized and checked the collected vehicle data in Excel. I then used formulas and PivotTables to compare asking prices across model years, trims, mileage levels, and vehicle history.

2. Comparable Valuation Model

I created a model that compares each vehicle with similar listings based on model year, trim, and mileage.

The model classifies vehicles into four groups:

Above Benchmark, Near Benchmark, Below Benchmark, Insufficient Data.

The model was able to calculate a comparable price benchmark for 57 out of 70 vehicles (81.4%).

3. Risk Analysis

I created a simple rule-based scoring system using reported vehicle history and previous owner count.

Vehicles were grouped into Low, Moderate, or High Review Priority to help identify listings that may require additional research.

4. Tableau Dashboard

I built an interactive Tableau dashboard to visualize:

Average asking price by model year and trim

Relationship between mileage and asking price

Pricing status distribution

Vehicle review priority distribution

Key market statistics



# Key Findings

The average asking price across the 70 listings was approximately $26,930.

The 2023 models had the highest average asking price among the model years in the dataset, at approximately $29,524.

Mileage and asking price showed a negative correlation of approximately -0.666.

A simple linear regression showed an R² of approximately 0.443, suggesting that mileage was associated with a substantial portion of the observed price variation.

The comparable valuation model achieved 81.4% benchmark coverage.


# Dashboard
[View My Tesla Model 3 Tableau Dashboard](https://public.tableau.com/app/profile/shichen.zhu/viz/TeslaModel3UsedMarketValuationRiskAnalysis/Tesla_Model_3_Market_Dashboard)


# Limitations

This project uses a relatively small sample of 70 listings from one geographic area. The prices represent advertised asking prices rather than actual sale prices.
For simplicity, Standard Range, Standard Range Plus, and Mid Range vehicles were grouped into a single "Standard Range" category. However, these versions have different specifications and may have different market values, which could affect the accuracy of the trim comparisons and valuation model.



# Conclusion

This project helped me gain more experience working with real-world data and using Excel and Tableau to answer business questions. I also learned how to build a basic valuation model, check data quality, and present analysis through an interactive dashboard.


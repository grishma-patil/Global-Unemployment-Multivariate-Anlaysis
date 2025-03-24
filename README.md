**Global Unemployment Analysis**
## **Dataset**

**Source and Editing**
* The dataset contains global unemployment trends collected over a span of 10 years (2014-2024).
* It includes various demographics such as age groups, gender, and country-wise unemployment rates.
* The dataset consists of X columns and Y rows with a focus on analyzing patterns, classifying trends, and predicting unemployment risks.

**Data Dictionary**
* Country Name – Name of the country
* Sex – Gender classification (Male/Female)
* Age Group – Categorized into under 15, 15-24, 25-54, 55+ years
* Yearly Unemployment Rate – Percentage of unemployed individuals per country
* Total Unemployment Rate – Aggregate unemployment for all years
* High-Risk Category – Binary classification of high/low unemployment risk

## **Questions and Hypothesis**
Questions
1. Can we classify if a country falls under a high-risk unemployment category?
2. Can we predict unemployment risk based on historical data trends?

**Hypothesis**
* The time period, country’s economic factors, and demographics influence unemployment trends.
* Unemployment rate patterns can help predict future high-risk categories.

## **Two Approaches**
Due to the presence of outliers and varying economic conditions, two analytical approaches were considered:
* Comprehensive Analysis – Using all available features to analyze global trends.
* Focused Analysis – Using key features like age group, country, and total unemployment rate for classification and prediction.

## **Key Techniques Used**
* Data Cleaning & Transformation – Handling missing values and normalizing data.
* Exploratory Data Analysis (EDA) – Identifying unemployment trends over time.
* Principal Component Analysis (PCA) – Reducing dimensionality while retaining key features.
* Clustering Analysis – Grouping countries based on unemployment risk.
* Predictive Modeling – Using logistic regression and decision trees to classify high-risk unemployment categories.

## **File Dictionary**
* Global_Unemployment_Report.pdf – Detailed report on findings, hypotheses, and results.
* Global_Unemployment_Dataset.csv – Dataset used for analysis.
* Global_Unemployment_Analysis.rmd – Rmd file contains the R code for the complete analysis performed, the flow of thought process, and inferences mentioned after each step.
* Global_Unemployment_Analysis.html – HTML output file showcasing results, visuals, and inferences.

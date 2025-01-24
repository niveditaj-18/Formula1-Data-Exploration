# Formula1-Data-Exploration
A machine learning and data analytics project using the Ergast Motor Racing Data API to explore Formula 1 race outcomes, driver demographics, circuit dynamics, and constructors' performance. This project employs machine learning models to predict race outcomes and provides insights into the impact of key factors on Formula 1 performance.

## Overview
This project explores Formula 1 race outcomes using the Ergast Motor Racing Data API. It combines data analysis and machine learning to:
- Predict race outcomes.
- Analyze the impact of circuits on race results.
- Investigate constructors' performance trends.
- Explore the influence of driver demographics on race outcomes.

## Dataset
- **Source**: [Ergast Motor Racing Data API](http://ergast.com/mrd/)
- **Description**:
  - Historical data from 1950 to the present.
  - Information on circuits, constructors, drivers, and race results.
  - Includes granular details like lap times, pit stops, and qualifying results.

## Methodology
1. **Data Cleaning**:
   - Merged 14 interrelated datasets using foreign keys.
   - Addressed null values (`\N`) through removal or imputation.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed constructors' performance, circuit impact, and driver demographics.
3. **Modeling**:
   - Machine learning models: Naïve Bayes, Decision Tree, Logistic Regression, Gradient Boosting.
   - Evaluation metrics: Accuracy, Precision, Recall, and ROC-AUC.
4. **Visualization**:
   - Geographical maps for circuits.
   - Line plots for constructors' performance over time.
   - Bar charts for driver demographics and circuit performance.

## Results
1. **Top Model**: Gradient Boosting achieved 96.6% accuracy.
2. **Key Insights**:
   - Constructors’ performance fluctuates significantly over the years.
   - Circuits influence race outcomes based on car performance (e.g., high-speed vs. low-speed corners).
   - Driver demographics (e.g., nationality) impact performance trends.

## Tools and Technologies
- **Programming Languages**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Data Source**: Ergast Motor Racing Data API


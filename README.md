# User Churn Prediction Using Exploratory Data Analysis

## Project Overview
This project aims to analyze user churn for the Waze app through comprehensive exploratory data analysis (EDA). By identifying user behaviors that contribute to churn, the analysis seeks to enhance retention strategies and improve overall customer satisfaction.

## Business Understanding
The Waze data team is the primary stakeholder, aiming to reduce monthly user churn by understanding the underlying factors influencing user behavior. The insights gained from this analysis will inform proactive strategies to engage users at risk of leaving the app.

## Data Understanding
The analysis leverages user activity data over a specified timeframe, examining key features such as:
- **App Usage**: Frequency of app use and its relationship to churn.
- **Distance Driven**: Average kilometers driven per day and its correlation with churn rates.
- **Driving Days**: The number of days users actively drove and how this impacts retention.

Notably, several variables presented highly improbable outliers, indicating potential data quality issues. 

## Modeling and Evaluation
This project focuses on EDA rather than traditional modeling, emphasizing the following key insights:
- Increased app usage correlates with decreased churn; 40% of non-users churned, while 100% of daily users did not.
- A positive correlation exists between distance driven per day and churn likelihood.
- More frequent driving days negatively correlate with churn rates.

## Conclusion
The analysis reveals critical patterns in user behavior, indicating that low app usage significantly increases churn risk. Recommendations include:
- Investigating discrepancies in user activity data to enhance accuracy.
- Collaborating with the Waze team to explore user profiles, particularly those who drive long distances, to understand their churn behavior better.
- Planning for deeper statistical analyses to further assess the impact of identified variables on user churn.

Future steps will involve refining data collection methods and applying more sophisticated statistical models to predict churn effectively.

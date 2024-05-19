# FIFA World Cup 2022 prediction with Python

## Overview

This project aims to simulate the progression of a soccer tournament, starting from the round of 16 to the final, and predict the outcomes of each match using historical data and linear regression models. The project involves data preparation, analysis, and modeling to achieve accurate predictions of match results.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Preparation](#data-preparation)
3. [Data Analysis](#data-analysis)
4. [Data Modeling](#data-modeling)
5. [Conclusion](#conclusion)
6. [Authors](#authors)

## Introduction

Football tournaments are highly unpredictable and exciting events that draw the attention of millions of fans worldwide. This project leverages historical match data and ranking information to simulate and predict the outcomes of matches in a knockout tournament format for the FIFA World Cup 2022 Qatar. The project involves several steps, including data preparation, analysis, and modeling, to ensure accurate and reliable predictions.

## Data Preparation

In this stage, we gathered and prepared the data required for our analysis and modeling. The primary datasets used include historical match results and team rankings. The following steps were undertaken to prepare the data:

1. **Data Collection**: We collected historical match data and team rankings from reliable sources. The match data includes information about the home team, away team, and the goal difference, while the ranking data includes the rankings of each team at different points in time.

2. **Data Cleaning**: The datasets were cleaned to remove any inconsistencies or missing values. This involved handling null values, correcting data types, and ensuring that the team names were consistent across both datasets.

3. **Data Structuring**: The data was structured to facilitate analysis and modeling. This involved creating a unified dataframe that combines match results with corresponding team rankings, ensuring that each match record has the necessary information for analysis.

## Data Analysis

With the data prepared, we performed several analyses to understand the factors influencing match outcomes and to prepare features for our predictive models. The following analyses were conducted:

1. **Exploratory Data Analysis (EDA)**: We conducted EDA to gain insights into the distribution and relationships of key variables. This included visualizing the distribution of goal differences, the ranking differences between teams, and the outcomes of matches.

2. **Feature Engineering**: Based on our EDA, we engineered features that could be used in our predictive models. This included calculating the ranking difference between the home and away teams, the average goal difference, and other relevant metrics.

3. **Correlation Analysis**: We analyzed the correlation between different features and the match outcomes to identify the most influential factors. This helped in selecting the most relevant features for our predictive models.

## Data Modeling

The core of the project involved building and training predictive models to simulate the tournament progression. The following steps were taken in this phase:

1. **Model Selection**: We experimented with different machine learning models, including linear regression, to predict match outcomes. Linear regression was chosen due to its simplicity and interpretability.

2. **Model Training**: The models were trained on the historical match data, with features such as ranking differences and historical goal differences. The models were evaluated using cross-validation to ensure their accuracy and robustness.

3.  **Cross-validation**: We implemented a cross-validation function to evaluate the model's performance across different samples of the data. This ensured that the model's predictions were reliable and generalizable.

4. **Simulation**: Using the trained models, we simulated the progression of the tournament from the round of 16 to the final. The results of each match were predicted, and the winners advanced to the next round until the champion was determined.

## Conclusion

This project demonstrates the application of data analysis and machine learning techniques to simulate and predict the outcomes of an eliminatory bracket of a football world cup. By leveraging historical match data and team rankings, we built a robust model that can accurately predict match results and simulate the progression of this tournament. This project can be extended and improved by incorporating more sophisticated models and additional features to further enhance prediction accuracy.

## Authors

+ Alvarez Colombo, Juan Ignacio
+ Amster, Martin
+ Ledesma Cueli, Nicolas

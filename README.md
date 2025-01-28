## Introduction
This project was developed as part of the Data Science Academy selection process for COMPFEST 16, hosted on Kaggle. The goal of this competition was to predict groundwater hardness levels based on various chemical attributes, utilizing a dataset provided during the competition.

## Introduction
Groundwater is a vital resource for many communities, yet it is often contaminated with harmful chemicals. One of the most common issues is water hardness, caused by high concentrations of minerals such as calcium and magnesium. Hard water not only affects the quality of drinking water but also damages household appliances and water distribution infrastructure.

To address this issue, regular chemical testing is crucial to monitor hardness levels and ensure that groundwater meets health and safety standards. This project aims to contribute to solving groundwater challenges, particularly in Mexico, by predicting hardness levels using machine learning models.

## Objective
The primary goal of this project is to build a predictive model for groundwater hardness using the provided dataset. By analyzing chemical features like alkalinity, calcium, and magnesium levels, the project aims to:
* Enhance understanding of groundwater quality.
* Provide a reliable tool for predicting hardness levels, aiding in water resource management.

## Evaluation Metrics
Model performance is evaluated using the R² score, a metric that measures how well the predicted values align with the actual values. The closer the R² score is to 1, the better the model’s performance. Our team achieved an R² score of 0.92648 for the private leaderboard, which indicates that our model explained approximately 92.65% of the variance in groundwater hardness levels. This high score demonstrates the effectiveness of the selected features and model in capturing patterns in the dataset.

Link to R² score documentation: sklearn.metrics.r2_score

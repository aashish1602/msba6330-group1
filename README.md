# Project Overview
This project repository is created in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.”

## Key Question
How can we utilize AWS services to provide a robust data exploration and ML pipeline that predicts the likelihood of advertisements being clicked?

## Topic
In online advertising, click-through rate (CTR) is a very important metric for evaluating ad performance. As a result, click prediction systems are essential and widely used for sponsored search and real-time bidding. For business promoters, they want to promote products in most effective ways which means they want to choose advertisements with high CTR. In this project, out goal is to predict the performance of advertisements before lauching them.

## Dataset
Our data is from a kaggle competition, which is provided by Avazu, a service provider of online advertising and digital marketing with its focus on globalized PC and mobile internet advertising. We have 10 days of click-through data containing 6 GB total and one day of ads for testing model predictions.

Data Source Link: https://www.kaggle.com/competitions/avazu-ctr-prediction/data

## Approach
- Data is storaged on AWS S3 bucket
- Data Visualization & Key Trends & Insights on AWS Quicksight
- Feature Exploration and Data Summaries on Data Wrangler
- Building ML model using Python libraries under AWS Sagemaker
![Alt text](/ProcessFlow.png)

## Dashboard Demo
We connect data stored in S3 bucket to Quicksight for dashboarding. Quicksight handled 6GB data for visualization and updated in less than 10 seconds for the entire dashboard, showing it's a powerful tool for EDA.

![Alt text](/dashboard_demo.jpg)

## Main Files
```msba6330-trends-ml-pipeline_final.ipynb```: Script to import data from S3 and run ML algorithm to make predictions.

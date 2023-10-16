# airline_review_ETL_EDA_ML

**British Airways Customer Review Analysis ReadMe**

**Project Overview**
The goal of this project is to analyze and gain insights from customer reviews of British Airways. The project covers various aspects, including data collection, data preprocessing, sentiment analysis, exploratory data analysis (EDA), and machine learning for recommendation prediction.

**Data Sources:**
https://www.airlinequality.com/airline-reviews/british-airways/

**Code Structure**
Below is a summary of the code sections included in this project:

1. Data Collection
The initial section focuses on installing necessary libraries and collecting data from an airline review website. The code uses web scraping techniques to retrieve customer reviews.

2. Data Preprocessing
Data preprocessing is a crucial step to clean and prepare the collected data for analysis. This section involves importing relevant libraries and performing tasks such as removing unwanted text using regular expressions, converting data types, and filtering data based on specific criteria.

3. Sentiment Analysis
Sentiment analysis is performed using two different methods: VADER sentiment analysis and a pre-trained RoBERTa model. This section details the process of calculating sentiment scores and categorizing them as negative, neutral, or positive.

4. Exploratory Data Analysis (EDA)
EDA is conducted to investigate possible reasons for negative reviews, understand rating distributions, and identify trends over the years. This section includes the creation of visualizations such as pairplots and word clouds.

5. Feature Selection and Random Forest Classifier
Feature selection is employed to choose relevant columns for building a machine learning model. A Random Forest Classifier is constructed to predict whether passengers would recommend the airline. The model is evaluated for accuracy, and a confusion matrix is generated to assess its performance.


**Project Organization**
The code is organized into distinct sections, making it easy to understand and navigate. Each section addresses a specific aspect of the project, from data collection to model evaluation.


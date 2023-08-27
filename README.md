# Marketing Campaign Response Prediction Model
[Dataset](https://github.com/JoaoCA98/Campaign_Response/blob/main/campaign.xlsx) | [Notebook](https://github.com/JoaoCA98/Campaign_Response/blob/main/Classification_Response_to_Marketing_Campaign.ipynb)
## Overview
This project involves the development of a predictive model to assist the Marketing Department of a retail company in predicting customer responses to marketing campaigns. The primary objective is to enhance campaign efficiency by identifying customers likely to respond to marketing efforts based on data from previous campaigns.

## Business Understanding
A profound understanding of the project's purpose is crucial to its success.

In the modern marketing landscape, data and algorithms play a pivotal role in decision-making. To make informed choices in marketing, harnessing the power of data analysis is paramount.

Features such as income, education, and past campaign responsiveness contribute to a model's ability to classify prospects as likely or unlikely to respond to future campaigns.

### Business Objectives
The project's core objectives are as follows:
1. Develop insights into the impact of variables on campaign responsiveness.
2. Build a predictive model that categorizes customers' likelihood of responding to marketing campaigns.
3. Enable the marketing team to optimize campaign targeting and resource allocation.

## Data Understanding
A thorough understanding of the dataset is imperative.

The dataset comprises 2,240 observations and 29 features, including 3 categorical and 26 numerical variables. Some observations:
- 'ID' is a unique numerical identifier.
- 'Year_Birth' indicates customers' birth years, with an average around 1968.8.
- 'Education' and 'Marital' are categorical variables.
- 'Income' has 24 missing values out of 2,240, and its distribution is skewed due to possible outliers.
- 'Kidhome' and 'Teenhome' denote the number of children and teenagers at home.
- 'Dt_Customer' signifies customers' enrollment dates, spanning between 2012 and 2014.
- 'Recency' indicates the days since the last purchase, following an almost uniform distribution.
- Spending behavior on various product categories is analyzed.
- 'NumDealsPurchases' represents deal purchases and follows a Log Normal distribution.
- Shopping habits, online purchases, and website visits are also considered.
- Customer responses to campaigns and complaints are binary.

## Data Preparation
Effective data preparation is essential for meaningful analysis.

Steps taken during data preparation:
1. Duplicated data was removed.
2. Missing values, outliers, and skewed distributions were addressed.
3. Categorical variable transformations were applied.
4. Feature engineering enhanced data for modeling.

## Model Evaluation
Several classification models were developed and evaluated:
1. Decision Tree
2. Support Vector Machine (SVM)
3. K Neighbors
4. Neural Networks
5. Naïve Bayes
6. Logistic Regression
7. Random Forest

The Random Forest model emerged as the best performer, showcasing a perfect recall score of 1.0. The focus on recall aimed to ensure the identification of customers highly likely to respond to campaigns, thereby minimizing the risk of missing out on potentially profitable customers.

## Conclusion
This project underscores the pivotal role of data science in modern marketing. By harnessing data insights and deploying advanced classification models, we can significantly enhance campaign responsiveness prediction. The project facilitates optimized resource allocation, ensuring that marketing efforts target the most responsive customer segments. The chosen Random Forest model, with its outstanding recall score, offers the best solution for accurately identifying customers likely to engage with marketing campaigns.

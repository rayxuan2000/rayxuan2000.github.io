---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
A first-year graduate student who aims to find data scientist internship, with more than one year experience in handling
data sets using machine learning / deep learning, big data framework and data visualization tools to make data-driven
decisions. Solid programming skills in Python and SQL and strong written communication and presentation skills.

Education
======
* University of California, San Diego    CA, US                                                     2023.10-2025.5 (expected)
  * Master in Electrical and Computer Engineering                                                                  GPA: 3.6/4
  * Core coursework: Programming for Data Analysis, Probability and Statistics for Data Science, Scientific Data Analysis and
Statistical Learning, Introduction to Visual Learning, Web Mining and Recommender Systems
* Southeast University    Jiangsu, China                                                                        2019.9-2023.6
  * Bachelor in Information Engineering (with honored degree)                                                     GPA: 3.75/4

Project experience
======
* RNN Based Prediction of Time Series in Stock Market
  * Performed a time series prediction using a LSTM (Long Short - Term Memory) model via PyTorch.
  * Implemented data normalization, divided dataset into two consecutive chunk (first full $$\frac{4}{5}$$ and last $$\frac{1}{5}$$) as training, testing set and loaded data into GPU memory.
  * Built a RNN (Recurrent Neural Network) with one LSTM module and a fully connected module, adopted
MMSE metric, imported Adam optimizer and set sliding window size to be 7 for predicting.
  * Trained RNN model with 300 epoch, presented parameters and loss figure with final loss 1.1 × 10^{−3}.

* MovieLens Data Analytics and Recommendation System Simulation
  * Built collaborative filtering algorithms based on Spark machine learning pipeline and deployed recommender system
in production scenario.
  * Implemented online analysis processing (OLAP) for movie data analysis.
  * Used Spark ML to predict ratings, leveraging Alternating Least Square (ALS) algorithm (matrix factorizarion
based ) for a large-scale dataset with resulting RMSE = 0.65.
  * Utilized above trained model and number k (top k liked) to recommend movies with random user id.

* NLP based Women’s E-Commerce Clothing Reviews
  * Used women’s clothing E-Commerce dataset (data size = 23486) to parse out and analyzed text via Python.
  * Split the corpus into positive and negative category based on exploratory data analysis (EDA), imported NLP tools
with stopwords and prepossessed each document via tokenization and stemming.
  * Implemented term frequency- inverse document frequency (TF-IDF) in bigram manner and trained K-Means
Clustering method (K = 5).
  * Performed Latent Dirichlet Allocation (LDA) method for topic modeling (topic number = 5).

* Machine Learning Model Based CTR Prediction
  * Used advertisement CTR(Click through rate) data sets to predict whether an advertisement will be clicked after each
impression via Python.
  * Utilized EDA and visualization to explore data patterns, along with data cleaning.
  * Performed frequency encoding, data split and standardization before model training.
  * Built and trained logistic regression, k-nearest-neighbors, random forest and XGBoost with 5-fold cross validation,
fine-tuned parameters in regularization term and attained best F1 score = 0.91.

* E-commerce Fraud Detection and Processing
  * Used E-commerce company transaction data sets (data size= 138376), built machine learning solution and gained insights
to mimimize enterprise fraud losses via Python.
  * Identified potential fraud country information based on ip address and reduce the look-up time by 22\%
  * Utilized feature engineering, built logistic regression and random forest model with and without SMOTE (Synthetic
Minority Oversampling Technique) method on minority set, performed parameter tuning, increased recall score by
20\% , and analyzed fraud characteristics by presenting feature importance.
  
Skills
======
* Programming Languages
  * Python (proficient), SQL (proficient), MATLAB (familiar)
* Analysis Skills and tools
  * Predictive Modeling, Exploratory Data Analysis, Data Cleaning (NumPy, Pandas, Scikit-learn), Data Visualization (Mat-
plotlib, Seaborn, Tableau), Big Data Analysis (SparkSQL, PySpark ), Deep Learning (PyTorch), Recommender System
  * A/B Testing, Hypothesis Testing, Inference for Independence, Fraud Detection

Honor & Award
======

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Projects by Prerak Agarwal


## Project 1: Standardized Testing, Statistical Summaries and Inference

### Problem Statement

The new format for the SAT was released in March 2016. With this new test format, **how can College Board improve the statewide participation rates for the SAT, as compared to the ACT?**

### Executive Summary

The datasets of aggregate SAT and ACT scores and participation rates from each state in the United States for 2017 and 2018 are given. I'll seek to identify trends in the data and combine data analysis with outside research to identify likely factors influencing participation rates in various states. Based on this data analysis, I will then make recommendations for College Board to help improve the SAT participation rates across the United States.

In this project, I utilize the following skillsets:
- Working with Jupyter notebooks for development and reporting
- Programmatically interacting with files and directories
- Exploratory Data Analysis (EDA) with Pandas
- Data Visualization with Matplotlib & Seaborn
- Basic Statistics (Distributions, Hypothesis Testing, etc.)


## Project 2: Ames Housing Data Analysis and Modelling

### Problem Statement

Using the information in the Ames Housing Dataset, is it possible to **predict the housing sale prices for houses in Ames, IA, USA (by employing different Machine Learning techniques)**? If yes, **how accurately can these housing sale prices be predicted?**

### Executive Summary

The Ames Housing Dataset containing observations of housing sales in Ames, Iowa, USA between 2006 and 2010 is given. I'll seek to apply different machine learning techniques to predict the sale price of houses based on their features. For ease of organization and understanding, the project has been divided into 3 separate Jupyter notebooks.

In order to predict the housing sale prices, I employ different methods of feature selection and machine learning techniques in this project. Some of the techniques/models employed in this project are:
- Multiple Linear Regression
- Regularization (Lasso, Ridge & ElasticNet)
- Recursive Feature Elimination with Cross-Validation (RFECV)
- Grid Search with Cross-Validation (GridSearchCV)
- Sequential Feature Selector

Each of the models built are evaluated using metrics such as R^2 score, Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) to explain how well the models may generalize to new data.


## Project 3: Classification of Subreddits

## Problem Statement

People seek advice from each other all the time, especially on social media platforms like **Reddit** (where they can maintain their anonymity). Given a post from a user seeking advice on a subreddit, is it possible to **categorize the post into different categories (by employing different Machine Learning techniques)**? If yes, **how accurately can this advice request categorization be done?**

## Executive Summary

To answer the above question and give Reddit a brief sample of the possibilities of machine learning, in this project, I seek to apply different data classification techniques to classify textual posts from **two subreddits - [r/relationship_advice](https://www.reddit.com/r/relationship_advice/) (dedicated for people seeking advice on their personal relationships) and [r/legaladvice](https://www.reddit.com/r/legaladvice/) (dedicated for people seeking semi-professional/professional advice on legal issues)**.

In order to do the classification modelling, about a 1000 posts were scraped from each of the two subreddits (sorted by newest at the time of scraping). Some of the techniques used to classify the posts from the two subreddits are:
- Logistic Regression
- K-Nearest Neighbors classifier
- Naive Bayes classifier
- Random Forests

Each of the models and their hyperparameters are optimized by passing them through **Cross-Validated Grid Searching (GridSearchCV)**. Different **NLP techniques** are also employed to convert textual data into machine-understandable forms of data, such as **Count Vectorization and TF-IDF Vectorization**. Each of the classification models built are assessed for generalizability using the **Accuracy metric**, with the final selected model being evaluated on further metrics such as **Sensitivity (True Positive Rate), Specificity (True Negative Rate) and ROC AUC**.


## Project 4: West Nile Virus (WNV) Predictions

## Problem Statement

West-Nile-Virus (WNV) is a mosquito-borne disease that has plagued the continental United States since 1999. Given historical data about WNV outbreak in the city of Chicago, IL, **how accurately is it possible to predict the locations with high potential of having mosquitoes carrying WNV?** Also, **what are some of the factors that contribute to the growth and spread of the virus in mosquitoes?**

## Executive Summary

WNV outbreaks typically intensify over as little as a couple of weeks. Research and operational experience shows that increases in WNV infection rates in mosquito populations can provide an indicator of developing outbreak conditions several weeks in advance of increases in human infections. Aggressive and timely efforts to reduce the number of infected adult mosquitoes will optimally impact human WNV case incidence.

The goal of this project is to derive a plan to deploy pesticides throughout the city of Chicago, IL. The modelling techniques and strategies will be presented to biostaticians, epidemiologists, American Public Health Service and decision makers from Centers for Disease Control and Prevention (CDC). Some of the techniques employed in this project are:
- Random Forests
- Support Vector Classifier
- Gradient Boosting
- Class balancing techniques such as **SMOTE**, **ADASYN** & **ClusterCentroids**
- Deployment through **Flask**

Each of the models built are assessed for generalizability using the **Accuracy** and **Sensitivity** metrics (due to the nature of our predictions being disease related, with the minimisation of *false negatives* being the most important factor).


## Project 5 (Capstone): Age Classification using Facial Images

## Problem Statement

**Given an image of someone's face, is it possible for a computer to guess their age? If yes, how accurately can their age be guessed?**

## Executive Summary

Computer vision is a rapidly growing field with many interesting applications. A huge area of study within this field is about the facial features of humans, and how they relate to an individual's characteristics, such as age, gender, race, etc. In this project, I explore one such application of computer vision - to guess someone's age based on an image of their face.

Computer vision applications nowadays rely more and more on deep learning techniques and neural networks, because of an increase in availability and ease of access to computers with much higher processing capabilities. However, to appreciate the **traditional machine learning** way of doing things in data science and to truly appreciate the power and possibilities of **deep learning**, in this project, I seek to explore the traditional machine learning approach to this problem as well (image feature extraction followed by classification modelling using the ***scikit-learn*** library). To explore the deep learning approach in this project, I utilize the ***TensorFlow*** library.

The project is done entirely on **Google Colab**. I utilize the following methods and libraries to train age classification models for facial images:
- ***OpenCV*** and ***scikit-image*** for Image Processing and Feature Extraction
- **scikit-learn** RandomForestClassifier & Support Vector Classifier (SVC) for traditional Machine Learning approach
- **Convolutional Neural Networks (CNNs)** using **TensorFlow** for Deep Learning approach

The description and walkthrough for the entire project is available as an **[article on Towards Data Science](https://towardsdatascience.com/age-detection-using-facial-images-traditional-machine-learning-vs-deep-learning-2437b2feeab2)**. The **[source code](https://drive.google.com/drive/folders/1Z-yE8YDbf_C8nWmcqpkeSf06a23PvrqJ?usp=sharing) Google Colab notebooks** and the **[datasets](https://drive.google.com/drive/folders/1dZhJNGmdoO1La6MOJRfUYxDZwIa-hXNX?usp=sharing)** for this project are accessible **on Google Drive**.
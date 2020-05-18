# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 

# Project_3 Xbox One vs PS4

### Context and Problem Statement

Using Reddit's API to collect posts from XBox One & PS4 subreddits, then use NLP to train a classifier to differentiate which subreddit the post came from.

Microsoft can use the classifier to efficiently filter posts from other social media platform for further analysis.Success will be evaluated based on how much improvement over the baseline score.

---

## Executive Summary


### Contents:

- [Webscraping](#Webscraping)
- [Import libraries and Data](#Import-libraries-and-Data)
- [Data Cleaning & Exploratory Data Analysis](#Data-Cleaning-&-Exploratory-Data-Analysis)
- [Modeling](#Modeling)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Sources](#Sources)

---

### 1.Webscraping

Two Reddit urls are webscraped repeatedly via a loop

### Import libraries and Data

After importing libraries, data was loaded.

### Data Cleaning & Exploratory Data Analysis

Data cleaning was performed and the overview of summary statistics is shown.

### Modeling
### 4.1 Logistic Regression Model
### 4.2 Naive Bayes model
### 4.3Logistic Regression Model with Pipeline
### 4.4MultinomialNB Model with Pipeline

### Conclusions and Recommendations
- Baseline score:0.523305

Logistic Regression Model with Pipeline training score: 0.9900662251655629

Logistic Regression Model with Pipeline testing score: 0.9682539682539683

MultinomialNB Model with Pipeline training score: 0.9688741721854305

MultinomialNB Model with Pipeline testing score: 0.9629629629629629

Based on the best results, Logistic Regression testing with Pipeline scored the better than MultinomialNB. However, both the results are extremely close to each other. Moreover, they are also very close to 1, which might hint at overfitting. Therefore, more data is required to address the overfitting problem. Success will be evaluated based on how much improvement over the baseline score.

This project has successfully trained a classifier to differentiate which subreddit the post came from. Consequently, Microsoft can use the classifier to efficiently filter posts from other social media platform for further analysis.

---

### Sources:

- [Xboxone](https://www.reddit.com/r/xboxone/)
- [Reddit](https://www.reddit.com/r/xboxone.json)
- [PS4](https://www.reddit.com/r/PS4/)
- [Reddit](https://www.reddit.com/r/PS4.json)

# Hw4 - Time Series Classification (Part2) - Binary and Multi-class classification

### Introduction
- Binary classification using logistic regression
- Binary classification using L1-penalized logistic regression
- Multi-class classification (The realistic case) using L1-penalized multinomial regression model and a Naïve Bayes’ classifier
- Compare all models


### Data description
Activity Recognition System  based on Multisensor data fusion (https://archive.ics.uci.edu/dataset/366/activity+recognition+system+based+on+multisensor+data+fusion+arem)

The dataset contains 7 folders that represent seven types of activities. In each folder, there are multiple files each of which represents an instant of a human performing an activity. 
Each file contains 6 time series collected from activities of the same person, which are called avg rss12, var rss12, avg rss13, var rss13, vg rss23, and ar rss23. There are 88 instances in the dataset, each of which contains 6 time series and each time series has 480 consecutive values.

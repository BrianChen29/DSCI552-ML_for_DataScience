# Hw3 - Time Series Classification (Part1) - Feature creation and extraction
### Introduction
Classification of time series usually needs extracting features from them. In this problem, we focus on time-domain features. Minimum, maximum, mean, median, standard deviation, 1st quartile, and 3rd quartile are used in this problem.
Use Python's Bootstrapped build a 90% bootstrap confidence interval for the standard deviation of each feature.


### Data description
Activity Recognition System  based on Multisensor data fusion (https://archive.ics.uci.edu/dataset/366/activity+recognition+system+based+on+multisensor+data+fusion+arem)

The dataset contains 7 folders that represent seven types of activities. In each folder, there are multiple files each of which represents an instant of a human performing an activity. 
Each file contains 6 time series collected from activities of the same person, which are called avg rss12, var rss12, avg rss13, var rss13, vg rss23, and ar rss23. There are 88 instances in the dataset, each of which con- tains 6 time series and each time series has 480 consecutive values.

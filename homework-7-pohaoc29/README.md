# Hw7 - Anuran Calls (MFCCs) Data Set - Multi-class and Multi-Label Classification

### Introduction
Multi-class & Multi-Label Classification
* Using Support Vector Machines
* Using K-Means Clustering - Monte-Carlo Simulation

Each instance has three labels: Families, Genus, and Species. Each of the labels has multiple classes. We wish to solve a multi-class and multi-label problem.


### Data description
#### Anuran Calls (MFCCs) Data Set (https://archive.ics.uci.edu/dataset/406/anuran+calls+mfccs)

This dataset was used in several classifications tasks related to the challenge of anuran species recognition through their calls. It is a multilabel dataset with three columns of labels. This dataset was created segmenting 60 audio records belonging to 4 different families, 8 genus, and 10 species. Each audio corresponds to one specimen (an individual frog), the record ID is also included as an extra column. We used the spectral entropy and a binary cluster method to detect audio frames belonging to each syllable.

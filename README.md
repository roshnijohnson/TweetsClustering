# K-Means Algorithm

## Description:

A K-Means algorithm is implemented using Jaccard Distance.
We are going to use the following dataset for this exercise: https://archive.ics.uci.edu/ml/datasets/Health+News+in+Twitter
Choose the cnnhealth.txt file as a data file from the dataset.

The Input variables are:
K cluster value,
Number of iternations,
Dataset

Before running the K-Means algorithm, the data is pre-processed:

- Removed the tweet id and timestamp
- Removed any word that starts with the symbol @ e.g. @AnnaMedaris
- Removed any hashtag symbols e.g. convert #depression to depression
- Removed any URL
- Converted every word to lowercase in the tweet

The dataset used here is from UCI and can be accessed directly using the link provided in the code.

## Requirements & Libraries used:

- Python 3
- Pandas
- NumPy

## Running the code:

- Click on the following links to open the Colab notebook:

https://colab.research.google.com/drive/1ZlDVrbX6ZVbjNCsRjmc_nhvgbSYURvCz#scrollTo=fXqCOlTYfEGJ

- Kindly upload the cnnhealth.txt file in your local google colab environment before running the code. File is attached in zip folder.

- To execute the code in each cell, select it with a click and then either press the play button to the left of the code, or use the keyboard shortcut "Command/Ctrl+Enter"

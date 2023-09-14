# TweetAura

This project focuses on the detection of hate speech in tweets. The objective is to classify tweets into two categories: those containing racist or sexist sentiments and those that do not. This classification is done using machine learning techniques, specifically logistic regression.

## Table of Contents
- [Introduction]
- [Dataset Information]
- [Preprocessing]
- [Exploratory Data Analysis]
- [Input Split]
- [Model Training]
- [Results]
- [Usage]
- [Contributing]
- [License]

## Dataset Information
The dataset used for this project is provided in the form of a CSV file. It contains 31,962 labeled tweets, with each entry including a tweet ID, a label (1 for racist/sexist and 0 for non-racist/sexist), and the tweet text.

## Preprocessing
The dataset preprocessing steps include:
- Removing Twitter handles (@user)
- Removing special characters, numbers, and punctuation
- Removing short words
- Tokenization of words
- Stemming using Porter Stemmer

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) is performed to gain insights into the dataset. Key EDA steps include:
- Word cloud visualization of frequent words in all tweets
- Word cloud visualization of frequent words in non-racist/sexist tweets
- Word cloud visualization of frequent words in racist/sexist tweets
- Analysis of hashtags in tweets

## Input Split
The dataset is split into training and testing sets. Features are extracted using Count Vectorization with specific parameters.

## Model Training
A logistic regression model is trained using the training data. Model performance is evaluated using F1 score and accuracy metrics. Probability thresholds are also used to optimize the model's performance.

## Results
The model achieves a certain F1 score and accuracy on the test dataset. You can insert the actual scores and results obtained during your experiments here.

## Usage
To use this code and dataset for your own hate speech detection task, follow these steps:
1. Clone this repository to your local machine.
2. Ensure you have the necessary libraries and dependencies installed.
3. Run the provided Jupyter Notebook or Python script to preprocess the data, perform EDA, split the dataset, train the model, and evaluate the results.

## Contributing

Contributors are always welcomed 🫶

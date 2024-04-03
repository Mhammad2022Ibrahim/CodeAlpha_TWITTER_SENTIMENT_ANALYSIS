# CodeAlpha_TWITTER_SENTIMENT_ANALYSIS

# Sentiment Analysis on Twitter Data

## Overview:
This project focuses on performing sentiment analysis on Twitter data to classify tweets into either `racist/sexist` or `non-racist/sexist` categories. It covers data preprocessing steps, feature extraction techniques like `Bag-of-Words` and `TF-IDF`, and building predictive models using various classifiers.
## Dataset
The dataset used in this project is stored in `train_twitter.csv`

# Contents:
## Data Cleaning:
Removing Twitter handles, special characters, and short words.
Tokenization and stemming of tweets.

## Exploratory Data Analysis:
Generating wordclouds to visualize common words.
Analyzing hashtag trends in tweets based on sentiments.

## Feature Extraction:
Creating Bag-of-Words and TF-IDF features from cleaned tweets.

## Model Building:
Utilizing `Logistic Regression`, `Random Forest`, `Support Vector Machine`, and `XGBoost classifiers`.
Evaluating model performance metrics like `F1 Score`, `Accuracy`, `Precision`, and `Recall`.

## Instructions for Running the Notebook:
Ensure the necessary libraries are imported using the provided code snippets.
Read the data from the CSV files and follow the data preprocessing steps.
Execute the code cells sequentially for `tokenization`, `stemming`, and `story generation`.
Visualize common words and hashtags for analysis.
Extract features using Bag-of-Words and TF-IDF methods.
Build and evaluate sentiment analysis models with different classifiers.

## Usage

### Google Colab

To use the `CodeAlpha_TWITTER_SENTIMENT_ANALYSIS.ipynb` file with Google Colab, follow these steps:

1. Open Google Colab.
2. Click on `File > Open notebook`.
3. Select the `GitHub` tab.
4. Enter the URL of your GitHub repository and press Enter.
5. Click on the `CodeAlpha_TWITTER_SENTIMENT_ANALYSIS.ipynb` file to open it.
6. You can now run and modify the notebook in Google Colab.

## Additional Information:
The notebook contains detailed code snippets, explanations, and visualizations for each step.
Make sure to have the required packages installed to run the notebook successfully.
Feel free to modify the code or experiment with different models for enhanced results.
Credits:
This project is done as part of a data analysis and machine learning task.

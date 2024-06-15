# News Popularity Prediction

This repository contains the project files for the "News Popularity Prediction" project, part of the IE 7275: Data Mining in Engineering course at Northeastern University. The project aims to predict the popularity of news articles published by Mashable over a two-year period.

## Project Overview

The goal of this project is to build a predictive model to estimate the social media shares of articles published by Mashable. By analyzing a dataset hosted on the UCI Machine Learning Repository, we seek to identify the factors that significantly impact the virality of news articles.

## Data Description

The dataset consists of 39,797 instances, each with 61 variables. The variables include content attributes like the number of words, type of content, and publication day. The target variable is "shares", representing the count of social media shares for each article.

## Data Mining Tasks

### Data Pre-processing
- Removal of extraneous spaces and irrelevant columns.
- Conversion of data types for better analysis consistency.

### Feature Selection and Extraction
- Utilization of Correlation Matrices and Recursive Feature Elimination to refine the feature set.

### Models Implemented
- Logistic Regression
- Decision Trees
- Random Forest Classifier
- kNN Classifier

## Installation

To replicate the analysis:
1. Clone this repository.
2. Ensure Python and required packages (`pandas`, `numpy`, `scikit-learn`) are installed.
3. Run the Jupyter notebooks provided in the repository.

## Results

The Decision Trees model exhibited superior performance, achieving an accuracy of 99.987% in classifying articles as popular or not based on their predicted shares.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## References

- UCI Machine Learning Repository: [Online News Popularity Dataset](https://archive.ics.uci.edu/dataset/332/online+news+popularity)

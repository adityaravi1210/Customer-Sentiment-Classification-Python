# Sentiment Analysis on Amazon Reviews using Logistic Regression

This project focuses on conducting sentiment analysis on reviews from Amazon. The main objective is to classify each review into one of two sentiments: positive or negative, using logistic regression.

## Dataset Overview

The dataset used in this project comprises reviews and their associated sentiments. It contains the following attributes:

- **review**: Text of the review left by a user on Amazon.
- **sentiment**: Labeled sentiment of the review, which can be either "positive" or "negative".

Sample data:

| review                                                    | sentiment |
|-----------------------------------------------------------|-----------|
| So there is no way for me to plug it in here in the US... | negative  |
| Good case, Excellent value.                               | positive  |
| Great for the jawbone.                                    | positive  |

## Analysis Approach and Statistical Methods

1. **Text Vectorization**: Using the `CountVectorizer`, the reviews are converted into numerical vectors suitable for machine learning.
2. **Logistic Regression**: A logistic regression model is trained to classify the reviews based on their content.
3. **Model Evaluation**: The accuracy of the logistic regression model is evaluated using the model's score and a confusion matrix.
4. **Adjusting Classification Threshold**: The threshold for classification in logistic regression is adjusted to observe its effect on the model's predictions.

## Libraries and Tools Used

- **Pandas**: Used for data manipulation and analysis.
- **Scikit-learn**: Specifically, the `CountVectorizer` from `sklearn.feature_extraction.text` is used for text vectorization, and `LogisticRegression` from `sklearn.linear_model` is used for classification. The confusion matrix is derived using `sklearn.metrics`.

## Further Details

For a deeper dive into the analysis, methodology, and code, refer to the Jupyter notebook: `Review Sentiment Analysis Python.ipynb`.



# NLP Sentiment Analysis Using Machine Learning

## Project Overview

This project uses Natural Language Processing (NLP) and machine learning to classify movie reviews as positive or negative.

The project applies text preprocessing, TF-IDF feature extraction, and two classification algorithms to evaluate sentiment prediction performance.

## Objectives

* Clean and preprocess movie review text.
* Convert text into numerical features using TF-IDF.
* Train Multinomial Naive Bayes and Logistic Regression classifiers.
* Evaluate models using accuracy, precision, recall, and F1-score.
* Predict sentiment for custom user-provided reviews.

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Hugging Face Datasets
* Google Colab

## Dataset

The project uses the IMDb movie reviews dataset, containing positive and negative movie reviews.

Dataset: https://huggingface.co/datasets/stanfordnlp/imdb

## Project Workflow

1. Load the movie review dataset.
2. Clean text and remove HTML tags.
3. Convert text to lowercase.
4. Remove stopwords and perform lemmatization.
5. Split data into training and testing sets.
6. Extract TF-IDF features using a maximum of 5,000 features.
7. Train Multinomial Naive Bayes.
8. Train Logistic Regression.
9. Compare model performance.
10. Predict sentiment for custom reviews.

## Machine Learning Models

### 1. Multinomial Naive Bayes

A probabilistic classification algorithm used to classify text based on learned word-feature patterns.

### 2. Logistic Regression

A classification algorithm used to predict whether a review expresses positive or negative sentiment.

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

Actual evaluation results are available in the notebook.

## Interactive Prediction

The notebook includes a `predict_sentiment()` function that accepts a custom review and predicts whether its sentiment is positive or negative.

Example:

```python
predict_sentiment("This movie was fantastic and entertaining!")
```

## How to Run

1. Download or clone this repository.
2. Open `NLP_Sentiment_Analysis.ipynb` in Google Colab.
3. Run the notebook cells in order.
4. Allow the required libraries and dataset to load.
5. Review the evaluation results.
6. Test custom reviews using the prediction function.

## Future Improvements

* Test additional machine learning algorithms.
* Compare different TF-IDF configurations.
* Add a simple web interface for predictions.
* Explore deep learning models for sentiment classification.

## Author

Created as a Natural Language Processing and Machine Learning project.

# Sentiment Analysis and Topic Modeling on IMDB Movie Reviews

## Project Overview

This project involves analyzing the IMDB dataset containing 50,000 movie reviews to perform:

- *Sentiment Analysis*: Classifying reviews as positive or negative.
- *Topic Modeling*: Identifying common themes discussed in the reviews.

## Objectives

- Build classifiers to categorize reviews.
- Compare models using accuracy, precision, recall, and F1-score.
- Discover common topics or themes in the reviews.
- Interpret and visualize the discovered topics.

## Dataset

The dataset consists of 50,000 movie reviews labeled as positive or negative. It is balanced, with an equal number of positive and negative reviews.

## Methodology

### 1. Data Preprocessing

- *Text Cleaning*: Removal of HTML tags, special characters, and stopwords.
- *Tokenization*: Splitting text into individual words.
- *Lemmatization/Stemming*: Reducing words to their base forms.

### 2. Sentiment Analysis

- Implemented models:
  - Logistic Regression
  - Naive Bayes
  - Long Short-Term Memory (LSTM) Network
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

### 3. Topic Modeling

- Techniques used:
  - Latent Dirichlet Allocation (LDA)
  - Non-negative Matrix Factorization (NMF)
- Visualization tools:
  - Word Clouds
  - Bar Charts of Top Words per Topic

## Results

- *Sentiment Analysis*: Achieved highest accuracy with the LSTM model.
- *Topic Modeling*: Identified key themes such as acting, screenplay, and music.

## Conclusion

The project successfully built models to classify sentiments and identify prevalent topics in movie reviews, providing insights into audience opinions.

## How to Run

1. Clone the repository.
2. Install required libraries: pip install -r requirements.txt
3. Run the Jupyter Notebook: jupyter notebook analysis.ipynb

## References

- [IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- [NLTK Documentation](https://www.nltk.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

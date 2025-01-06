# *Sentiment Analysis and Topic Modeling on IMDB 50k Reviews*

## *Overview*
This repository contains multiple projects focused on sentiment analysis and topic modeling using machine learning (ML), deep learning (DL), and natural language processing (NLP) techniques. The IMDB 50k reviews dataset is utilized to explore, preprocess, analyze, and derive meaningful insights about movie reviews.

---

## *Repository Structure*

### *sentiment_ML.ipynb*
*Description*:
- Performs sentiment analysis on the IMDB 50k reviews dataset using:
  - *Naive Bayes (NB)*
  - *Logistic Regression (LR)*

*Key Features*:
- Comparison of metrics like accuracy, precision, recall, and F1 score for both models.
- Insights into model performance for classification tasks.

*Colab Link*:  
[View Sentiment Analysis with ML](https://colab.research.google.com/drive/1445ps_cTLuqe4IPcRlQ1kSZIHBmuKJLP#scrollTo=0iZUYjYZtQXR)

---

### *IMDb-Sentimenet-DL.ipynb*
*Description*:
- Applies deep learning to sentiment classification using:
  - *Long Short-Term Memory (LSTM) networks*

*Key Features*:
- Implementation of LSTM for textual data.
- Analysis of performance metrics.

*Colab Link*:  
[View Sentiment Analysis with DL](https://colab.research.google.com/drive/1binEtnIPrqz4CE5HOCh1sYXtf7NWQ3px#scrollTo=yQ-7wgJDtRT6)

---

### *Topic_Modeling_BERT.ipynb*
*Description*:
- Performs topic modeling on the IMDB 50k reviews dataset using *BERTopic*.

*Key Features*:
- Extracts topics to discover themes in reviews.
- Provides insights into common discussion points such as acting, screenplay, and music.

*Colab Link*:  
[View Topic Modeling with BERTopic](https://colab.research.google.com/drive/1XBa5bXoxY5uaZDz4yBXAIAa_yy4DRERq#scrollTo=nOsA37CatOhU)

---

### *index.ipynb*
*Description*:
- A comprehensive file combining all the analyses and comparisons in one place.

*Key Features*:
1. *Exploratory Data Analysis (EDA)*:
   - Visualizations of demographic and textual data.
   - Identification of the best and worst-reviewed movies by genre.
2. *Sentiment Analysis Comparison*:
   - Metrics comparison for Naive Bayes (NB), Logistic Regression (LR), and LSTM models.
3. *Topic Modeling with BERTopic*:
   - Extracting and visualizing key topics in the reviews.
4. *Preprocessed data and model training insights.*

*Colab Link*:  
[View Combined Analysis](https://colab.research.google.com/drive/1_zblryNdS6zc--F5YGk3yXrPji3E5NUi#scrollTo=x0x-W6ZE1DOI)

---

## *Installation*

To use the notebooks, clone this repository and set up the required environment:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
pip install -r requirements.txt



## Acknowledgments

- Dataset: [Kaggle IMDB 50k Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Libraries: Scikit-learn, TensorFlow, BERTopic, Pandas, Matplotlib, and more.

---

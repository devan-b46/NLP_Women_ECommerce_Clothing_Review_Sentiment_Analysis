# NLP for Customer Insights: A Deep Dive into Women's Clothing Reviews

![image](files/1552941175192.jpeg)

---

This project presents a comprehensive case study on Women's E-Commerce Clothing Reviews, focusing on two key areas: Sentiment Analysis and Predictive Modeling. The primary objective was to extract actionable insights from unstructured text data to understand customer sentiment and predict how a product might be rated based on the language of the review.


## Sentiment Analysis
Conducted a comparative sentiment analysis using multiple popular NLP libraries:

- **spaCy**: Leveraged for its powerful linguistic features and text processing capabilities to prepare the data for analysis.

- **TextBlob**: Employed for its straightforward and accessible API to get polarity and subjectivity scores.

- **NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner)**: Utilized for its effectiveness on social media and short, informal text, which is common in reviews.

---

## WordCloud Analysis
* The Positive WordCloud visually confirmed that attributes like *fit*, *comfort*, *color*, and *quality* (using words like 'love', 'perfect', 'great', 'soft', 'beautiful') are key drivers of high ratings. 

* In stark contrast, the Negative WordCloud immediately highlighted significant customer pain points, with words like *small*, *tight*, *cheap*, *return*, and *disappointed* being most prominent.

---

## Predictive Analysis
1. **Text Preprocessing & Feature Engineering**: Cleaned and prepared the text data. Utilized TF-IDF Vectorizer to convert the corpus of reviews into a meaningful matrix of numerical features, giving weight to words that are more important to a specific review.
   
3. **Data Visualization**: Generated WordClouds for different sentiment categories to visually identify the most frequent and prominent words associated with positive and negative feedback
   
5. **Model Building**: Implemented a Logistic Regression model, a robust and interpretable classification algorithm, to predict the sentiment or star rating of a review. The model was trained on the TF-IDF features to learn the patterns in the language that correlate with customer satisfaction.



---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spaCy&logoColor=white" alt="spaCy"/>
  <img src="https://img.shields.io/badge/NLTK-3776AB?style=for-the-badge&logo=NLTK&logoColor=white" alt="NLTK"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/Matplotlib-3776AB.svg?style=for-the-badge&logo=Matplotlib&logoColor=white" alt="Matplotlib"/>
</p>

### Core Technologies
* **Language:** Python
* **Environment:** Jupyter Notebook

### Data Handling & Analysis
* **Pandas:** Used for loading, cleaning, and structuring the e-commerce review dataset.

### Natural Language Processing (NLP)
* **spaCy:** Leveraged for efficient text preprocessing, including tokenization and lemmatization.
* **NLTK (VADER):** Implemented for its powerful sentiment analysis on short, informal review texts.
* **TextBlob:** Used for comparative sentiment scoring to validate results.

### Machine Learning & Predictive Analysis
* **Scikit-learn:** Employed for:
    * `TfidfVectorizer`: To convert text data into numerical features.
    * `LogisticRegression`: To build and train the predictive model.

### Data Visualization
* **WordCloud:** To create insightful visualizations of the most frequent positive and negative words.
* **Matplotlib & Seaborn:** For generating plots and charts during exploratory data analysis (EDA).

  



---
That's all folks

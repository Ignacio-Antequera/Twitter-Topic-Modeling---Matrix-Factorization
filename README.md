# Twitter Topic Modeling with Non-negative Matrix Factorization

## Introduction

This project aims to analyze topics found on Twitter related to the pandemic using Non-negative Matrix Factorization (NMF). The goal is to extract latent topics from the tweets and gain insights into the discussions and trends surrounding the pandemic on Twitter.

Link to visualize demo of the project on the browser: [Twitter Topic Modeling with Non-negative Matrix Factorization](https://twitter-topic-modeling-antequera.netlify.app/)

## Dataset

The dataset used in this project consists of Twitter data related to the pandemic in 2020. The dataset was obtained from Kaggle and preprocessed to remove non-English tweets, URLs, punctuation, and stop words. Additionally, common COVID-related terms were removed to improve the analysis.

## Tools and Methods

### Tools:
- Python programming language
- Libraries:
  - NumPy
  - Pandas
  - Matplotlib
  - Plotly
  - scikit-learn

### Methods:
1. Data Preprocessing:
   - Removal of non-English tweets, URLs, punctuation, and stop words.
   - Cleaning the text data to prepare it for analysis.

2. Topic Modeling with NMF:
   - Generation of the TF-IDF matrix to represent the text data numerically.
   - Application of Non-negative Matrix Factorization (NMF) to extract latent topics from the TF-IDF matrix.
   - Visualization of the topic modeling results using 3D scatter plots.

3. Outlier Detection:
   - Identification of outlier tweets based on their projections in the topic space.
   - Extraction of unique outlier tweets from the dataset.

## Project Development

1. **Data Loading and Preprocessing:**
   - The Twitter dataset was loaded into a Pandas DataFrame.
   - Data preprocessing steps were applied to clean the text data.

2. **Topic Modeling:**
   - The TF-IDF matrix was generated using scikit-learn's TfidfVectorizer.
   - Non-negative Matrix Factorization (NMF) was applied to extract topics from the TF-IDF matrix.
   - The topics were visualized using 3D scatter plots to understand the distribution of tweets in the topic space.

3. **Outlier Detection:**
   - Outlier tweets were identified based on their projections in the topic space.
   - Unique outlier tweets were extracted from the dataset.

## Conclusion

This project provided valuable insights into the topics and discussions surrounding the pandemic on Twitter. By leveraging Non-negative Matrix Factorization (NMF), we were able to extract latent topics from the tweet data and gain insights into the trends and discussions on Twitter related to the pandemic.

The project utilized various tools and methods in Python, including data preprocessing, topic modeling with NMF, visualization, and outlier detection. Overall, it served as a valuable learning experience in analyzing textual data from social media using machine learning techniques.

## Author
Ignacio Antequera Sanchez

Kindly find my contact details listed below for your convenience. Your input is greatly appreciated.

***

[LinkedIn](https://www.linkedin.com/in/ignacio-antequera)  ||  [GitHub](https://github.com/Ignacio-Antequera)  ||  [Leetcode](https://leetcode.com/Ignacio_antequera)
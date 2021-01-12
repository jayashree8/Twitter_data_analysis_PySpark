# Twitter data analysis and model building using PySpark

The aim of the project is to analyze Twitter data to understand the positive and negative tweets along with the most frequently used words in form of bi-grams and tri-grams. The words which make up the positive and negative tweets are also determined.

## Experimental setup:
1) Data Collection
This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the Twitter API. The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment.

2) Exploratory Analysis of the Data
Various visualizations were generated such as count of respective class-labels, frequency of words in tweets, most common words in each class, n-gram analysis, etc.

3) Data Processing
Following data cleaning steps were followed: Elimination of 
HTML tags
Punctuations
Typos / Misspelled words
Emojis
Stop words

4) Data Modeling
The process of modeling means training a machine-learning algorithm to predict the labels from the features, tuning it for the business need, and validating it on holdout data. The following was achieved via two phases which is
Feature Extraction using TF-IDF
Classification with Logistic Regression

5) Data Interpretation
The model is real-world ready to interpret any text. The text can simply be passed through the above pipeline where it gets cleaned, tokenized, its features are extracted, and then classified as a positive or negative tweet

## Results:
![result](https://github.com/jayashree8/Twitter_data_analysis_PySpark/blob/main/Assets/img1.PNG)
![result](https://github.com/jayashree8/Twitter_data_analysis_PySpark/blob/main/Assets/img2.PNG)
![result](https://github.com/jayashree8/Twitter_data_analysis_PySpark/blob/main/Assets/img3.PNG)
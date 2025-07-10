# SMS Spam Classifier

A machine learning project to classify SMS messages as **spam** or **not spam** using basic text analysis and natural language processing.

---

## Project Overview

This project walks through a complete ML pipeline — from raw SMS data to a trained spam detection model. The dataset used is the **SMS Spam Collection** from the UCI Machine Learning Repository.

---

## Data Exploration & Visualization

- Loaded and inspected the dataset  
- Cleaned the text and added basic features like:
  - Number of words  
  - Number of characters  
  - Number of sentences  
- Performed visual EDA using:
  - Histograms and bar plots  
  - WordClouds for both spam and ham messages  

---

## Text Preprocessing

- Built a custom preprocessing function that:
  - Removed stopwords and punctuation  
  - Converted text to lowercase  
  - Applied stemming  
- Stored the cleaned version in a new column `transformed_text`

---

## Feature Extraction

- Vectorized the text using:
  - **CountVectorizer**  
  - **TF-IDF Vectorizer**

---

## Model Training & Evaluation

Trained and compared the following models on vectorized data:

- **Naive Bayes variants**:
  - GaussianNB  
  - MultinomialNB  
  - BernoulliNB  
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**

Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score

---

## Insights & Results

- **Multinomial Naive Bayes with TF-IDF** provided the best balance across metrics  
- **Logistic Regression** also performed strongly, especially in precision and F1  
- Vectorization technique significantly impacted model performance

---

## Tech Stack

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  
- Git & GitHub  

---

## Files

- `spam_classifier.ipynb`: Complete notebook (data analysis → modeling)  
- `spam.csv`: Dataset (UCI SMS Spam Collection)  
- `README.md`: Project summary and documentation  

---

## Author

Created by **Abhishek Godiyal**



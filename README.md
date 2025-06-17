
# 💬 SMS Spam Classifier

A simple machine learning project to classify SMS messages as **spam** or **not spam** using basic text analysis and natural language processing.

---

## ✅ Day 1 Progress

- Loaded the dataset  
- Performed initial data cleaning  
- Added basic features:
  - Number of words
  - Number of characters
  - Number of sentenses
- Did some basic exploratory data analysis (EDA)

---

## 🔄 Day 2 Progress

- Continued EDA:
  - Compared spam and ham messages on character count, word count, and sentence count  
  - Visualized distributions using histograms and bar plots  
  - Generated WordClouds for spam and ham messages to highlight common words  
- Performed further preprocessing:
  - Implemented a custom preprocessing function (stopword removal, punctuation removal, stemming)  
  - Created a new column `transformed_text` with cleaned and processed text  
- Verified text cleaning effectiveness with sample outputs  

---

## 🚀 Day 3 Progress

- Vectorized the cleaned text using two methods:
  - **CountVectorizer**
  - **TfidfVectorizer**
- Trained and evaluated three Naive Bayes models with both CountVectorizer and TfidfVectorizer:
  - **GaussianNB** 
  - **MultinomialNB** 
  - **BernoulliNB** 
- Compared model performances using:
  - Accuracy, Precision, Confusion Matrix
- Analyzed how different vectorization techniques and Naive Bayes variants affect performance

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  
- Git & GitHub  

---

## 📁 Files

- `spam_classifier.ipynb`: Jupyter notebook (Day 1 to Day 3 Work)  
- `spam.csv`: Dataset used for training (UCI Machine Learning : SMS Spam Collection Dataset)  
- `README.md`: Project overview  

---

## 🙌 Author

Created by **Abhishek Godiyal**


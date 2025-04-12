# Brainwave_Matrix_Intern_Task2

# 📊 Sentiment Analysis using NLP and Machine Learning

This project focuses on building a **Sentiment Analysis** model that classifies text data (e.g., tweets, reviews, or comments) into **positive**, **negative** sentiment using Natural Language Processing (NLP) and machine learning techniques.

## 🔍 Project Overview

The workflow of the project includes:

1. **Data Preprocessing**:
   - Text cleaning: Removing punctuation and stopwords
   - Tokenization and lemmatization using **spaCy**
   - Converting text into vector form using **Gensim's Glove Twitter embeddings (glove-twitter-25)**

2. **Feature Engineering**:
   - Each processed text is converted into a 25-dimensional mean word vector
   - Null vectors are removed and data is cleaned for consistency

3. **Exploratory Data Analysis (EDA)**:
   - Visualizing sentiment distribution
   - Plotting sentiment trends over time

4. **Model Training**:
   - Splitting the dataset using `train_test_split` with stratification
   - Training a **Random Forest Classifier** with `class_weight='balanced'` to account for class imbalance

5. **Evaluation**:
   - Model evaluated using **accuracy score**, **F1 score**, and **classification report**
   - Visualizations include sentiment timeline

## 🛠️ Technologies Used

- Python 
- Pandas & NumPy
- spaCy (for text preprocessing)
- Gensim (for word embeddings)
- Scikit-learn (for modeling and evaluation)
- Matplotlib (for visualization)

## ✅ Final Results

- **Accuracy**: `87.43%`  
- **F1 Score**: `88.25%`

📚 Content-Based Book Recommendation System

This project implements a content-based book recommendation system using TF-IDF vectorization and cosine similarity to suggest books based on user input queries.

## 🎯 Features
- Processes book descriptions from Kaggle's Books Dataset
- Text preprocessing (stopword removal, tokenization, normalization)
- TF-IDF vectorization of book descriptions
- Cosine similarity for matching user queries
- Returns top-N recommendations with similarity scores

## 📂 Dataset
Uses the **Books Dataset** from Kaggle:  
[Kaggle Dataset Link](https://www.kaggle.com/datasets/elvinrustam/books-dataset)  
Contains:
- Book titles
- Descriptions
- Categories

## ⚙️ Installation & Setup

### 1️⃣ Install Dependencies
```bash
pip install pandas numpy scikit-learn nltk jupyter
python -m nltk.downloader punkt stopwords

# 🎬 Movie Recommendation System

This is a basic content-based movie recommender system built using Python. It suggests similar movies based on metadata like genres, cast, director, keywords, and overview.

## 📊 Dataset
The model is built using the TMDB 5000 Movie Dataset from Kaggle:
- movies_metadata.csv
- credits.csv
- keywords.csv

## 🔧 Features Used
- **Genres**
- **Keywords**
- **Cast**
- **Director**
- **Overview**

These features are combined and processed to create a meaningful representation of each movie.

## 🛠️ Technologies
- Python
- Pandas
- NumPy
- scikit-learn
- NLTK
- Jupyter Notebook

## 🧠 How it Works
1. Preprocess and clean the data
2. Combine relevant textual information into a `tags` column
3. Vectorize using CountVectorizer
4. Calculate cosine similarity between all movie vectors
5. Use a function to recommend top 5 similar movies

## 💡 How to Use
```python
recommend('Avatar')

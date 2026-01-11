# 🎬 Movie Recommendation System using Machine Learning

## 📌 Overview
This project implements a **content-based movie recommendation system** that suggests similar movies based on textual features such as genres and descriptions.

The system uses **Natural Language Processing (NLP)** and **cosine similarity** to recommend movies that are contextually similar to a given input movie.

---

## 🚀 Features
- Content-based filtering approach
- Text feature extraction using TF-IDF
- Similarity calculation using cosine similarity
- Personalized movie recommendations

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, NLTK  
- **ML Concepts:** NLP, Feature Engineering, Similarity Measures  

---


---

## 📊 Dataset
The dataset contains movie-related information such as:
- Movie title
- Genres
- Description / Overview

---

## ⚙️ How It Works
1. Load and preprocess movie data  
2. Combine textual features into a single representation  
3. Convert text into numerical vectors using TF-IDF  
4. Compute similarity using cosine similarity  
5. Recommend top-N similar movies  

---

## ▶️ How to Run the Project
```bash
# Clone the repository
git clone https://github.com/Praveen-kumar1Singh/movie-recommendation-system-ml.git

# Navigate to project directory
cd movie-recommendation-system-ml

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/movie_recommendation_system.ipynb

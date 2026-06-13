# 🎬 Movie Recommendation System

A content-based movie recommendation system that suggests movies similar to a selected movie using machine learning techniques and cosine similarity.

## 🚀 Features

* Recommend movies based on similarity
* Content-based filtering approach
* Fast recommendation generation
* Interactive and user-friendly interface

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit

## 📂 Dataset

The project uses the TMDB Movie Dataset containing information such as:

* Movie titles
* Genres
* Keywords
* Cast
* Crew
* Overview

## ⚙️ How It Works

1. Movie metadata is preprocessed and combined.
2. Text features are converted into vectors.
3. Cosine similarity is calculated between movies.
4. The system recommends the most similar movies based on the selected movie.

## ▶️ Installation

```bash
git clone https://github.com/ishanegi7/movie-recommender-system.git
cd movie-recommender-system
pip install -r requirements.txt
streamlit run app.py
```

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

## 📄 License

This project is licensed under the MIT License.

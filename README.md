# Movie Recommender System

This project is a **content-based movie recommender system** built using Python and Streamlit. It suggests movies similar to the one selected by the user by analyzing metadata such as **genres, keywords, cast, and crew** from the **TMDB 5000 Movies Dataset**.

## Features

* 📌 **Movie Recommendations** – Get top 5 similar movies based on your selection
* 🎭 **Content-Based Filtering** – Uses TF-IDF and cosine similarity for finding similar movies
* 🖼️ **Movie Posters** – Posters fetched dynamically via the TMDB API
* 🖥️ **Interactive UI** – Simple and responsive web interface built with Streamlit
* 💾 **Model Persistence** – Preprocessed data stored as `.pkl` files for fast loading

## Tech Stack

* **Python**
* **Pandas, NumPy** – Data processing
* **Scikit-learn** – Similarity computation
* **Pickle** – Model storage
* **Streamlit** – Web app development
* **TMDB API** – Poster fetching

## 📂 Project Structure

```
├── app.py                 # Streamlit app
├── movies_dict.pkl        # Preprocessed movie data
├── similarity.pkl         # Cosine similarity matrix
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

## ⚡ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   cd movie-recommender-system
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 🎯 Outcome

A lightweight and interactive recommender system that helps users discover movies tailored to their taste.

Would you like me to also create a **short 3–4 line version** (resume/portfolio-friendly) for the repo’s description box (not README), so it looks professional at first glance?

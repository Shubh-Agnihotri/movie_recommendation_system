# 🎬 Movie Recommendation System

This project implements a content-based movie recommendation system using the TMDB 5000 Movies dataset. The system suggests movies similar to a selected movie by analyzing metadata such as genres, keywords, cast, and crew.

## 📌 Features

Preprocessing of movie and credits datasets.

Feature extraction from genres, keywords, cast, and crew.

Text vectorization for building a similarity matrix.

Content-based recommendations using cosine similarity.

Simple interface to query similar movies.

## 📂 Dataset

The project uses the TMDB 5000 Movies dataset, which contains metadata for over 5,000 movies.
It includes information such as:

Movie ID & Title

Overview (plot description)

Genres & Keywords

Cast & Crew

## ⚙️ Technologies Used

Python 3

Pandas – Data manipulation

NumPy – Numerical computations

scikit-learn – Vectorization & similarity calculations

NLTK – Text preprocessing

## 🚀 How It Works

Load and merge movie and credits datasets.

Extract key metadata fields (genres, keywords, cast, crew).

Convert text fields into structured data using ast.literal_eval.

Preprocess and combine features into a "tags" column.

Apply vectorization (CountVectorizer) to convert tags into numerical vectors.

Compute similarity scores using cosine similarity.

Recommend top-N movies similar to the input movie.

# 🎬 Movie Recommendation System

A content-based movie recommendation system using the TMDB 5000 dataset. It suggests movies based on genres, keywords, cast, director, and overview.


## Features

- Content-based filtering using NLP techniques.
- Data preprocessing using pandas.
- Feature extraction using `CountVectorizer`.
- Cosine similarity for recommendations.
- Movie recommender returns top 5 similar titles.


## Dataset

Used datasets from TMDB:
- `tmdb_5000_credits.csv`
- `tmdb_5000_movies.csv`


## Technologies Used

- **Python**
- **pandas** & **numpy** for data manipulation
- **NLTK** for text preprocessing (stemming)
- **scikit-learn** for vectorization and similarity measures
- **pickle** for model/data serialization


## How It Works

1. **Merge Datasets**: Combine movie metadata with credits.
2. **Preprocessing**:
   - Extract and clean genres, keywords, cast, and crew.
   - Tokenize and stem text using NLTK.
   - Create a new 'tags' column combining all important text data.
3. **Vectorization**:
   - Use `CountVectorizer` to convert text to vectors.
   - Use cosine similarity to find similar movies.
4. **Recommendation**:
   - Input a movie title.
   - Get top 5 similar movies based on content.


## I’ve also created a Streamlit web app to demo this project.

### Live Demo

Try the Streamlit web app: [Live App](https://your-streamlit-link)

### GitHub Repo

View the source code on GitHub: [GitHub Repo] (https://github.com/muhammadmateensadiq/Movie-Recommender-Web)

## Author
Created by Muhammad Mateen Sadiq

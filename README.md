# Movie Recommender System

A content-based movie recommendation system built using TF-IDF vectorization and cosine similarity.

## Features
- Recommends movies based on similarity of content
- Uses TF-IDF for text processing
- Uses cosine similarity for ranking
- Handles missing data

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## How It Works
1. Load dataset
2. Clean and preprocess data
3. Apply TF-IDF on movie overview
4. Compute cosine similarity
5. Recommend top similar movies

## Example
Input:
get_recommendations("The Dark Knight Rises")

Output:
Batman Begins  
The Dark Knight  
Man of Steel  

## Author
Aditya Mishra
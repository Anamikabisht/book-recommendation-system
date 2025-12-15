Book Recommendation System

A machine learning–based Book Recommendation System that suggests relevant books to users using collaborative filtering and popularity-based recommendation techniques.
The system analyzes historical user–book interaction data to generate personalized recommendations.

Features

Popularity-based book recommendations

User-based collaborative filtering

Cosine similarity for recommendation scoring

Data preprocessing and filtering to handle sparsity

Serializable models for reuse and deployment

Dataset

Source: Kaggle – Book Recommendation Dataset

Files Used:

Books.csv

Users.csv

Ratings.csv

The dataset contains explicit user ratings (0–10) with high sparsity, simulating real-world recommendation challenges.

Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Scikit-learn

ML Technique: Collaborative Filtering

Similarity Metric: Cosine Similarity

Project Structure
.
├── bookRecommendation.ipynb
├── popular.pkl
├── pt.pkl
├── similarity_scores.pkl
├── books.pkl
└── README.md

Recommendation Approach
Popularity-Based Filtering

Recommends books based on:

Number of ratings

Average rating

Useful for new users (cold start).

Collaborative Filtering

Filters active users and frequently rated books

Creates a user–item interaction matrix

Computes cosine similarity between books

Recommends books similar to the selected item

How to Run

Clone the repository:

git clone https://github.com/your-username/book-recommendation-system.git
cd book-recommendation-system


Install dependencies:

pip install pandas numpy matplotlib scikit-learn


Open the notebook:

jupyter notebook bookRecommendation.ipynb

Results

Generates accurate book recommendations

Handles sparse datasets efficiently

Ready for integration with a web application

Future Enhancements

Content-based recommendation

Hybrid recommendation system

Web application using Flask or Streamlit

Performance optimization for large datasets

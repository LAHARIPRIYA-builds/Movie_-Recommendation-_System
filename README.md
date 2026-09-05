# 🎬 Movie Recommendation System

## 📌 Project Description

The Movie Recommendation System is a simple machine learning project that recommends movies to users based on their interests and movie genres.

This project uses the **MovieLens dataset** and applies **Content-Based Filtering** to find movies that are similar to a movie selected by the user.

The movie genres are converted into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)**. Then, **Cosine Similarity** is used to measure how similar the movies are.

When a user enters a movie name, the system finds similar movies and displays the top recommended movies.

## 🎯 Objectives

- To build a simple movie recommendation system.
- To recommend movies based on their genres.
- To understand Content-Based Filtering.
- To use TF-IDF for feature extraction.
- To use Cosine Similarity to find similar movies.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📊 Dataset

The project uses the **MovieLens Small Dataset**, which contains movie information such as:

- Movie ID
- Movie Title
- Movie Genres
- User Ratings

## ⚙️ How It Works

1. Load the MovieLens dataset.
2. Read the movie information.
3. Process the movie genres.
4. Convert genres into numerical features using TF-IDF.
5. Calculate similarity between movies using Cosine Similarity.
6. Select a movie entered by the user.
7. Find movies with the highest similarity.
8. Display the recommended movies.

## 💡 Example

If the user selects:

**Toy Story (1995)**

The system can recommend other movies with similar genres such as animation, adventure, or children.

## 🚀 Future Improvements

- Add a user rating-based recommendation system.
- Implement Collaborative Filtering.
- Create a web interface for the recommendation system.
- Add movie posters and additional movie information.
- Improve recommendations using user preferences.

## 👩‍💻 Author

**Lahari Priya**

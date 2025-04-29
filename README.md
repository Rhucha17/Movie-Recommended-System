# Movie-Recommended-System
The movie recommendation system helps users discover movies similar to their favorites. By selecting a movie from the list, users receive a list of top 10 recommended movies along with their posters. This project leverages machine learning techniques to analyze the features of movies and find similarities between them. It uses the TMDB API to fetch and display movie posters, enhancing the user experience by providing visual context for the recommendations. The system is built with Streamlit, providing an interactive and user-friendly interface for users to explore movie recommendations easily.

## __What is a Recommendation System?__<br>
A recommendation system is a subclass of information filtering systems that seek to predict the rating or preference a user would give to an item. They are widely used in various applications like movie recommendations, product recommendations, and content recommendations.

## __Types of Recommendation Systems__<br>
1. Content-Based Filtering: This method recommends items similar to those a user liked in the past. It relies on the attributes of the items and a profile of the user's preferences.
2. Collaborative Filtering: This method recommends items based on the preferences of similar users. It doesn't require the attributes of the items and instead focuses on user-item interactions.
3. Hybrid Methods: These methods combine content-based and collaborative filtering to provide more accurate recommendations.
![Image](https://github.com/user-attachments/assets/aa0b3fe2-4bea-4101-b1a2-0461c18258a5)

## __Cosine Similarity__
In this project, we use cosine similarity to measure the similarity between movie titles. Cosine similarity is a metric used to measure how similar two vectors are. It is calculated as the cosine of the angle between two vectors projected in a multi-dimensional space. For movie recommendation, the vectors represent movie features, and the similarity score indicates how alike two movies are.

## __Dataset__<br>
The dataset used for this project contains information about movies, including their titles and IDs. It is processed and stored in movie_data.pkl. The dataset is used to calculate the cosine similarity between movies.

## __Model__<br>
The model for recommending movies is based on cosine similarity. Cosine similarity is used to measure the similarity between movie titles. The model computes the similarity scores and suggests the top 10 similar movies based on the selected movie title.

## __Results__<br>
The system provides the top 10 recommended movies for any selected movie title. It also fetches and displays the posters of these recommended movies using the TMDB API.
<p align="center">
  <img src="https://github.com/user-attachments/assets/872597bb-7edf-49ae-9192-cd9cc65eabab" alt="Image" width="400"/>
</p>


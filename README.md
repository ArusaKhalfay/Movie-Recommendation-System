# Movie Recommendation System

A movie recommendation system built using Streamlit and a machine learning model that suggests movies based on a selected movie title. The system uses cosine similarity to find similar movies and fetches movie posters from the TMDB API, enhancing the user experience with visual context.

---

## Overview

This project allows users to discover movies that are similar to their favorites. By selecting a movie title from a list, users will receive the top 10 recommended movies based on cosine similarity, along with the movie posters fetched from the TMDB API. The user-friendly interface is built using Streamlit, making the interaction smooth and easy.

---

## Recommendation System Theory

### What is a Recommendation System?

A recommendation system predicts a user's preference for items, helping them discover content they might like. These systems are commonly used in platforms such as Netflix, YouTube, and e-commerce sites.

### Types of Recommendation Systems

- **Content-Based Filtering**: Recommends items similar to those a user has liked in the past, based on item attributes and user preferences.
- **Collaborative Filtering**: Recommends items by analyzing the preferences of users with similar tastes, without needing item attributes.
- **Hybrid Methods**: Combines content-based and collaborative filtering to provide more accurate and personalized recommendations.

### Cosine Similarity

This project uses **cosine similarity** to measure how similar two movies are based on their features. Cosine similarity calculates the cosine of the angle between two vectors in a multi-dimensional space, where each vector represents movie features. The closer the cosine similarity score is to 1, the more similar the two movies are.

---

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Select a movie from the dropdown list and click "Recommend" to get the top 10 recommended movies along with their posters.


## Results

The system provides the top 10 recommended movies for any selected movie title. It also fetches and displays the posters of these recommended movies using the TMDB API.

![image](https://github.com/user-attachments/assets/8045e432-b46a-4faa-91f6-f0430b80f97d)

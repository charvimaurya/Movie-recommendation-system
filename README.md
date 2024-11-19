# Movie Recommendation System

## Overview

This project is a **Movie Recommendation System** built using **Streamlit** and **Python**. The system uses a collaborative filtering approach to recommend movies based on the input movie title. It leverages a pre-trained similarity model (`similarity.pkl`) that calculates movie similarities to provide personalized recommendations. The app is deployed on **Streamlit** for easy access through a web interface.

The model is trained using a dataset of 5000 movies from **The Movie Database (TMDb)**, which includes movie titles, genres, and other metadata. 

You can interact with the live version of the system here: [Movie Recommendation System - Streamlit App](https://movie-recommendation-system-h3g77ainsgbabrawzp2x52.streamlit.app/).

---

## Features

- **Movie Recommendations**: Provides movie suggestions based on the similarity to the movie entered.
- **Collaborative Filtering**: Uses collaborative filtering and similarity models to recommend movies.
- **Web Interface**: Built with **Streamlit**, allowing easy user interaction with the system.
- **Pre-trained Model**: Utilizes a pre-trained similarity model (`similarity.pkl`) to enhance performance.

---

## Technologies Used

- **Python 3.x**: Programming language for building the recommendation logic.
- **Streamlit**: For creating the interactive web application.
- **Pandas**: For data processing and manipulation.
- **Scikit-learn**: For implementing the recommendation system's algorithm.
- **Git LFS (Large File Storage)**: For managing the large model file (`similarity.pkl`).

---

## Dataset

The system is trained on the **TMDb 5000 Movies Dataset**, which includes information on 5000 movies, such as:
- Movie titles
- Genres
- Popularity
- Release dates
- Descriptions

Dataset Source: [TMDb 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## How to Run Locally

### Step 1: Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/charvimaurya/Movie-recommendation-system.git


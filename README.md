# 🎧 Music Recommendation System

A simple yet powerful music recommendation system that suggests songs based on user input such as **mood, genre**, or **favorite song**. It uses **cosine similarity** on audio features or metadata to find the most similar tracks from a dataset.

---

## 🚀 Features

- 🎵 Recommends songs based on mood, genre, or reference track
- 📊 Uses **cosine similarity** for measuring song-to-song relevance
- 🧠 Built using **Python**, **Pandas**, and **Scikit-learn**
- 🖥️ Streamlit interface for interactive song suggestions

---

## 🧠 How It Works

1. **Data Processing**:
   - The dataset contains songs with attributes like genre, mood, artist, and audio features (tempo, energy, danceability, etc.).

2. **Vectorization**:
   - Each song is converted into a numerical vector based on its features.

3. **Similarity Calculation**:
   - When a user enters a mood or reference song, the system:
     - Finds the vector of the input.
     - Calculates **cosine similarity** between the input vector and all others.
     - Sorts and recommends the top N most similar songs.

4. **Cosine Similarity Formula**:
   \[
   \text{cosine\_similarity}(A, B) = \frac{A \cdot B}{\|A\|\|B\|}
   \]
   Where `A` and `B` are song feature vectors.

   Output

   output/


![Screenshot (61)](https://github.com/user-attachments/assets/da34e091-1c21-4421-8c69-5bf7c2f86908)



![Screenshot (62)](https://github.com/user-attachments/assets/fb334c7c-723b-444c-bb95-421d342ee107)




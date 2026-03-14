# KNN-Music-Recommender

# 🎵 Music Recommendation System using KNN

A **content-based music recommendation system** built using **Machine Learning (K-Nearest Neighbors)** that recommends songs based on their audio features such as energy, danceability, tempo, valence, and popularity.

The system analyzes musical characteristics of songs and finds **similar tracks using feature similarity**, allowing users to discover music with comparable styles and moods.

---

## 📌 Project Overview

Music streaming platforms recommend songs based on listening behavior and song similarity. This project demonstrates how a **content-based recommendation system** can be built using **audio features extracted from songs**.

Using **KNN (Nearest Neighbors)**, the model identifies songs that are closest in feature space to a selected song and recommends them.

---

## 📊 Dataset

The dataset used in this project contains **Spotify song audio features**.

### Features

| Feature | Description |
|---------|-------------|
| acousticness | Confidence measure of whether the track is acoustic |
| danceability | How suitable the track is for dancing |
| energy | Intensity and activity of a song |
| instrumentalness | Predicts whether a track contains vocals |
| liveness | Presence of audience in recording |
| loudness | Overall loudness of a track |
| speechiness | Presence of spoken words |
| tempo | Speed of the track |
| valence | Musical positivity of a song |
| duration_ms | Duration of the track |
| popularity | Popularity score of the track |

The dataset contains **over 170,000 songs**.

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand the distribution and relationships between different audio features.

Key visualizations included:

- Song duration distribution
- Popularity distribution
- Feature correlation heatmap
- Energy vs Danceability analysis
- Outlier detection using boxplots

These analyses helped identify **patterns in musical characteristics** and prepare the dataset for modeling.

---

## ⚙️ Model

The recommendation system uses **K-Nearest Neighbors (KNN)**.

### Steps Involved

1. Data preprocessing
2. Feature selection
3. Feature scaling using **StandardScaler**
4. Training a **Nearest Neighbors model**
5. Computing similarity between songs

The model recommends songs based on **cosine similarity between audio feature vectors**.

---

## 🎯 Recommendation Process

1. A song is selected from the dataset
2. The audio feature vector of that song is extracted
3. The KNN model finds the **closest songs in feature space**
4. The system returns **top similar songs** as recommendations

---

## 📁 Project Structure
```
Music-Recommendation-System-KNN/
│
├── data/
│   └── data.csv
│
├── notebooks/
│   ├── eda.ipynb
│   └── model.ipynb
│
├── models/
│   └── knn_model.pkl
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Music-Recommendation-System-KNN.git
```

### 2️⃣ Navigate to the Project Folder
```bash
cd Music-Recommendation-System-KNN
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebooks

Open Jupyter Notebook and run:

- `eda.ipynb`
- `model.ipynb`

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Results

The model successfully identifies songs with similar musical characteristics and generates recommendations based on audio feature similarity.

This demonstrates how machine learning can power recommendation systems similar to those used in music streaming platforms.

---

## 🔮 Future Improvements

Possible improvements include:

- Incorporating genre and artist similarity
- Applying dimensionality reduction (PCA)
- Using deep learning-based recommendation models
- Building a web application interface

---

## 👨‍💻 Author

**Amulya Gavankar**

Machine Learning | Data Science | AI Projects
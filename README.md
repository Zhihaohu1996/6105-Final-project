# 6105-Final-project
# 🎵 Spotify Hit Prediction — Data Science Final Project

This project predicts whether a song is a **Hit (1)** or **Not Hit (0)** using Spotify song features.  
The dataset comes from the *Spotify Tracks 2023* CSV file, and the project follows the three-phase structure required for the course:

1. **EXTRACT** — Data cleaning, feature selection, and visualization  
2. **LEARN** — Model training and evaluation (Decision Tree & Random Forest)  
3. **PREDICT** — Use the best model to generate predictions

---

## 📁 Project Structure


---

## 📊 1. Problem Statement

The goal of this project is to classify songs as:

- **Hit (1)** — High-performing songs  
- **Not Hit (0)** — Other songs

Because the dataset does not include a direct popularity score, we define **Hit = songs with streams in the top 25% (≥ Q3)**.

This makes the problem a **binary classification task**.

---

## 📂 2. Dataset Description

Dataset: **spotify-2023.csv**

Key fields used:
- `streams`
- `bpm`
- `danceability_%`
- `energy_%`
- `valence_%`
- `acousticness_%`
- `instrumentalness_%`
- `liveness_%`
- `speechiness_%`

Target variable created:  hit = 1 if streams >= 75th percentile
hit = 0 otherwise


---

## 🛠 3. Environment Setup

### Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn joblib
pip install jupyter
git clone <your-repo-url>
cd <your-repo>
jupyter notebook
Notebooks/spotify_simple_project_updated.ipynb




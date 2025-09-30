
# 🎵 Creating Cohorts of Songs  

## 📌 Overview  
This project explores Spotify track data to **analyze song features** and **cluster similar songs** for better recommendations. Using **EDA** and **K-Means clustering**, songs are grouped into cohorts based on attributes like *acousticness* and *danceability*.  

## 🔑 Dataset  
- 1,610 songs (Rolling Stones collection)  
- Features: acousticness, danceability, energy, valence, tempo, loudness, popularity, etc.  

## 🛠️ Tools & Libraries  
- Python (pandas, numpy, matplotlib, seaborn)  
- Scikit-learn (KMeans, StandardScaler, PCA)  

## 📊 Key Steps  
1. **EDA**: Analyzed popularity, trends, correlations.  
2. **Top Albums**: *Sticky Fingers (Remastered)*, *Some Girls*.  
3. **Clustering**: Optimal clusters = 2 (via Elbow Method).  

## 🚀 How to Run  
```bash
git clone https://github.com/YourUsername/creating-cohort-of-songs.git
cd creating-cohort-of-songs
pip install -r requirements.txt
jupyter notebook notebooks/cohorts_of_songs.ipynb

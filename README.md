# Spotify Mood Personality Analyzer (MPA) 🎧

This project clusters Spotify tracks using audio features and builds a Mood + Personality Analyzer system.  
It also includes a recommendation engine that suggests similar songs based on cosine similarity.

---

## 📌 Project Features
- KMeans clustering of Spotify songs based on audio features
- PCA 2D visualization of clusters
- Mood naming system for clusters (Party Beast, Acoustic Chill, etc.)
- Personality analyzer based on mood distribution
- Recommendation system:
  - Song-to-song similarity recommendation
  - Mood-based recommendations

---

## 🛠 Tools & Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebooks
- Git + GitHub

---

## 📂 Dataset
Spotify Tracks Dataset containing:
- track name
- artists
- popularity
- audio features (danceability, energy, tempo, etc.)

---

## 🔍 Workflow
### 1. Data Cleaning
- Removed missing values
- Selected useful numeric features

### 2. Feature Scaling
- Used StandardScaler to normalize features

### 3. Clustering (KMeans)
- Tested k = 3 to 8
- Used Elbow Method + Silhouette Score
- Final clusters assigned to each song

### 4. PCA Visualization
- Reduced features into 2 components (PC1, PC2)
- Plotted clusters in 2D

### 5. Mood Naming + Personality Analyzer
- Assigned mood names to each cluster
- Calculated mood distribution of playlist
- Generated personality statement

### 6. Recommendation Engine
- Song similarity recommendations using cosine similarity
- Mood-based recommendations

---

## 📊 Results
- Songs were grouped into meaningful mood-based clusters.
- Each cluster was interpreted using average audio features.
- Recommendation engine successfully suggests similar songs.

---

## 📸 Visual Examples
- Cluster Distribution Bar Chart
- PCA Cluster Plot
- Feature Heatmap (Cluster vs Audio Features)


---

## 🚀 How to Run
### 1. Clone the repository

git clone https://github.com/AditiMahajan2/Spotify-MPA
cd Spotify-MPA


### 2. Create Virtual Environment
python -m venv .venv

### 3. Activate Virtual Environment

# Windows (PowerShell):

.\.venv\Scripts\activate

### 4. Install Dependencies
pip install -r requirements.txt

### 5. Run Jupyter Notebooks

Open VS Code / Jupyter Notebook and run the notebooks in order:

01_Data_Cleaning.ipynb
02_EDA_Clustering.ipynb
04_PCA_Clustering_Visualization.ipynb
05_Recommendation_System.ipynb
06_Final_Visuals_and_Summary.ipynb

```bash



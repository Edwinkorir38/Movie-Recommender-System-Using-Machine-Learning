# 🎬 Movie Recommender System Using Machine Learning

![Banner](demo/6.jpeg)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Cosine%20Similarity-green" />
  <img src="https://img.shields.io/badge/Framework-Streamlit-ff4b4b?logo=streamlit" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

---

## 🌟 Overview

In a world overloaded with content, recommendation systems help users quickly find what they love.  
This project uses **content-based filtering** powered by **cosine similarity** to recommend the most similar movies based on metadata.

Built with:
- 💻 Python  
- 🎯 Machine Learning  
- 🌐 Streamlit  
- 📊 TMDB dataset  

---

## 🏗️ Project Architecture (Visual)

Movie Chosen → Text Vectorization → Cosine Similarity Search → Top 5 Similar Movies
---

## 🎥 Live Demo 


👉 https://your-deployed-app-link

---

## 📸 Demo Screenshots

| UI Preview | Recommendations |
|-----------|----------------|
| ![](demo/1.png) | ![](demo/2.png) |

![](demo/3.png)

---

## 🧠 Types of Recommendation Systems

### **1️⃣ Content-Based Filtering**
- Uses item attributes (genre, cast, keywords)
- Personalized to individual users  
- Used in: **YouTube**, **Spotify**, **Twitter**

### **2️⃣ Collaborative Filtering**
- “People similar to you liked…”  
- Based on user–item interactions  
- Prone to the cold-start problem  

### **3️⃣ Hybrid Systems**
- Best of both worlds  
- Used in: **Netflix**, **Amazon**, **TikTok**

---

## 📂 Dataset Used

**TMDB 5000 Movies Dataset**  
🔗 https://www.kaggle.com/tmdb/tmdb-movie-metadata

Includes:
- Genres
- Overview text
- Cast & crew
- Keywords
- Popularity, rating, etc.

---

## 🧮 ML Core: Cosine Similarity

Cosine similarity outputs **how close two movies are**, based on vectorized metadata.

- **1.0** → identical  
- **0.7** → highly similar  
- **0.0** → not similar  

Useful reference:  
https://www.learndatasci.com/glossary/cosine-similarity/

---

## 🧱 Project Structure

```yaml
Movie-Recommender-System-Using-Machine-Learning/
│── app.py                     # Streamlit UI
│── model.pkl                  # Cosine similarity matrix
│── movies.pkl                 # Cleaned movie metadata
│── requirements.txt
│── demo/
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   └── 6.jpeg
│── Movie Recommender System Data Analysis.ipynb
└── README.md
```

# ⚙️ Installation Guide

## 1️⃣ Clone Repository

```
bash
git clone https://github.com/Edwinkorir38/Movie-Recommender-System-Using-Machine-Learning.git
```

## 2️⃣ Create a Conda Environment
```
bash
conda create -n movie python=3.10 -y
conda activate movie
```

## 3️⃣ Install Dependencies
```
bash
pip install -r requirements.txt
```

## 4️⃣  Recreate ML Model

**Run the notebook:**
```
bash
Movie Recommender System Data Analysis.ipynb
```
## 5️⃣ Run the Web App
```
bash
streamlit run app.py
```

🧑‍💻 Author

Edwin Korir

Data Scientist

📧 Email: ekorir99@gmail.com

🐙 GitHub: https://github.com/Edwinkorir38
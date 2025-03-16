# 🎥 Movie Recommendation System: Smart Suggestions with TF-IDF & Collaborative Filtering  

This project builds an **interactive and intelligent Movie Recommendation System** that suggests films based on **user preferences** and **movie similarities**. The system uses **TF-IDF vectorization** to analyze movie titles, **cosine similarity** for relevance matching, and **collaborative filtering** to recommend movies based on user ratings.  

⭐ As the user types a movie title, recommendations update dynamically in real time!  

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/IPython%20Widgets-FFD43B?style=for-the-badge&logo=python&logoColor=white" alt="IPython Widgets"/>
</p>

---

## 🚀 Project Features

### ✅ **1. Data Preprocessing**
✔ Cleans movie titles by removing special characters.  
✔ Vectorizes movie titles using **TF-IDF (Term Frequency-Inverse Document Frequency)** to create a feature matrix.  
✔ Computes **cosine similarity** to measure how closely movies are related.  

### 🎯 **2. Interactive Movie Search**
✔ Uses **IPython widgets** to create a dynamic search bar.  
✔ As the user types, the system finds **the most relevant movies** using **TF-IDF similarity**.  

### 🔎 **3. Finding Similar Movies Based on User Ratings**
✔ Identifies **users who highly rated a given movie**.  
✔ Finds **other movies these users also rated highly** (*collaborative filtering*).  
✔ Computes **recommendation scores** based on how frequently similar users liked each movie.  

### 🎬 **4. Personalized Movie Recommendations**
✔ Calculates the **popularity of recommended movies** among both similar users and all users.  
✔ Ranks movies by their **relevance** using a custom scoring formula.  
✔ Suggests **top 10 movies similar** to the one selected.  

### 💡 **5. Fully Interactive UI for Real-Time Recommendations**
✔ Uses **IPython widgets** for **instant movie recommendations**.  
✔ Displays the **top similar movies dynamically**—no manual execution required!  

---

## 🛠️ Technologies & Tools

| Category          | Tools & Libraries |
|------------------|------------------|
| **Programming Language** | Python |
| **Data Manipulation** | `pandas`, `numpy` |
| **Machine Learning** | `scikit-learn` (TF-IDF, Cosine Similarity) |
| **Interactive UI** | `ipywidgets` |

---

## 🎬 **How It Works**
1. **User types a movie title** ➝ The system finds similar movies based on **TF-IDF vectorization**.  
2. **The system retrieves users who liked the movie** ➝ It checks other movies they rated highly.  
3. **The recommendation score is computed** ➝ Top 10 most relevant movies are suggested.  
4. **Movies dynamically update in real-time** as the user continues typing.  

---

🔹 **Want to test it out?** Clone the repository, install dependencies, and run the Jupyter Notebook! 🚀  

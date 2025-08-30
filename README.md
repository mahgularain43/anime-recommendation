# 🎬 Anime Recommendation System  

This project is a **Machine Learning-based Anime Recommendation System** that helps users discover similar anime titles based on their viewing patterns and ratings. It combines **dimensionality reduction, clustering, and KNN-based collaborative filtering** to provide recommendations.  

---

## 🚀 Features
- **Data Preprocessing**: Cleaning and preparing anime datasets.  
- **Dimensionality Reduction**: Applied **PCA** for better clustering and visualization.  
- **Clustering**: Used **KMeans** with Silhouette Score & Inertia analysis.  
- **Cluster Insights**: Top anime, genres, ratings, members, and episodes per cluster.  
- **Visualizations**:  
  - Genre distributions  
  - Wordclouds for genres  
  - Category-wise anime breakdown (TV, OVA, Movie, etc.)  
- **Recommendation Engine**:  
  - Built with **KNN (cosine similarity)**  
  - Suggests similar anime titles based on user preferences  

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy** – data handling  
- **Matplotlib, WordCloud** – visualizations  
- **scikit-learn** – PCA, KMeans, KNN  

---

## 📂 Project Structure
├── anime_recommendation.ipynb # Main notebook with analysis & model
├── data/ # Anime dataset (CSV files)
├── README.md # Project documentation

yaml
Copy code

---

## 📊 How It Works
1. Load and preprocess the anime dataset.  
2. Apply **PCA** to reduce dimensions.  
3. Perform **KMeans clustering** to explore anime groups.  
4. Visualize clusters & genre trends.  
5. Build **KNN recommendation system** using cosine similarity.  
6. Input an anime title → get similar anime suggestions.  

---

## 🎯 Example Recommendation
```text
We will find recommendations for: Naruto

1: Naruto: Shippuuden (distance: 0.1521)  
2: Bleach (distance: 0.1783)  
3: One Piece (distance: 0.1832)  
4: Fairy Tail (distance: 0.1945)  
5: Dragon Ball Z (distance: 0.2012)

## 📌 Future Improvements
Deploy with Streamlit for an interactive UI

Integrate content-based filtering (synopsis, genres, tags)

Add hybrid recommendation system combining collaborative + content-based

## 🤝 Contributing
Pull requests are welcome! If you have ideas for improvements, feel free to open an issue.

## 📜 License
This project is licensed under the MIT License.

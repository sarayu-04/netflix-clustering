# Netflix Clustering

This project applies unsupervised machine learning algorithms to group Netflix titles based on their attributes.  
Explored how clustering algorithms like KMeans and DBSCAN reveal hidden patterns in the dataset.  
And then, dimensionality reduction techniques like PCA and t-SNE are used for visualization.

---

## Dataset
- Source: [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- File: dataset/netflix_titles_set.csv

---

## Tech Stack
- python, pandas, scikit-learn, matplotlib   
- Algorithms: KMeans, DBSCAN  
- Visualization: PCA, t-SNE  
- Jupyter Notebook

---

## Project Flow
1. Data preprocessing  
2. Feature extraction (genre, director, etc.)  
3. Clustering using KMeans & DBSCAN  
4. Dimensionality reduction (PCA, t-SNE)  
5. Visualization of clusters  

---

## Results
- Both KMeans and DBSCAN successfully identified clusters of Netflix content.  
- KMeans required a predefined number of clusters, while DBSCAN automatically detected clusters based on density.  
- t-SNE allowed to visualize the high-dimensional data in 2D, making the clusters more interpretable.
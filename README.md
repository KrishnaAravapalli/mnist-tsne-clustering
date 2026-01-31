# MNIST Digit Clustering with t-SNE Visualization

## Project Overview
This project implements a system to visualize clustering of handwritten digit images from the MNIST dataset.  
It uses **t-SNE** for dimensionality reduction and **K-Means clustering** to group visually similar digits in a **2D space**, implemented using a **Jupyter Notebook**.

---

## Dataset
The project uses the MNIST digits dataset from `sklearn.datasets.load_digits()`.

- **Total samples:** 1,797  
- **Image size:** 8×8 grayscale  
- **Digit classes:** 0–9  

Digit labels are used **only for evaluation**, not during clustering.

---

## Methodology
- Loaded handwritten digit images and labels  
- Reduced high-dimensional pixel data into **2D using t-SNE**  
- Applied **K-Means clustering** on the t-SNE embeddings  
- Visualized clusters using 2D scatter plots  
- Evaluated clustering quality using:
  - Silhouette Score  
  - Cluster purity (majority voting)  
- Selected optimal number of clusters using:
  - Elbow Method  
  - Silhouette Analysis  

---

## Features & Analysis
- 2D visualization of digit clusters  
- Color-coded cluster representation  
- Hover-based inspection of digit labels (Plotly)  
- Experimentation with number of clusters (**k = 3 to 15**)  
- Elbow and silhouette-based cluster evaluation  

---

## Technologies Used
- Python  
- NumPy  
- scikit-learn  
- Matplotlib  
- Plotly  
- Jupyter Notebook  

---
## Installation and Running the Notebook


# Step 1: Clone the repository
git clone https://github.com/KrishnaAravapalli/mnist-tsne-clustering.git

# Step 2: Install dependencies
pip install numpy scikit-learn matplotlib plotly

# Step 3: Run the notebook
# Open the following notebook and run all cells sequentially:
mnist_tsne_kmeans_clustering.ipynb

## 📸 Screenshots

### t-SNE Cluster Visualization
![t-SNE Clusters](images/1_tsne_clusters.png)

### Elbow Method for Optimal K
![Elbow Plot](images/2_elbow_plot.png)

### Silhouette Score vs K
![Silhouette Plot](images/3_silhouette_plot.png)

## Author
Krishna Aravapalli  
AI / Backend Internship Assignment – Sparkable Digital Solutions
```bash

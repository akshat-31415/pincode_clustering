# 📍 Maharashtra Pincode Clustering with K-Means (from Scratch)
Made by Akshat Banzal(CS24BTECH11005)

This project applies **K-Means clustering from scratch** to analyze the spatial distribution of **pincodes in Maharashtra, India**. The goal is to identify geographic patterns, urban-rural clusters, and draw insights about regional development using geospatial data and clustering techniques — **without using `sklearn`** for the core algorithm.

---

## 📦 Dataset

- **Source:** `clustering_data.csv`
- **Contents:** Indian pincodes along with their **latitude**, **longitude**, and **state**.
- **Filtering:** Only entries belonging to **Maharashtra** are used in the clustering.


- **Steps:**
  1. Download the files from this repo.
  2. Place it in the root directory of this project.

---

---

## 🚀 Features

- ✅ Custom implementation of **K-Means** clustering (with **K-Means++** initialization)
- ✅ **GeoPandas** and **Matplotlib** used for mapping and plotting
- ✅ Interactive **state boundary map** overlay
- ✅ Clustering evaluation using the **Elbow Method**
- ✅ Visualization of **clusters**, **centroids**, and optionally:
  - **Road networks**
  - **Rivers**
  - **Elevation data**

---

## 📊 Insights

- Clusters with fewer pincodes correspond to **Marathwada**, a drought-prone region.
- Dense clusters' centroids align with **major urban cities** such as Pune, Nagpur, Latur, and Satara.
- Helps visualize **population distribution** and could aid in planning infrastructure, delivery routes, or development programs.

---

## 🧪 How to Run

1. Clone the repo or run in **Google Colab**.
2. Make sure the following libraries are installed:
   ```bash
   pip install pandas geopandas matplotlib osmnx shapely
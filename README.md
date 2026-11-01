# Vancouver Spatial Analysis & Clustering Dashboard

An interactive data analytics web application built with Python, Streamlit, and Plotly to analyze and cluster commercial business density across Vancouver using unsupervised machine learning.

**Data Source:** City of Vancouver Open Data Portal — Business Licences https://opendata.vancouver.ca/explore/dataset/business-licences/

## Project Overview
Developed as an advanced data science and spatial analysis pipeline, this project processes large-scale urban open data to uncover patterns in commercial distribution. It benchmarks unsupervised machine learning algorithms (K-Means and DBSCAN) against high-dimensional spatial datasets to evaluate business density and geographic clustering.

## Tech Stack & Libraries
- **Core Language:** Python
- **Data Manipulation & Processing:** Pandas, NumPy
- **Machine Learning (Scikit-Learn):** K-Means, DBSCAN, Principal Component Analysis (PCA), StandardScaler
- **Visualization & Web App:** Plotly, Streamlit

## Key Features & Engineering
- **Automated Data Pipelines:** Engineered data cleaning scripts and feature-scaling pipelines using Pandas to ingest, clean, and format raw business license records and GeoJSON spatial datasets from the City of Vancouver Open Data Portal.
- **Unsupervised Clustering:** Benchmarked distance-based spatial clustering (DBSCAN) against centroid-based clustering (K-Means), utilizing PCA for dimensionality reduction and 2D variance visualization.
- **Interactive Streamlit App:** Built a live dashboard allowing users to dynamically tune algorithm hyperparameters (such as cluster counts and epsilon thresholds) and inspect spatial data anomalies in real time.

## Local Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/cda79/vancouver-spatial-clustering-dashboard.git](https://github.com/cda79/vancouver-spatial-clustering-dashboard.git)
   cd vancouver-spatial-clustering-dashboard

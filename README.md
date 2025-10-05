# 🌍 Country Clustering Analysis

This project applies **unsupervised learning** techniques to analyze countries based on socio-economic indicators.  
It compares multiple clustering algorithms — both with and without **Principal Component Analysis (PCA)** — and visualizes the results in 2D PCA space as well as on an interactive **choropleth world map**.

---

## 🧠 Models Used

- **KMeans**
- **Agglomerative Clustering**
- **Spectral Clustering**
- **Gaussian Mixture Model**
- **DBSCAN**

Each model is evaluated using the **Silhouette Score** to measure clustering quality.

---

## 📊 Visualizations

- PCA-based 2D scatter plots showing different clustering results.
- A Plotly choropleth map showing “Budget Needed”, “In Between”, and “No Budget Needed” countries based on final clustering.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|----------|
| **Python** | Core programming language |
| **Pandas / NumPy** | Data manipulation |
| **Scikit-learn** | Clustering & PCA |
| **Matplotlib / Plotly Express** | Visualization |
| **Jupyter Notebook** | Interactive environment |

---

## 📂 Files

| File | Description |
|------|--------------|
| `country_unsupervised.ipynb` | Main notebook with clustering, PCA, and visualizations |
| `country_data.csv` | Input dataset containing country features |
| `README.md` | Project documentation |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/country-clustering-analysis.git
   cd country-clustering-analysis

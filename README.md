# 🚀 SpaceX Launch Success Prediction — Data Science Capstone

A full end-to-end data science project that predicts whether a SpaceX Falcon 9 first-stage booster will successfully land, enabling cost estimation for rocket launches.

---

## 📌 Project Overview

SpaceX advertises Falcon 9 launches at around $62 million, far cheaper than competitors, largely because it reuses the first-stage booster. Predicting whether that booster will land successfully is key to estimating launch costs. This project applies a complete data science pipeline — from data collection to machine learning — to solve that prediction problem.

---

## 📁 Repository Structure

| Notebook | Description |
|---|---|
| `jupyter-labs-spacex-data-collection-api.ipynb` | Collecting SpaceX launch data via REST API |
| `jupyter-labs-webscraping.ipynb` | Web scraping additional launch records from Wikipedia |
| `labs-jupyter-spacex-Data wrangling (1).ipynb` | Cleaning and preparing the dataset |
| `jupyter-labs-eda-sql-coursera_sqllite (1).ipynb` | Exploratory Data Analysis using SQL |
| `edadataviz (1).ipynb` | EDA with data visualizations (Matplotlib / Seaborn) |
| `lab_jupyter_launch_site_location.ipynb` | Interactive launch site mapping with Folium |
| `SpaceX_Machine Learning Prediction_Part_5.ipynb` | ML models: Logistic Regression, SVM, Decision Tree, KNN |

---

## 🔄 Project Pipeline
```
Data Collection (API + Web Scraping)
        ↓
   Data Wrangling
        ↓
Exploratory Data Analysis (SQL + Visualizations)
        ↓
  Launch Site Analysis (Folium Maps)
        ↓
  Machine Learning Prediction
```

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **SQL** (SQLite via Jupyter)
- **Folium** — interactive maps
- **BeautifulSoup** — web scraping
- **Jupyter Notebook**

---

## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

Models were optimized using `GridSearchCV` and compared on test accuracy.

---

## 🚀 Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/Mohammad-Alajmi/Data-science-capestone.git
   cd Data-science-capestone
```

2. Install dependencies:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn folium beautifulsoup4 requests
```

3. Run the notebooks in order (01 → 07) using Jupyter:
```bash
   jupyter notebook
```

---

## 👤 Author

**Mohammad Alajmi**  
[GitHub Profile](https://github.com/Mohammad-Alajmi)

---

## 📄 License

This project was completed as part of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) on Coursera.

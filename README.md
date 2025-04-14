# 🗽 NYC Taxi Data Analysis

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on NYC taxi data.  
It covers:

- 📁 Data preparation and cleaning
- 📊 Exploratory data analysis (general and detailed)
- 🧠 Insights and recommendations to optimize NYC taxi operations

---

## 🚀 Open in Google Colab

You can run this notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/yourrepo/blob/main/NYC_Taxi_EDA_Analysis.ipynb)

> ⚠️ Replace `yourusername` and `yourrepo` with your actual GitHub username and repository name.

---

## 📂 Files Included

- `NYC_Taxi_EDA_Analysis.ipynb`: The main Jupyter notebook with full analysis
- `README.md`: Project overview and usage instructions

---

## 📌 Project Highlights

- Analyses hourly pickup trends, tip percentages, route speeds, and fare variations
- Generates actionable insights on demand hotspots, slow routes, and pricing strategies
- Recommends optimizations for routing, cab distribution, and fare structuring

---

## 📈 Sample Visuals

```python
# Example: Taxi pickups by hour
sns.countplot(x='hour', data=combined_df)
plt.title('Taxi Pickups by Hour')
plt.show()

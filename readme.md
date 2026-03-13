# Developer Insights Analysis

Exploratory data analysis of a global developer survey — uncovering trends in job satisfaction, remote work, programming language adoption, and compensation using Python.

---

## 📌 Overview

This project analyses survey responses from thousands of developers worldwide to extract meaningful patterns about the tech workforce. The goal is to answer real questions that developers, hiring managers, and researchers actually care about — using clean, reproducible Python analysis.

**Key questions explored:**
- Does more experience lead to higher job satisfaction?
- Which job roles are most associated with remote work?
- What are the most popular programming languages by region?
- How does education level relate to employment type?
- Who are the highest earners, and what do they have in common?

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)

---

## 📊 Analyses Performed

| # | Analysis | Method |
|---|---|---|
| 1 | Experience vs Job Satisfaction | Scatter plot, correlation |
| 2 | Job Satisfaction Distribution | Count plot |
| 3 | Remote Work Trends by Job Role | Grouped bar chart |
| 4 | Programming Language Popularity by Region | Frequency analysis |
| 5 | Education Level vs Employment Type | Cross-tabulation |
| 6 | Industry Distribution of Respondents | Bar chart |
| 7 | High Compensation Identification | Percentile filtering |
| 8 | Compensation Correlation (outlier-cleaned) | Correlation heatmap |

---

## 📁 Project Structure

```
Developer-Insights-Analysis/
├── analysis.ipynb        # Main Jupyter Notebook
├── data/
│   └── survey_results.csv
├── outputs/
│   └── *.png             # Generated charts
└── README.md
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/zakaria17amir/Developer-Insights-Analysis.git
cd Developer-Insights-Analysis

# Install dependencies
pip install pandas matplotlib seaborn jupyter

# Launch notebook
jupyter notebook analysis.ipynb
```

---

## 🔮 Future Work

- Segment analysis by company size and job seniority
- Build a predictive model for job satisfaction using scikit-learn
- Expand salary analysis with cost-of-living adjustments by country

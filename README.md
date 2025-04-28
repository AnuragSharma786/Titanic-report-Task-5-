# 🚢 Titanic EDA Project

## Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset** using **Python**, **Pandas**, **Matplotlib**, and **Seaborn** inside a **Jupyter Notebook** environment.

The goal is to uncover patterns, highlight important features, and visualize relationships that influenced survival rates during the Titanic disaster.

---

## 📚 Technologies Used
- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** — Data loading, cleaning, and manipulation
- **Matplotlib** — Data visualization
- **Seaborn** — Advanced statistical data visualization

---

## 📈 EDA Highlights
- **Data Cleaning:** Handled missing values and basic preprocessing.
- **Univariate Analysis:** 
  - Survival counts
  - Age distribution
  - Fare distribution
- **Bivariate Analysis:** 
  - Survival rate by gender
  - Class vs Survival correlation
  - Fare vs Survival trends
- **Multivariate Analysis:** 
  - Pair plots
  - Correlation heatmaps
- **Visualizations:** 
  - Bar plots
  - Histograms
  - Pie charts
  - Pair plots
  - Heatmaps

---

## 📊 Key Insights
- Females had a much higher survival rate than males.
- Higher ticket classes (1st class) had a greater chance of survival.
- Younger passengers, especially children, had better survival rates.
- Most passengers paid relatively low fares.
- Strong correlation between fare, class, and survival.

---


## 📁 Project Structure
```
├── data/
│   └── titanic.csv           # Titanic dataset
├── notebooks/
│   └── Titanic_EDA.ipynb      # Main Jupyter Notebook
├── README.md                  # Project README
└── requirements.txt           # Python dependencies
```

## 🎯 Future Improvements
- Feature engineering for Machine Learning models
- Build predictive models (Logistic Regression, Random Forest, etc.)
- Handle missing data with more advanced techniques (like imputation)
- Deploy an interactive dashboard using Plotly/Dash or Streamlit

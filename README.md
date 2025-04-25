# Task-2-Elevate-Labs
# Task 2 Exploratory Data Analysis (EDA)

This project is part of my internship task aimed at performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries. The goal is to understand the data through summary statistics and visualizations to identify important patterns and trends.

---

## Objective

To explore and understand the Titanic dataset using statistical analysis and visualizations for insights that will help in building future machine learning models.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (optional, interactive visualization)

---

## Steps Performed

### 1. Summary Statistics
- Used `.describe()` to get mean, median, standard deviation, and quartiles for numerical features.
- Displayed count, unique values, and top frequencies for categorical features.

### 2. Histograms & Boxplots
- Created **histograms** to visualize distributions of numerical columns like `Age`, `Fare`, `SibSp`, and `Parch`.
- Used **boxplots** to detect outliers and understand value spread.

### 3. Pairplot & Correlation Matrix
- Generated a **correlation heatmap** (only numeric columns) to identify relationships between features.
- Used **pairplot** to visualize pairwise relationships, colored by survival status.

### 4. Pattern & Anomaly Detection
- Found clear patterns such as:
  - Higher survival rate for **females**.
  - Better survival chances for **1st class passengers**.
  - Outliers in `Fare` and `Age`.

### 5. Feature-Level Inferences
- Sex, class, and age are important features for predicting survival.
- Categorical encoding and numerical scaling may be needed before modeling.

---

## Files Included

- `Elevate Labs task 2.ipynb` – Jupyter notebook with all visualizations and code
- `README.md` – This file
- `Titanic-Dataset.csv` - dataset file

---

## Conclusion

This EDA helped uncover key patterns and relationships in the Titanic dataset, which will guide effective feature engineering and model building in the next steps.


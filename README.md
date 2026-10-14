 # Python Data Analysis & Machine Learning Practice

A hands-on repository documenting exploratory data analysis (EDA), data visualization, and applied baseline machine learning models developed in Google Colab.

---

## 📌 Repository Overview

This repository contains practical exercises and foundational workflows covering end-to-end data processing, feature inspection, visual analytics, and baseline supervised learning implementations using standard Python libraries.

### Core Objectives
- Hands-on data cleaning, indexing, aggregation, and handling missing values.
- Exploratory data visualization and pattern discovery using statistical plotting libraries.
- Implementation and evaluation of baseline Linear Regression and Logistic Regression models.
- Model performance assessment using standard regression and classification metrics.

---

## 🛠️ Tech Stack & Libraries

- **Environment:** Google Colab
- **Language:** Python
- **Data Manipulation & Math:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning (Scikit-Learn):**
  - Algorithms: `LinearRegression`, `LogisticRegression`
  - Preprocessing: `StandardScaler`, `train_test_split`, `GridSearchCV`
  - Evaluation Metrics: `r2_score`, `mean_squared_error`, `confusion_matrix`, `classification_report`, `roc_curve`, `roc_auc_score`

---

## 📂 Notebook Highlights & Implemented Workflows

1. **Exploratory Data Analysis (EDA):**
   - DataFrame inspection (`head()`, `tail()`, `info()`, `describe()`, column indexing).
   - Value counting, filtering, sorting, and summary statistics.
   - Grouping and aggregations (`groupby()`, `.agg()`).
   - Merging tabular datasets (`pd.merge()`).

2. **Visual Analytics:**
   - Distribution analysis using histograms and Kernel Density Estimates (KDE).
   - Categorical visualization using bar charts and count plots.
   - Correlation analysis via heatmaps (`sns.heatmap`) and pair plots (`sns.pairplot`).
   - Scatter plots and box plots for numerical comparison.

3. **Supervised Learning Workflows:**
   - **Linear Regression:** Multi-feature regression pipelines, coefficient inspection, and residual error evaluation ($R^2$, MSE, RMSE).
   - **Logistic Regression:** Feature scaling (`StandardScaler`), training baseline classifiers, probability estimation, and evaluating classification reports, confusion matrices, and ROC/AUC curves.

---

## 👥 Scope & Attribution

- **Type:** Technical Practice & Coursework Implementation
- **Focus:** Practical application of foundational data manipulation, exploratory plotting, and standard supervised learning algorithms.

# CS4503 – Data Analytics and Visualization Lab

---

## 📌 About This Repository

This repository contains the Python and Jupyter Notebook implementations completed for the **Data Analytics and Visualization Laboratory**.

The repository currently covers experiments **up to Experiment 4(D)**, including data handling, statistical analysis, regression modeling, data visualization, and hypothesis testing.

---

## 🧪 Experiments Completed

### Experiment 1 – Installation and Exploration

Exploration and verification of Python libraries used for scientific computing, data analysis, statistics, and visualization.

**Libraries:**
- NumPy
- SciPy
- Jupyter
- Statsmodels
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Bokeh

---

### Experiment 2 – Data Handling and Analysis

#### 2A. NumPy Array Operations

- Array creation
- Indexing and slicing
- Element-wise operations
- Aggregation
- Boolean operations
- Boolean masking
- Fancy indexing
- Reshaping
- Structured arrays

#### 2B. Pandas DataFrame Operations

- Loading datasets
- Data inspection
- Summary statistics
- Handling missing values
- Creating new columns
- Filtering
- Grouping and aggregation
- Sorting
- Boolean masking
- Removing duplicates
- Selecting columns
- Exporting data

#### 2C. Reading Data from Different Sources

Reading and processing data from:

- Text/CSV files
- Excel files
- Web-based sources

#### 2D. Descriptive Analytics Using Iris Dataset

- Dataset exploration
- Summary statistics
- Species frequency analysis
- Histograms
- Boxplots
- Pair plots
- Feature distribution analysis

---

## 🩺 Experiment 3 – Statistical Analysis Using Diabetes Datasets

The **UCI Diabetes Dataset** and **Pima Indians Diabetes Dataset** are used for statistical and regression analysis.

### 3A. Univariate Analysis

Statistical measures calculated include:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Skewness
- Kurtosis

Variables analyzed include:

`Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age`

### 3B. Bivariate Analysis – Linear and Logistic Regression

#### Linear Regression

Analyzes the relationship between:

**Glucose → BMI**

Performance is evaluated using the **R² Score**.

#### Logistic Regression

Predicts diabetes outcome using:

**Glucose, BloodPressure, BMI, Age**

Performance is evaluated using **Accuracy Score**.

### 3C. Multiple Regression Analysis

Multiple Linear Regression is used to predict **BMI** using:

- Glucose
- BloodPressure
- Age

The model is evaluated using the **R² Score**.

### 3D. Comparison of Analysis Results

The UCI and Pima Diabetes datasets are compared based on:

- Mean
- Median
- Variance
- Skewness
- Kurtosis
- Linear Regression performance
- Logistic Regression accuracy
- Multiple Regression performance

---

## 📊 Experiment 4 – Data Visualization and Hypothesis Testing

### 4A. Normal Curves

Normal distribution curves are visualized for important attributes of the UCI Diabetes Dataset, including:

- Glucose
- BMI

Histograms with KDE curves and normal distribution curves are used.

### 4B. Z-Test

A Z-test is performed on the UCI Diabetes Dataset to determine whether the mean glucose level significantly differs from a specified population mean.

### 4C. T-Test

An independent T-test is performed to compare the means of selected variables between the UCI and Pima Diabetes datasets.

Variables:

- Glucose
- BloodPressure
- BMI

### 4D. ANOVA

One-Way ANOVA is performed to compare group means and determine whether statistically significant differences exist.

**Decision Rule:**

- `p < 0.05` → Significant difference
- `p ≥ 0.05` → No significant difference

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Jupyter Notebook | Interactive execution |
| NumPy | Numerical computing |
| Pandas | Data manipulation |
| SciPy | Statistical analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Regression and machine learning |
| Statsmodels | Statistical modeling |
| Plotly | Interactive visualization |
| Bokeh | Interactive visualization |

---

## 📁 Repository Structure

```text
Data-Analytics-and-Visualization/
│
├── Experiment-1/
│
├── Experiment-2/
│   ├── 2A-NumPy/
│   ├── 2B-Pandas/
│   ├── 2C-Data-Sources/
│   └── 2D-Iris/
│
├── Experiment-3/
│   ├── 3A-Univariate-Analysis/
│   ├── 3B-Linear-Logistic-Regression/
│   ├── 3C-Multiple-Regression/
│   └── 3D-Dataset-Comparison/
│
├── Experiment-4/
│   ├── 4A-Normal-Curves/
│   ├── 4B-Z-Test/
│   ├── 4C-T-Test/
│   └── 4D-ANOVA/
│
├── datasets/
│
└── README.md

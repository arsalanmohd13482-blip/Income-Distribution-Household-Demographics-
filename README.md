# 📊 Income Distribution & Household Demographics

## 📌 Project Overview

This project analyzes household income and demographic characteristics using Python and statistical techniques.

The objective is to understand the distribution of household income and explore how income varies across factors such as **education level, urban/rural location, house ownership, family size, and age of the household head**.

The analysis focuses on moving beyond simple averages by examining **variability, distribution shape, potential outliers, and relationships between variables**.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Excel / Google Colab

---

## 📂 Dataset

The dataset contains **200 households and 7 variables**.

| Variable                | Type        | Description                 |
| ----------------------- | ----------- | --------------------------- |
| `Household_ID`          | Identifier  | Unique household ID         |
| `Age_of_Household_Head` | Numerical   | Age of household head       |
| `Household_Income`      | Numerical   | Household income            |
| `Education_Level`       | Categorical | Education level             |
| `Family_Size`           | Numerical   | Number of household members |
| `Owns_House`            | Categorical | House ownership status      |
| `Urban_Rural`           | Categorical | Urban or rural location     |

---

## 🔬 Analysis Performed

### Descriptive Statistics

* Mean
* Median
* Mode
* Range
* Variance
* Standard deviation
* Quartiles
* IQR

### Distribution Analysis

* Histogram
* Gaussian distribution comparison
* Skewness
* Kurtosis
* Outlier detection

### Comparative Analysis

* Income by education level
* Urban vs rural income
* Income by house ownership
* Family size by education
* Age vs income

---

## 📈 Key Findings

### 1. Household Income is Right-Skewed

* Mean income: **64,956**
* Median income: **56,571**
* Skewness: **1.095**

The mean being higher than the median, combined with positive skewness, indicates a right-skewed income distribution with a smaller group of higher-income households.

### 2. Income Shows High Variability

The standard deviation is approximately **40,310**, showing substantial variation between household incomes.

### 3. Potential High-Income Outliers

The IQR method identifies **7 observations** above the upper outlier boundary of approximately **162,412**.

The maximum observed income is **204,776**.

These observations should be investigated rather than automatically removed because they may represent genuine high-income households.

### 4. Urban Households Have Higher Observed Income

| Location | Average Income | Median Income |
| -------- | -------------: | ------------: |
| Rural    |         60,239 |        54,359 |
| Urban    |         69,398 |        64,207 |

Urban households show higher average and median income in this sample.

### 5. Education Does Not Show a Simple Linear Pattern

Post-Graduate households have the highest average income, but income does not increase consistently across every education level.

Therefore, a formal statistical test would be required before making a stronger conclusion.

### 6. Age Has Almost No Linear Relationship With Income

The simple correlation between age and household income is approximately:

**r = 0.008**

This indicates essentially no meaningful linear relationship in this sample.

---

## 📊 Statistical Takeaway

The strongest finding from the project is that **household income is much more variable and asymmetric than age or family size**.

This demonstrates why we should not rely only on the mean. Median, IQR, standard deviation, skewness, kurtosis, and outlier analysis provide a more complete understanding of the data.

---

## ⚠️ Limitations

* The dataset contains only 200 households.
* The analysis is observational.
* Association does not imply causation.
* Descriptive differences are not automatically statistically significant.
* Income is strongly skewed, so statistical-test assumptions should be checked.

---

## 🚀 Future Improvements

The next stage of the project will extend the analysis into inferential statistics:

* Hypothesis testing
* Confidence intervals
* Effect sizes
* Correlation significance testing
* ANOVA / non-parametric group comparisons
* Regression analysis

The goal is to determine not only **what the data looks like**, but also **whether the observed relationships are statistically supported**.

---



**Statistics → Python → Data Analysis → Machine Learning → ML Engineering**

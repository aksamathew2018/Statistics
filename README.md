# Customer PurchaseAmount Analysis

This project explores customer purchasing behaviour using a dataset that
contains information such as `PurchaseAmount`, gender, product category,
region, and churn status.  
The main goal is to answer a set of business and statistics questions
using Python and basic statistical techniques.

---

## Objectives

The analysis focuses on the following questions:

1. **Central tendency of spending**
   - What are the **average (mean)**, **median**, and **mode** of `PurchaseAmount`?

2. **Outlier detection**
   - Are there any **outliers** in the `PurchaseAmount` data?

3. **Shape of the distribution**
   - Is there any **skewness** or **kurtosis** in the `PurchaseAmount` distribution?

4. **Gender differences**
   - Is there a significant difference in spending between **male** and **female** customers?

5. **Product category & churn**
   - Is there a relationship between **ProductCategory** and **customer churn**?

6. **Regional variation**
   - Does `PurchaseAmount` vary significantly across different **regions**?

7. **Email campaign performance**
   - Which email campaign (**A or B**) performed better in terms of **average PurchaseAmount**?

8. **Normality of PurchaseAmount**
   - Can we assume `PurchaseAmount` follows a **normal distribution**?

9. **Central Limit Theorem**
   - What insights can we gain by applying the **Central Limit Theorem (CLT)** to `PurchaseAmount`?

10. **Confidence interval**
    - What is the **95% confidence interval** for the average `PurchaseAmount`?

---

## Dataset

`

---

## Methods & Tools

The analysis is done primarily in Python using:

- **pandas** for data loading, cleaning, and basic statistics
- **numpy** for numerical operations
- **matplotlib / seaborn** for visualizations
- **scipy.stats** or **statsmodels** for hypothesis testing and confidence intervals

Typical techniques used:

- Descriptive statistics (mean, median, mode, variance, std)
- Boxplots / IQR rule or z-scores for outlier detection
- Skewness and kurtosis calculation
- t-test / ANOVA for group comparisons (e.g., gender, region, campaigns)
- Chi-square test for association between `ProductCategory` and `Churn`
- Normality checks (histogram, Q–Q plot,, etc.)
- Central Limit Theorem demonstration using sampling distributions
- Confidence interval estimation for the mean

---

## Repository Structure



```text
.
├── Assignment_Statistics.ipynb   # Main Jupyter notebook with all analysis
├── data/
│   └── customer_data.csv         # Raw dataset (not always included in repo)
├── README.md                     # Project description (this file)
└── requirements.txt              # Python dependencies (optional)


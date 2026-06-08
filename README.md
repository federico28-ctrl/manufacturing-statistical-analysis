# manufacturing-statistical-analysis
A collection of projects applied to manufacturing and quality control
# Manufacturing & Operations Statistical Analysis

It`s my repository dedicated to practical statistical analysis in manufacturing and quality control.

## Project 1: Two-Sample, Equal Variance t-Test 
### 📌 Business Context
Imagine a situation where a supplier of electronic components offers a lower price. While switching to a new partner offers clear financial benefits, it carries a high risk for product quality. 

This project simulates a tensile strength test (Pull-off Force in Newtons) for connectors from two different suppliers ($n=30$ for each) to make a data-driven decision.

### 📊 Methodology & Formulas
Since both factories are certified and run automated production lines, the variability (dispersion) of parts is considered equal. The analysis implements:
* **Pooled Standard Deviation ($s_p$)** to combine sample variances.
* **Two-Sample t-Test** to compare sample means.

### 🚀 Key Results
* **t-statistic:** 0.704 (with $DF = 58$)
* **p-value:** ~0.48 (p > 0.05)

**Business Conclusion:** The difference in strength is purely random and statistically insignificant. The company can safely switch to the cheaper supplier, saving the budget without compromising product quality.

### 📂 How to run the code
1. Open the notebook: `01_equal_variance_t_test_suppliers.ipynb`
2. Run the cells to reproduce the data simulation and view the `seaborn` visualization.

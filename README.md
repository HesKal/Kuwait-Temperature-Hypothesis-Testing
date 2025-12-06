# 🌡️ Hypothesis Testing: Investigating Kuwait's Average Temperature

This repository documents a statistical analysis project designed to investigate the impact of global warming on Kuwait's climate. The core of the project is a one-tailed hypothesis test to determine if the average temperature has significantly exceeded 90°F.

This project was completed as part of the "Statistics and Probability (CIS 2003)" course.

---

## 🎯 Research Problem & Objective

The research aims to answer a critical question: **Is there statistical evidence to suggest that the average temperature in Kuwait is significantly higher than 90°F?**

This investigation serves as a case study on the local effects of global warming, using a sample of 34 temperature readings from a larger dataset spanning 1995-2020.

---

## 🧪 Methodology

My role in this project was focused on the core statistical methodology, from planning to conclusion.

### 1. Sampling Method
To ensure an unbiased and representative sample, a **stratified random sampling** technique was employed. The data was first stratified by region (Middle East) and country (Kuwait), after which 34 temperature readings were randomly selected. This method minimizes bias and provides a solid foundation for statistical analysis. The data was sourced from a trusted dataset on Kaggle, originally from the University of Dayton.

### 2. Descriptive Statistics
Initial analysis of the sample data (n=34) revealed:
- **Mean:** 80.89°F
- **Median:** 85.35°F
- **Standard Deviation:** 19.06°F
- **Distribution:** The data exhibited a left-skewed, bimodal distribution.

![Histogram](https://github.com/HesKal/Kuwait-Temperature-Hypothesis-Testing/blob/main/Histogram.png )
![Boxplot](https://github.com/HesKal/Kuwait-Temperature-Hypothesis-Testing/blob/main/BoxPlot.png)
### 3. Hypothesis Testing (My Core Contribution)
This was the central part of my contribution. I formulated and executed a one-tailed Z-test to validate our research question.

**Formulating the Hypotheses:**
- **Null Hypothesis (H₀):** The true mean temperature is less than or equal to 90°F.  `(μ ≤ 90)`
- **Alternative Hypothesis (H₁):** The true mean temperature is greater than 90°F.  `(μ > 90)`

**Test Execution:**
- **Significance Level (α):** 0.05
- **Test Statistic (Z-score):** Calculated using the sample mean (80.89), population mean (90), sample size (34), and standard deviation (19.06).

The resulting Z-score was **-2.79**.

![Python Visualization of Z-test](https://github.com/HesKal/Kuwait-Temperature-Hypothesis-Testing/blob/main/python_visualization.png)

---

## 📊 Conclusion & Results

The calculated Z-score of **-2.79** falls far outside the rejection region for a one-tailed test at α=0.05 (which starts at Z=1.645).

**Decision:** We **fail to reject the null hypothesis (H₀)**.

**Interpretation:** Based on our sample, there is **not enough statistical evidence** to conclude that the average temperature in Kuwait is significantly higher than 90°F. This was a critical insight, demonstrating the importance of rigorous statistical testing over anecdotal observations.

---

## 💡 What I Learned

This project was a deep dive into the practical application of statistical theory. My key takeaways were:
- The importance of proper sampling techniques to ensure data integrity.
- The complete process of conducting a hypothesis test, from formulating hypotheses to interpreting the results in a real-world context.
- Using Python and its libraries to visualize statistical concepts, bridging the gap between theory and practical application.


---

## 💻 Technical Implementation

The complete Python code for generating the descriptive statistics plots and visualizing the hypothesis test can be found in the Jupyter Notebook in this repository.

➡️ **[View the full analysis in the Jupyter Notebook](./Analysis.ipynb)**




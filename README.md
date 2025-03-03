
# Apple Store Reviews Analysis

This repository contains a comprehensive statistical analysis of the Apple Store Reviews dataset. 
The analysis explores user ratings, purchase amounts, likes, and correlations to draw meaningful insights. 
All steps are implemented using Python, and the notebook includes visualizations and key statistical methods.

---

## **Statistical Analysis Overview**

### **1. Central Tendency Analysis**
- **Objective:** Calculate the mean, median, and mode of app ratings and determine the best measure of central tendency.
- **Results:**
  - **Mean:** 2.869
  - **Median:** 3.0
  - **Mode:** 1.0
  - **Conclusion:** The **median** best represents the central tendency, as it is unaffected by outliers and provides a reliable measure for the dataset.

### **2. Spread of Data**
- **Objective:** Calculate the range and interquartile range (IQR) of the purchase amounts to understand the spread of the data.
- **Results:**
  - **Range:** 19.97
  - **IQR:** 10.19
  - **Conclusion:** The **IQR** highlights the spread of the middle 50% of purchase amounts, showing moderate variability in typical spending.

### **3. Variability Analysis**
- **Objective:** Calculate the variance and standard deviation for the number of likes on reviews.
- **Results:**
  - **Standard Deviation:** 28.69
  - **Variance:** 822.85
  - **Conclusion:** The moderate standard deviation indicates variability in user engagement, with some reviews receiving significantly more likes than others.

### **4. Correlation Analysis**
- **Objective:** Determine the correlation between the number of likes and app ratings.
- **Results:**
  - **Correlation Coefficient:** 0.8425
  - **Conclusion:** A strong positive correlation exists, suggesting that higher ratings are associated with more likes, indicating user preference for highly rated content.

### **5. Distribution Analysis**
- **Objective:** Plot the distribution of app ratings and analyze the skewness.
- **Results:**
  - **Skewness:** 0.102
  - **Conclusion:** The distribution is approximately symmetrical with a slight positive skew, indicating balanced user satisfaction with a tendency for higher ratings.

### **6. Hypothesis Testing**
- **Objective:** Test if Instagram's average rating is significantly higher than WhatsApp's at a 95% confidence level.
- **Results:**
  - **T-Statistic:** -0.797
  - **P-Value:** 0.787
  - **Conclusion:** There is no statistically significant difference between the average ratings of Instagram and WhatsApp.

### **7. Central Limit Theorem (CLT)**
- **Objective:** Take random samples of ratings, calculate their means, and create a sampling distribution to demonstrate the CLT.
- **Results:**
  - **Population Mean:** 2.869
  - **Sampling Mean:** 2.878
  - **Standard Error:** 0.268
  - **Conclusion:** The sampling distribution is normal, supporting the CLT. This allows reliable inference about the population mean from sample means.

---

## **How to Use This Repository**

1. **Dataset:** The dataset used for this analysis is included in the `Apple_Store_Reviews.csv` folder.
2. **Notebook:** The Python analysis notebook (`Apple_store_reviews_analysis.ipynb`) contains the complete code, visualizations, and statistical computations.
3. **Requirements:**
   - Python 
   - Libraries: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`

---

## **Connect**
Feel free to reach out with any questions or feedback:
- **Email:** bhuvanjari001@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/bhuvan-jari-001bz
---

Thank you for exploring this analysis!

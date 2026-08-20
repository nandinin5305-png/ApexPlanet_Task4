# ApexPlanet Task 4 — Hypothesis Testing

## 📌 Project Overview

This project was completed as part of the ApexPlanet Data Analytics Internship.

The objective of Task 4 is to apply statistical hypothesis testing techniques to a cleaned sales dataset, identify statistically significant patterns, and derive meaningful business insights.

## 🎯 Objectives

* Perform statistical hypothesis testing using Python.
* Test whether average Total Sales differs from ₹100,000.
* Analyze the relationship between Quantity and Total Sales.
* Interpret p-values and statistical significance.
* Present findings using visualizations and a final presentation.

## 📊 Dataset

The analysis uses a cleaned sales dataset containing 1,000 records.

Key variables include:

* Age
* Quantity
* Unit Price
* Total Sales

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Google Colab
* Microsoft PowerPoint

## 🔬 Hypothesis Test 1 — Average Total Sales

### Hypotheses

**H₀:** The mean Total Sales is ₹100,000.

**H₁:** The mean Total Sales is different from ₹100,000.

### Test Used

One-Sample t-Test

### Results

* Sample Mean: ₹139,399.44
* Hypothesized Mean: ₹100,000
* t-statistic: 10.92
* p-value: 2.66 × 10⁻²⁶
* Significance Level: 0.05

### Conclusion

Since the p-value is less than 0.05, the null hypothesis is rejected. There is statistically significant evidence that the average Total Sales is different from ₹100,000.

## 📈 Hypothesis Test 2 — Quantity vs Total Sales

### Hypotheses

**H₀:** There is no significant relationship between Quantity and Total Sales.

**H₁:** There is a significant relationship between Quantity and Total Sales.

### Test Used

Pearson Correlation

### Results

* Correlation Coefficient: 0.647
* p-value: 1.71 × 10⁻¹¹⁹
* Significance Level: 0.05

### Conclusion

Since the p-value is less than 0.05, the null hypothesis is rejected. There is a statistically significant positive relationship between Quantity and Total Sales.

## 📊 Visualizations

The project includes:

* Total Sales Distribution
* Quantity vs Total Sales scatter plot

## 💡 Key Business Insights

1. The average Total Sales in the dataset is approximately ₹139,399.
2. The average Total Sales is statistically different from the ₹100,000 benchmark.
3. Quantity and Total Sales have a statistically significant positive relationship.
4. Statistical testing can help support data-driven business decisions.

## 📁 Project Structure

```text
ApexPlanet_Task4
│
├── Dataset
│   └── Cleaned_Sales_Dataset.xlsx
│
├── Notebook
│   └── Task4_Hypothesis_Testing.ipynb
│
├── Presentation
│   └── Task4_Final_Presentation.pptx
│
├── Hypothesis_Testing
│   ├── Task3_PowerBI_Dataset.xlsx
│   ├── Task3_Deep_Dive_Analysis.xlsx
│   ├── Task3_Customer_Segmentation.xlsx
│   ├── Task3_KPI_Summary.xlsx
│   └── Task4_Hypothesis_Testing_Results.xlsx
│
└── Screenshots
    ├── Total_Sales_Distribution.png
    └── Quantity_vs_Total_Sales.png
```

## ✅ Conclusion

Task 4 demonstrates the use of statistical hypothesis testing to evaluate sales performance and relationships within the dataset. The analysis provides statistical evidence that can be used to support business-oriented decision-making.


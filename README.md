

# Marketing Strategy Conversion Rate Analysis 📊

A comprehensive data science project analyzing marketing campaign effectiveness through **A/B testing**, **temporal pattern analysis**, and **machine learning prediction models**.

---

## Why It Matters 💡

* ⏱️ Optimized ad scheduling can boost conversions by **15–20%**
* 📈 Data-driven strategy selection improves **marketing ROI**
* 🤖 Predictive modeling enables **real-time targeting**

---

## Project Overview

This project examines user conversion patterns in marketing campaigns using statistical analysis and machine learning techniques. The analysis focuses on:

* Identifying **optimal timing strategies**
* Evaluating **A/B test effectiveness**
* Building **predictive models** for conversion likelihood

---

## Dataset Description

The dataset contains **588,101 user records** with the following features:

* **UserId**: Unique identifier for each user
* **test\_group**: A/B test assignment (`ad` vs `psa`)
* **total\_ads**: Total number of ads displayed to user
* **most\_ads\_day**: Day of week with highest ad exposure
* **most\_ads\_hour**: Hour of day with highest ad exposure
* **converted** (target): Binary purchase indicator

---

## Key Findings

### Temporal Analysis 🔍

* **Peak conversion days**: Monday & Tuesday
* **Optimal hours**: 10 AM – 6 PM
* **Low activity**: 4 AM – 7 AM

📊 Example Visualization:
![Temporal Analysis](visualizations/temporal_analysis_charts.png)

---

### A/B Testing Results 🎯

| Strategy | Exposures | Conversions | Conversion Rate |
| -------- | --------- | ----------- | --------------- |
| **Ad**   | 550,154   | 14,423      | 2.62%           |
| **PSA**  | 23,104    | 420         | 1.82%           |

* ✅ Chi-square test (p < 0.001) → **Statistically significant difference**
* 📢 Recommendation: Prefer **Ad strategy** over PSA

📊 Example Visualization:
![A/B Test Results](visualizations/ab_test_results.png)

---

### Machine Learning Performance 🤖

| Model                    | Accuracy | Precision | Recall |
| ------------------------ | -------- | --------- | ------ |
| Logistic Regression      | **86%**  | 0.12      | 0.69   |
| Decision Tree Classifier | 82%      | 0.75      | 0.10   |

* **Best Model**: Logistic Regression (robust, interpretable)
* **Key Predictor**: Day ads shown(imbalanced)
* **Learning curve** shows stable performance with enough training data

📊 Example Visualization:
![Model Performance](visualizations/model_performance_curves.png)

---

## Techniques Implemented

### Data Analysis

* 📊 Exploratory Data Analysis (EDA)
* 📈 Data visualization with Seaborn/Matplotlib
* 🔧 Modular, reusable code functions

### Statistical Methods

* ✅ A/B Testing (chi-square validation)
* 🔗 Correlation analysis
* ⭐ Feature importance ranking

### Machine Learning

* ⚖️ Class imbalance handling (oversampling/undersampling)
* 🔄 Cross-validation for robust performance
* 📉 Learning curve analysis for validation

---

## Business Impact 🚀

1. **Schedule Optimization** → Focus ad spend on weekdays, 10 AM – 6 PM
2. **Strategy Selection** → Adopt **Ad** strategy for higher conversions
3. **Predictive Targeting** → Use ML model for **real-time scoring**

💰 **ROI Implications**:

* 15–20% improvement in conversion rates
* Cost savings by avoiding low-performance slots
* Smarter campaigns via predictive targeting

---

## Project Structure

```
├── marketing_AB.csv
├── ONLINE SALES PREDICTION.ipynb
├── visualizations/
│   ├── ms1.png
│   ├── ms2.png
│   └── ms3.png
└── README.md
```

---

## Technical Requirements ⚙️

```bash
pandas >= 1.3.0
numpy >= 1.21.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
scikit-learn >= 1.0.0
scipy >= 1.7.0
```

---

## Getting Started

1. Clone the repository

   ```bash
   git clone https://github.com/giftkalu/Marketing_Strategies-_Conversion_Rate_Analysis_with_Python.git
   ```
2. Install dependencies
3. Open notebook

   ```bash
   jupyter notebook Marketing_Strategies_Conversion_Rate_Analysis.ipynb
   ```

---

## Future Enhancements 🛠️

* [ ] Implement additional ML algorithms (Random Forest, XGBoost)
* [ ] Improved class imbalancement handling
* [ ] Extend dataset for **seasonal trend analysis**
* [ ] Build interactive **dashboard** for stakeholders
* [ ] Advanced feature engineering techniques

---
## Full Case Study📑

For full report on this analysis, click 👉[here](https://docs.google.com/document/d/167roNpH01L2mKu511366BbmNIBA9-YdtQax_UMPLo8I)

---

## Contributing 🤝

Contributions welcome! Submit pull requests or open issues for discussion.

⭐ If you found this repository useful, please give it a star!


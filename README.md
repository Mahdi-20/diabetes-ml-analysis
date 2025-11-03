
# 🩺 Diabetes Disease Progression Prediction (Machine Learning Project)

### 📘 Overview
This project explores the **Diabetes dataset** from `scikit-learn` to predict the *progression of diabetes disease* based on ten baseline health variables such as age, BMI, and blood pressure.

The main goal is to:
- Compare different regression models (Linear, Ridge, Lasso, Random Forest)
- Evaluate their performance using metrics like RMSE and R²
- Interpret which features most strongly affect disease progression

---

### 📊 Dataset Description
The dataset comes from the **`load_diabetes()`** function in scikit-learn.

| Property | Value |
|-----------|--------|
| **Samples** | 442 |
| **Features** | 10 (age, sex, bmi, bp, s1–s6) |
| **Target** | Quantitative measure of disease progression |
| **Source** | scikit-learn built-in dataset |

To load the data:
```python
from sklearn.datasets import load_diabetes
data = load_diabetes()
X, y = data.data, data.target







diabetes-ml-analysis/
│
├── data/                   # optional dataset exports
├── notebooks/
│   └── diabetes_analysis.ipynb
├── reports/
│   └── diabetes_report.pdf
├── src/
│   ├── preprocess.py
│   ├── train_model.py
│   ├── evaluate.py
│   └── visualize.py
├── requirements.txt
└── README.md
```


## 📄 Report
You can view the full analysis and model documentation here:

- [Diabetes Regression Report (PDF)](reports/Report on Regression_Assignment_Diabetes.pdf)
- [LaTeX Source File](Report on Regression_Assignment_Diabetes.tex)


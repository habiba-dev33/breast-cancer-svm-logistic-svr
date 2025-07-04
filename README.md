# breast-cancer-svm-logistic-svr
  تصنيف أورام الثدي Breast Cancer Classification using Logistic Regression and SVM with Polynomial Kernel. Also includes a bonus demo of Polynomial Regression using SVR for educational purposes 
#  Breast Cancer Classification & Polynomial Regression

This project contains two main parts:

---

##  1. Breast Cancer Classification

Using the **Breast Cancer Wisconsin (Diagnostic)** dataset from UCI, this section applies:

- ✅ Logistic Regression (baseline model)
- ✅ SVM with Polynomial Kernel (degree=2)

###  Evaluation Metrics:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix (visualized)

### Tools Used:
- `sklearn.linear_model.LogisticRegression`
- `sklearn.svm.SVC`
- `StandardScaler`, `train_test_split`
- `Seaborn` for visualization

---

##  2. Polynomial Regression with SVR (Demo)

This section is a simple demo to understand how **Support Vector Regression (SVR)** works with a **polynomial kernel**. We generate a noisy quadratic function:

- Polynomial: `-x² + x + 15`
- Noise added using `random.gauss(0,2)`
- SVR model trained and plotted

###  Tools Used:
- `sklearn.svm.SVR`
- `matplotlib.pyplot` for plotting

---

##  Dataset

- **Source**: [UCI Machine Learning Repository - WDBC](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data)

---

## 📷 Screenshots (Optional)

> Add graphs or confusion matrix visualizations here if you'd like.

---

## Author

**Habiba Elgendy**

---


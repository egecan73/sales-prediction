# 📈 Sales Prediction with Linear Regression

This project aims to predict product sales based on advertisement spend across three media channels: **TV**, **Radio**, and **Newspaper**.  
The dataset used comes from a publicly available advertising dataset on Kaggle.

---

## 📊 Dataset

- **Source**: [Advertising Dataset (Kaggle)](https://www.kaggle.com/datasets/ashydv/advertising-dataset)
- **Features**:
  - `TV`: Advertising budget on TV
  - `Radio`: Advertising budget on Radio
  - `Newspaper`: Advertising budget on Newspapers
  - `Sales`: Product sales (target variable)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📌 Project Steps

1. **Data Loading & Exploration**
   - Dataset structure, summary stats, correlation matrix
2. **Data Visualization**
   - Pairplots, heatmaps to explore relationships
3. **Modeling**
   - Linear Regression using scikit-learn
4. **Evaluation**
   - R² Score, MAE, and Cross-validation
5. **Feature Interpretation**
   - Analysis of model coefficients

---

## 🧠 Insights

- **TV and Radio** are strong predictors of sales.
- **Newspaper** has a weaker correlation.
- Linear regression offers a good baseline for modeling ad impact on sales.

---

## 🚀 Future Improvements

- Try **Ridge/Lasso regression** to improve generalization.
- Use **SHAP values** or **permutation importance** for feature interpretability.
- Deploy the model using **Streamlit** or **Flask**.
- Extend with more complex models like **Random Forest** or **XGBoost**.

---

## 👤 Author

Created by [Egecan] — aspiring marketing & data analyst.  
Feel free to connect on [LinkedIn](www.linkedin.com/in/egecan-karabulut-52107959)!


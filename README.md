# 📊 Predicting Life Expectancy

## 👀 Overview
This project explores methods to predict life expectancy using machine learning models. It aims to identify the best-performing approach by improving the \( R^2 \) score through feature engineering and model optimization. 

### 🪜 Key Steps:
1. **Data Exploration** 
   - Understand the dataset structure and variable distributions.
   
2. **Exploratory Data Analysis (EDA)** 
   - Handle missing values using mean/mode imputation.
   - Perform one-hot and label encoding for categorical variables.

3. **Feature Engineering**
   - Feature scaling using normalization techniques.
   - Feature extraction: Identify the top features impacting life expectancy.

4. **Model Building**
   - Train and evaluate regression models including:
     - Linear Regression
     - Lasso Regression
     - Advanced feature selection using PCA

5. **Evaluation**
   - Evaluate models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and \( R^2 \).

---

## 💪 Motivation
Understanding and predicting life expectancy can:
- Aid policymakers in addressing public health challenges.
- Enable targeted interventions in healthcare and resource allocation.

---

## 🔍 Methodology
1. **Data Preprocessing**
   - Imputation of missing values.
   - Winsorization to handle outliers.
   - Address multicollinearity using Variance Inflation Factor (VIF).

2. **Feature Selection**
   - Identify highly correlated features to life expectancy.
   - Perform Principal Component Analysis (PCA) to reduce dimensionality.

3. **Model Training**
   - Compare results from multiple regression models to maximize \( R^2 \).

---

## ✅ Results
| Model                | \( R^2 \) Score        | Improvement |
|----------------------|-----------------------|-------------|
| Linear Regression    | 0.8054               | -           |
| Lasso Regression     | 0.8064               | 0.012%      |
| Multilinear Regression (80/20 Split) | Best Performance | Significant |

---

## 🔧 Technologies Used
```text
- Pandas & NumPy: Data manipulation and numerical computations.
- Scikit-learn: Model training and evaluation.
- Seaborn & Matplotlib: Data visualization.
- Statsmodels: Statistical analysis and multicollinearity checks.
```

---

## 🔒 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/AlexCortes04/ML_toPredict_LifeExpectancy.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Regression_Models_to_Predict_Life_Expectancy.ipynb
   ```

---

## 📢 Contributing
Contributions are welcome! Please create an issue or submit a pull request.

---

## 👁‍🗨 License
This project is licensed under the [MIT License](LICENSE).


# 📊 Predicting Life Expectancy

## 👀 Overview
This project explores methods to predict life expectancy using machine learning models. It aims to identify the best-performing approach by improving the R² score through feature engineering and model optimization. 

---

## Problem statement: 
To predict the life expectancy of people in a country based on various immunization factors and the country in which they are based so that necessary action can be taken to increase the life expectancy.

---

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
    - Imputation of missing values
    - Label /One Hot encoding.
    - Format text.

2. **Feature Selection**
    - Address multicollinearity using Variance Inflation Factor (VIF).
    - Identify highly correlated features to life expectancy.
    - Handle positive and negative skewness with Yeo-Jonson and Square methods.
    - MinMax Scaling to normalize data.
    - Perform Principal Component Analysis (PCA) to reduce dimensionality.

3. **Model Training**
    - Use 60/40 and 80/20 splitted data to compare performance.
    - Build a simple linear regression model over 60/40 data.
    - Build a multilinear regression model with both 60/40 and 80/20 data.
    - Plot the best fit line for each independent feature 
    - Compare results from multiple regression models to maximize R².

4. **Model Evaluation and Tuning**
    - Display test data predictions for each model.
    - Evaluate models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.
    - K-fold Cross Validation and Lasso Regression

---

## ✅ Results
| Model                | R² Score      |
|----------------------|----------------------|
| Linear Regression    | 0.8054               |
| Lasso Regression     | 0.8047               |
| Multilinear Regression (80/20 Split) | Best Performance |

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


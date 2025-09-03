# Polynomialregression_ML_pipeline
This project demonstrates how **Linear Regression** can underfit nonlinear data and how **Polynomial Regression** can improve the fit.   A synthetic quadratic dataset is generated, and different regression models are compared using **R² score** and visualizations.

## 📊 Features
- Generate synthetic quadratic dataset with noise
- Fit **Linear Regression** model
- Fit **Polynomial Regression** (degree 2 and degree 3)
- Compare model performance using **R² score**
- Visualize predictions vs. true data

📈 Results

Linear Regression: R² ≈ 0.58 → underfits nonlinear data

Polynomial Regression (degree 2): R² ≈ 0.80 → good fit

Polynomial Regression (degree 3): R² ≈ 0.79 → slightly worse due to overfitting noise

Visualization shows how polynomial regression better captures the quadratic relationship.

🧰 Dependencies

numpy

pandas

matplotlib

seaborn

scikit-learn

Google Colab



polynomial-regression-demo/
│── data/                         # (optional) dataset or generated data
│── notebooks/
│   └── polynomial_regression.ipynb   # main notebook
│── src/
│   ├── data_generation.py        # dataset generation
│   ├── linear_regression.py      # linear regression model
│   ├── polynomial_regression.py  # polynomial regression model
│   └── visualization.py          # plotting utilities
│── requirements.txt
│── README.md
│── .gitignore

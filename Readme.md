# House Price Prediction with Regression Models

This project explores various regression techniques to predict housing prices. 

---


## Models Used & Performance

| Model                   | R² Score        | Performance       |
|------------------------|----------------|-------------------|
| **Multiple Linear Regression** | 0.66            | *Kinda Bad*        |
| **Polynomial Regression**     | -10.30          | *Horrendous*        |
| **Decision Tree Regression**  | 0.31            |  *Very Bad*          |
| **Random Forest Regression**  | 0.55            |  *Still Kinda Bad*   |
| **Support Vector Regression (SVR)** | 0.60      |  *Kinda Bad*        |

> Clearly, we need to look deeper into feature engineering, hyperparameter tuning, or try better data.

---

## Dataset

- Housing dataset with numerical and categorical variables, data taken from Kaggle
- Preprocessing steps: encoding, scaling (especially for SVR), and train/test split

---

## Tools and Libraries

- Python
- NumPy
- Pandas
- Scikit-learn:
  - `LinearRegression`
  - `PolynomialFeatures`
  - `DecisionTreeRegressor`
  - `RandomForestRegressor`
  - `SVR`

---
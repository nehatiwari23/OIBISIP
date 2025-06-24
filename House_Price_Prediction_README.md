
# 🏡 House Price Prediction using Linear Regression

## 📌 Project Overview
This project aims to build a linear regression model to predict house prices based on features like area, number of bedrooms, bathrooms, stories, and various amenities. It demonstrates the complete machine learning workflow from data preparation to model evaluation.

---

## 🗃️ Dataset Overview
- **Total Rows:** 545
- **Target Variable:** `price`
- **Feature Types:**
  - Numerical: `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
  - Categorical (encoded): `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`

---

## 🧼 Data Preprocessing
- Converted `yes/no` and `True/False` values to 1/0
- Applied One-Hot Encoding to categorical variables like `furnishingstatus`
- Defined `X` (features) and `y` (target)

```python
df.replace({'yes': 1, 'no': 0}, inplace=True)
df = pd.get_dummies(df, drop_first=True)
df = df.astype(int)
X = df.drop("price", axis=1)
y = df["price"]
```

---

## 🧠 Model Building
- **Algorithm Used:** Linear Regression
- **Train-Test Split:** 80% train, 20% test

```python
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
model = LinearRegression()
model.fit(X_train, y_train)
```

---

## 📈 Evaluation Metrics
- **Mean Squared Error (MSE):** 1,754,318,687,330.66
- **Root Mean Squared Error (RMSE):** ~1,324,596.33
- **R-squared Score (R²):** 0.65

---

## 📊 Visualization
```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.scatterplot(x=y_test, y=y_pred)
plt.xlabel("Actual Price")
plt.ylabel("Predicted Price")
plt.title("Actual vs Predicted House Prices")
plt.grid(True)
plt.show()
```

---

## 🔧 Future Improvements
- Use the full dataset (all 545 rows)
- Apply polynomial regression or regularization (Ridge/Lasso)
- Explore advanced models like Random Forest or Gradient Boosting

---

## 🎓 Learning Outcomes
- End-to-end ML project experience
- Feature engineering and data cleaning
- Model training, prediction, and evaluation with linear regression

---

**Prepared by:** Neha Tiwari  
**Tools Used:** Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

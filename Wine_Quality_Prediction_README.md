
# 🍷 Wine Quality Prediction – Machine Learning Project

## 📊 Project Summary

This project focuses on predicting the **quality of red wine** based on its **chemical properties** using three classification models:  
- **Random Forest Classifier**  
- **Stochastic Gradient Descent (SGD)**  
- **Support Vector Classifier (SVC)**

---

### 🧪 Dataset Overview
- **Total Samples**: 1,143
- **Features**: 11 (e.g., alcohol, pH, sulphates, density)
- **Target Variable**: Wine Quality (categorized as `Low`, `Medium`, `High`)

---

### ⚙️ Models & Accuracy

| Model              | Accuracy | Best For              |
|-------------------|----------|------------------------|
| Random Forest 🌲   | **66.8%**  | Overall balance ✅     |
| SGD 📉             | 54.1%    | High recall on `High` |
| SVC 🔷             | 58.0%    | Moderate performance  |

---

### ✅ Final Verdict

- **Random Forest** provided the best overall results in accuracy and balanced class prediction.
- **SVC and SGD** showed bias toward `High` quality class and underperformed on `Medium`.

---

### 📌 Tools Used

- Python, Pandas, NumPy, Scikit-learn  
- Seaborn & Matplotlib for visualization  
- SMOTE for balancing class distribution  
- StandardScaler for feature scaling

---

### 📈 Next Steps (Optional)

- Hyperparameter tuning (GridSearchCV)
- Feature importance analysis
- Dashboard visualization (Power BI/Tableau)

---

### 👩‍💻 Author

**Neha Tiwari**  
Aspiring Business Analyst | Data Analyst  
Internships at **Oasis Infobyte** and **Cognifyz Technologies**

> “Transforming raw data into real-world insights—one glass of wine at a time!”

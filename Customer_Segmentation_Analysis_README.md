
# 🛍️ Customer Segmentation Analysis – E-Commerce

This project performs **customer segmentation** using clustering techniques on e-commerce customer data. The goal is to group customers based on their purchasing behavior and demographics to help drive **targeted marketing**, **personalized offers**, and **business growth strategies**.

## 📁 Dataset
The dataset includes:
- Demographics (Age, Income, Marital Status, Education, etc.)
- Product purchases (Wine, Meat, Gold, etc.)
- Purchase channels (Web, Catalog, Store)
- Campaign responses and Recency

## 🚀 Project Steps

1. **Data Loading & Exploration**
   - Shape, structure, and null checks
   - Data type verification

2. **Data Cleaning & Feature Engineering**
   - Removed unnecessary columns
   - Created `MntTotal`, `MntRegularProds`, etc.

3. **Descriptive Statistics**
   - Avg. purchase value, Recency, Campaign response

4. **Clustering (K-Means)**
   - Features scaled using StandardScaler
   - Optimal clusters determined using Elbow Method
   - PCA for dimensionality reduction and visualization

5. **Visualization**
   - Scatter plots, cluster-wise statistics
   - PCA-reduced 2D clustering plots

6. **Insights & Recommendations**
   - Identified 4 clusters:
     - Premium Loyal Shoppers
     - Price-Conscious Families
     - Comfortable Digital Buyers
     - Low-Value Minimalists
   - Tailored marketing and engagement strategies provided

## 📊 Tools & Technologies

- **Python**, **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** for clustering
- **Jupyter Notebook**

## 📌 Key Learning Outcomes

- Practical application of **K-Means clustering**
- Hands-on **data preprocessing** and **feature scaling**
- Business insight generation for **marketing segmentation**
- Use of **PCA** and **visual storytelling** in analysis

---

## 🧠 Insights Preview

| Cluster | Segment                     | Strategy                  |
|---------|-----------------------------|---------------------------|
| 0       | Premium Loyal Shoppers      | Loyalty Programs          |
| 1       | Price-Conscious Families    | Discount Bundles          |
| 2       | Comfortable Digital Buyers  | Personalized Promotions   |
| 3       | Low-Value Minimalists       | Selective Retargeting     |

---

## 📎 Author

**Neha Tiwari**  
Aspiring Business Analyst | Data Enthusiast  
GitHub: [nehatiwari23](https://github.com/nehatiwari23)

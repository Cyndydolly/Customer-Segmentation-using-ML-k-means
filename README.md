# 🛍️ Customer Segmentation using Machine Learning

## 📖 Overview
This project uses **K-Means clustering** to segment mall customers based on their **age**, **annual income**, and **spending score**.  
By identifying similar customer groups, businesses can tailor marketing strategies and improve customer retention.

---

## 📊 Dataset
**Source:** [Mall Customer Segmentation Data on Kaggle]
| Column | Description |
|--------|--------------|
| CustomerID | Unique ID for each customer |
| Gender | Male / Female |
| Age | Age of customer |
| Annual Income (k$) | Customer’s yearly income |
| Spending Score (1–100) | Score assigned based on spending patterns |

---

## ⚙️ Technologies Used
- Python 🐍  
- Pandas & NumPy for data handling  
- Matplotlib & Seaborn for visualization  
- Scikit-learn for clustering (K-Means)

---

## 🚀 Project Workflow
1. Data loading & cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature scaling with `StandardScaler`  
4. Finding optimal K using the **Elbow Method**  
5. Clustering with **K-Means**  
6. Visualization and analysis of customer groups  

---

## 📈 Key Visualizations
| Elbow Method | Cluster Visualization |
|---------------|-----------------------|
| ![Elbow](images/elbow_method.png) | ![Clusters](images/clusters_plot.png) |

---

## 💡 Insights
| Cluster | Description |
|----------|--------------|
| 0 | High-income, high-spending → **Premium Shoppers 💎** |
| 1 | Low-income, low-spending → **Budget Shoppers 💰** |
| 2 | Young, moderate-spending → **Potential Loyalists 🌱** |
| 3 | Older, moderate spenders → **Average Customers 🧺** |
| 4 | Mid-income, selective spenders → **Cautious Buyers 💼** |

---

## 🧠 Results
- Identified **5 distinct customer groups**
- Gained actionable insights for targeted marketing

---


# (Optional) install dependencies
pip install -r requirements.txt

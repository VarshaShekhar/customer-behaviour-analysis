# 🛍️ Consumer Behavior Analysis and Customer Segmentation

This project explores a **consumer behavior dataset** to analyze shopping patterns and segment customers into distinct groups.  
It applies **clustering techniques** and examines **payment preferences, purchase categories, and review ratings** to provide actionable insights for businesses.

---
![Project Thumbnail](consumer_behavior.jpeg)

## 📌 Overview

- **Goal**: Understand customer purchasing behavior and segment them for targeted marketing.  
- **Algorithms**:  
  - K-Means Clustering  
  - Hierarchical Clustering  
  - DBSCAN  
- **Dataset**: Consumer Behavior and Shopping Habits Dataset  
- **Evaluation**: Silhouette Scores for cluster quality  

---

## 🧠 Problem Statement

Businesses need to identify **distinct customer segments** to optimize marketing, inventory, and loyalty strategies.  
This project aims to answer questions such as:  
- Which **payment methods** are most preferred?  
- What are the **popular purchase categories** by gender?  
- How can customers be **grouped based on shopping patterns**?  

---

## 🛠️ Features Used

- **Demographics**: Age, Gender, Location  
- **Purchase Info**: Item Purchased, Category, Purchase Amount, Size, Color, Season  
- **Behavioral Data**: Review Rating, Subscription Status, Shipping Type, Discount Applied, Promo Code Used, Previous Purchases, Payment Method, Frequency of Purchases  

> 🎯 **Target for clustering**: Customer segments based on behavior patterns

---

## ⚙️ Analysis Details

### 🔧 Clustering Methods
| Algorithm | Key Parameter | Result |
|-----------|---------------|--------|
| K-Means  | `n_clusters` determined by Elbow Method | Silhouette Score: 0.363 |
| Hierarchical | `n_clusters` same as K-Means | Silhouette Score: 0.317 |
| DBSCAN | `eps` and `min_samples` tuned | Silhouette Score: -1.0 |

### 🔍 Insights
- **Most preferred payment method**: PayPal  
- **Popular categories by gender**:  
  - Male: Clothing, Footwear  
  - Female: Clothing, Accessories  
- **Average review ratings**: Very similar for both genders (~3.75)  
- **Total distinguishable customer segments**: 4 (from K-Means clustering)  

---

## 📈 Future Improvements

- ✅ Explore **advanced clustering techniques** like Gaussian Mixture Models  
- ✅ Combine **demographics and purchase behavior** for more accurate segments  
- ✅ Build **predictive models** for purchase recommendations  

---

## 📁 Files

- `consumer_behavior_analysis.ipynb` – Jupyter notebook with all code and outputs  
- `consumer_behavior_analysis.html` – Exported version (viewable without running code)  

---

## 🧾 License

This project is for educational purposes only.
Please do not use the dataset for commercial purposes without permission.

---
## 🤝 Connect

- [LinkedIn](https://www.linkedin.com/in/varsha-shekhar)
- [Gmail](varshaiyer96@gmail.com)

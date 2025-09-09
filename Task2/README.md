# Task 2: Customer Segmentation using K-Means

## 📌 Objective
The goal of this task is to segment mall customers into groups based on their **Annual Income** and **Spending Score**.  
This helps businesses design personalized marketing strategies for each customer group.


---

## 🛠️ Technologies Used
- Python 3
- Pandas & NumPy (data handling)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (K-Means clustering, PCA)

---

## 📊 Dataset Information
The dataset `Mall_Customers.csv` contains the following columns:
- **CustomerID** – Unique ID
- **Gender** – Male/Female
- **Age** – Age of the customer
- **Annual Income (k$)** – Annual income in thousands
- **Spending Score (1-100)** – Score assigned by the mall based on spending behavior

---

## 🚀 Steps Performed
1. **Data Exploration** – Checked dataset info, distributions, and missing values.  
2. **EDA** – Visualized income and spending score distributions.  
3. **Feature Selection** – Used `Annual Income` and `Spending Score`.  
4. **Elbow Method** – Determined the best number of clusters (k=5).  
5. **K-Means Clustering** – Applied clustering to group customers.  
6. **Visualization** – Plotted clusters in 2D and using PCA.  
7. **Insights** – Identified customer groups for targeted marketing.

---

Insights
- **Cluster 0:** High income & high spending → Potential Premium Customers.  
- **Cluster 1:** Low income & low spending → Least engaged customers.  
- **Cluster 2:** High income & low spending → Need strategies to increase spending.  
- **Cluster 3:** Average income & average spending → Regular mall visitors.  
- **Cluster 4:** Low income but high spending → Budget shoppers who still spend actively.  

---

## ✅ Conclusion
K-Means successfully segmented customers into **5 distinct groups**, which can help businesses make **data-driven marketing decisions** and allocate resources effectively.

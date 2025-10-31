# portfolio
# Mall Customer Segmentation (K-Means Clustering)

##  Overview
This project analyzes the *Mall Customers Dataset* to understand customer purchasing behavior.  
Using *Exploratory Data Analysis (EDA)* and *K-Means clustering*, customers are grouped into meaningful segments based on:

- Annual Income  
- Spending Score  

The insights can help businesses improve *targeted marketing strategies, **customer profiling, and **business decisions*.

---

## 📂 Dataset Details
*File Name:* Mall_Customers.csv

This dataset contains the following features:

| Column Name | Description |
|------------|-------------|
| *CustomerID* | Unique ID for each customer |
| *Gender* | Male / Female |
| *Age* | Customer age |
| *Annual Income (k$)* | Income in thousands |
| *Spending Score (1–100)* | Assigned score based on customer behavior and spending |

---

##  Project Objectives
- Understand the structure of the dataset  
- Perform data visualization and distribution analysis  
- Apply *K-Means clustering*  
- Identify customer segments  
- Visualize clusters using scatter plots  
- Interpret each cluster for business insights  

---

## Technologies Used
- *Python 3*
- *Pandas*
- *NumPy*
- *Matplotlib*
- *Seaborn*
- *Scikit-learn*
- *Jupyter Notebook*

---

##  Exploratory Data Analysis (EDA)
Key steps include:

- Checking missing values  
- Descriptive statistics  
- Distribution plots  
- Income vs Spending visualizations  
- Correlation analysis  

Various plots help understand customer behavior patterns before clustering.

---

## K-Means Clustering
The following steps were applied:

1. Standardized the numerical features  
2. Used the *Elbow Method* to find the optimal number of clusters  
3. Selected *K = 5*  
4. Trained the K-Means algorithm  
5. Visualized the clusters in 2D  

---

##  Customer Segments Identified

### *Cluster 0 – Low Income, Low Spending (Green)*
- Budget-conscious  
- Minimal purchases  
- Not ideal for premium marketing  

### *Cluster 1 – High Income, High Spending (Orange)*
- Most profitable group  
- Strong spending behavior  
- Ideal for premium and targeted marketing  

### *Cluster 2 – Average Income, Average Spending (Blue)*
- Balanced customers  
- Suitable for general promotions  

### *Cluster 3 – High Income, Low Spending (Purple)*
- Wealthy but less interested  
- Requires engagement strategies to increase spending  

### *Cluster 4 – Low Income, High Spending (Red)*
- Surprisingly high spenders  
- Respond well to offers and loyalty programs  

These clusters help provide clear business insights for customer segmentation.

---

##  Visualization Output
The final plot shows *five color-coded clusters* along with their *centroids* (black stars).  
This provides a clear distinction between different customer groups based on spending score and income.

---

##  How to Run the Project
1. Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

##  
2. Run the jupyter Notebook:

```bash
jupyter notebook

##  
3. open the file:

```bash
Mall_Customer_Clustering.ipynb

##  Result Summary


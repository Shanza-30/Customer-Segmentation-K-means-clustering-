# Customer Segmentation using K-Means

## 📌 Project Overview
This project focuses on grouping customers of a retail store based on their purchasing behavior.  
Using Unsupervised Learning (K-Means), customers are segmented using Annual Income and Spending Score.


## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Apply K-Means clustering
- Use Elbow Method to find optimal clusters
- Visualize customer segments
- Analyze cluster behavior


## 📂 Dataset
Source: Kaggle – Customer Segmentation Tutorial in Python  
Features used:
- Annual Income (k$)
- Spending Score (1–100)


## 🛠 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (KMeans)


## 🔍 Steps Performed
1. Loaded dataset and explored using `head()`, `info()`, `describe()`, `shape`, and `columns`.
2. Checked missing values using `isnull().sum()`.
3. Visualized age distribution and income vs spending score.
4. Selected important features for clustering.
5. Applied Elbow Method to find optimal k.
6. Trained K-Means model.
7. Visualized customer clusters with centroids.
8. Generated cluster summary.


## 📊 Output
- Elbow curve for optimal cluster selection  
- Scatter plot showing customer clusters  
- Cluster-wise summary for analysis  


## 📌 Conclusion
This project successfully segments customers into meaningful groups using K-Means clustering.  
The results can help businesses understand customer behavior and design targeted marketing strategies.

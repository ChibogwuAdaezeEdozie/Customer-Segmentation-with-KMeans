# Customer-Segmentation-with-KMeans
This project applies unsupervised machine learning to segment mall customers into distinct groups based on their Annual Income and Spending Score using the K-Means clustering algorithm.
Dataset
The Mall Customers dataset contains 200 records with the following features: Customer ID, Gender, Age, Annual Income (k$), and Spending Score (1-100).
What Was Done

Exploratory data analysis and visualization of all features
Used the Elbow Method and Silhouette Score to determine the optimal number of clusters (K=5)
Built and fitted a K-Means model
Visualized the resulting customer segments

Results
Five distinct customer segments were identified:
ClusterAnnual IncomeSpending ScoreDescription0AverageAverageTypical customers1HighHighBest customers — high priority for marketing2LowHighImpulsive buyers3HighLowCareful spenders — respond well to promotions4LowLowBudget shoppers

Tools & Libraries
Python Pandas NumPy Matplotlib Scikit-learn

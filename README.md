
# Project Title:
Customer Segmentation Using Unsupervised Learning Techniques

# Project Overview:
This project focuses on segmenting customers for Selore Nigeria, a popular electronics retail chain. The objective is to better understand customer spending behavior and demographics, using unsupervised learning techniques such as K-Means Clustering. The segmented data will help Selore Nigeria develop personalized marketing strategies, optimize pricing, and recommend targeted products.

# Business Context:
Selore Nigeria specializes in selling mobile phones, tablets, laptops, and related accessories from top brands like Samsung, Apple, Nokia, and Huawei. With outlets across Nigeria, the company wants to segment its customers based on purchasing behavior and demographic information to increase customer engagement and sales.

# Dataset:
The dataset used for this project contains 200 customer entries with the following fields:

CustomerID: Unique identifier for each customer.
Gender: The gender of the customer.
Age: The age of the customer.
Annual Income (k$): The annual income of the customer in thousands of dollars.
Spending Score: A score assigned by the retail store based on customer behavior and spending patterns.

# Project Structure:
Customers.csv: Contains the raw data of the 200 customers.
Customer Segmentation Model - Selore Nigeria.ipynb: Jupyter notebook that contains the code for customer segmentation using unsupervised learning.
Customer Segmentation.pdf: Presentation document explaining the project, methodology, and results.

# Approach:
Data Preprocessing: Handling missing values, data normalization, and visualization of trends using matplotlib and seaborn.
Clustering Algorithm: We applied K-Means Clustering to group customers based on their demographic and spending behavior. The optimal number of clusters was determined using the Elbow Method.
Results and Interpretation: The segmented customers were visualized, showing distinct groups that Selore Nigeria can target with specific campaigns.

# Prerequisites:
To run this project, ensure you have the following installed:

Python 3.x
Jupyter Notebook
Libraries: pandas, matplotlib, seaborn, sklearn
You can install the required libraries using pip:


pip install pandas matplotlib seaborn scikit-learn
# How to Run:
Clone the repository from GitHub (instructions below).
Open the Jupyter notebook (Customer Segmentation Model - Selore Nigeria.ipynb).
Run the cells in the notebook to preprocess the data, perform clustering, and visualize the results.
# Results:
The segmentation model successfully grouped customers into distinct clusters. Each cluster represents a set of customers with similar income and spending behaviors. The insights from these clusters will help Selore Nigeria create more personalized and effective marketing campaigns.

# Future Improvements:
Experimenting with different clustering techniques such as Hierarchical Clustering or DBSCAN.
Incorporating additional customer data, such as product preferences or geographical location, to refine the segmentation.

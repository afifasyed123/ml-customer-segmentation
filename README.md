# Customer Segmentation using K-Means Clustering

## Project Overview
This project applies unsupervised machine learning (K-Means Clustering) to segment mall customers into distinct groups based on their annual income and spending score. The goal is to identify patterns for targeted marketing strategies.

## Techniques Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **Machine Learning Algorithm:** K-Means Clustering
- **Methodology:** Elbow Method for optimal cluster selection, data standardization, cluster analysis and visualization.

## Dataset
The dataset (`Mall_Customers.csv`) contains information about customers:
- CustomerID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1-100)

## How to Run
1.  Clone this repository.
2.  Ensure you have Python and Jupyter Notebook installed.
3.  Install the required libraries: `pip install pandas numpy matplotlib scikit-learn`
4.  Open the `customer_segmentation.ipynb` notebook and run all cells.

## Results
The algorithm successfully identified 5 distinct customer segments, which can be categorized as:
- Cluster 0: Low Income, Low Spending
- Cluster 1: High Income, High Spending
- Cluster 2: Low Income, High Spending
- etc. *(Describe what you found!)*

These segments provide valuable insights for developing tailored marketing campaigns.

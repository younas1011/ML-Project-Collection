# Customer Segmentation Using K-Means Clustering
This project uses the K-Means Clustering algorithm to group mall customers based on two key features: Annual Income and Spending Score. The dataset includes demographic and spending information, and clustering helps identify distinct customer groups for marketing strategies.

## What the code does
* Loads the Mall Customers dataset
* Displays first and last rows of the dataset
* Checks dataset size and info
* Identifies categorical and numerical columns
* Checks for missing values
* Selects Annual Income and Spending Score as features
* Computes WCSS values for different cluster sizes
* Plots an elbow graph to choose optimal clusters
* Trains the K-Means clustering model
* Generates cluster labels for all customers
* Visualizes all 5 clusters with different colors
* Plots centroids of clusters

## Steps in the project
1. Import required libraries
2. Load the dataset
3. View first 5 rows
4. View last 5 rows
5. Check dataset size
6. Check dataset info
7. Check for missing values
8. Select relevant features (Annual Income & Spending Score)
9. Compute WCSS values for 1–10 clusters
10. Plot elbow graph to find optimal number of clusters
11. Train K-Means model with 5 clusters
12. Get cluster labels for all data points
13. Visualize clusters on a scatter plot
14. Plot centroids of clusters

## Result
* WCSS plot showing the elbow point
* Optimal number of clusters = 5
* Visual scatter plot showing 5 customer groups
* Centroid positions for each cluster
* Each customer assigned to cluster 0, 1, 2, 3, or 4

## How to run
* Make sure the dataset file (Mall_Customers.csv) is available
* Install required libraries (numpy, pandas, matplotlib, seabor, scikit-learn)
* Run the script in Python / Jupyter Notebook / Google Colab

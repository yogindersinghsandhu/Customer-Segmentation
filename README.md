# Marketing Analytics - Customer Segmentation

## Project Overview

This project applies **KMeans clustering** to perform customer segmentation for marketing analytics. Customer segmentation is essential for identifying different groups of customers based on shared characteristics, allowing businesses to personalize their marketing strategies, improve customer retention, and target high-value customers more effectively.

The Python script processes customer data, applies KMeans clustering to form customer groups, evaluates the model using the silhouette score, and visualizes the resulting clusters.

## Key Features

- **KMeans Clustering**: Groups customers into clusters based on their attributes.
- **Silhouette Score**: Helps determine the optimal number of clusters by measuring the cohesion and separation of the clusters.
- **Data Preprocessing**: Handles missing values, scales features, and selects relevant variables for clustering.
- **Cluster Visualization**: Visualizes the clustering results to help interpret customer segments.

## Project Structure

- **`Marketing Analytics - Customer Segmentation.py`**: The main Python script that runs the entire process of customer segmentation.
- **`README.md`**: This documentation file.

## Dataset

The dataset used in this project contains customer information with several attributes that influence customer behavior. Typical features include:
- **Customer ID**: A unique identifier for each customer.
- **Age**: The age of the customer.
- **Annual Income**: The annual income of the customer.
- **Spending Score**: A score assigned to customers based on their spending habits.

Note: You will need to load your dataset inside the script.

## Dependencies

To run this project, the following Python libraries are required:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required packages via `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

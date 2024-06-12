# mall_customer_segmentation
Mall Customer Segmentation Using KMeans

# Mall Customer Segmentation

This repository contains a data analysis project on mall customer segmentation using K-Means clustering algorithm. In this project, we aim to segment mall customers based on their annual income and spending score.

## Dataset

The dataset used in this project contains information about mall customers, including their CustomerID, Gender, Age, Annual Income, and Spending Score. The dataset has 200 rows and 5 columns.

### Data Columns

1. CustomerID: Unique identifier for each customer.
2. Gender: Gender of the customer.
3. Age: Age of the customer.
4. Annual Income (k$): Annual income of the customer in thousands of dollars.
5. Spending Score (1-100): Score assigned to the customer based on their spending behavior.

## Analysis Steps

1. **Basic Exploration**:
   - Explored the dataset to understand its structure, checked for null values, and examined summary statistics.

2. **Data Preprocessing**:
   - Removed the `CustomerID` column as it was not relevant for analysis.

3. **Visualization**:
   - Visualized the data using scatterplots to explore the relationship between annual income and spending score.

4. **K-Means Clustering**:
   - Utilized the K-Means clustering algorithm to segment customers into distinct clusters based on their similarities.
   - Calculated the within-cluster sum of squares (WCSS) for different numbers of clusters to determine the optimal number of clusters.
   - Observed the elbow point in the WCSS plot to identify the optimal number of clusters.

5. **Visualization of Clusters**:
   - Visualized the clusters by plotting the data points along with their centroids.
   - Each cluster was represented by a different color for easy interpretation.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

## Usage

1. Clone the repository:

```bash
git clone https://github.com/riitk/mall_customer_segmentation.git

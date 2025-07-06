# Customer Segmentation using K-Means Clustering

## Overview
This project demonstrates how to perform customer segmentation using K-Means clustering on mall customer data. The goal is to group customers based on their annual income and spending habits to help businesses create targeted marketing strategies.

## Features
- Data loading and preprocessing
- Visual exploration of customer data
- K-Means clustering implementation
- Optimal cluster selection using:
  - Elbow Method
  - Silhouette Analysis
- Visualization of results
- Business insights generation

## Technologies Used
- Python 3.x
- Libraries:
  - pandas (data manipulation)
  - scikit-learn (machine learning)
  - matplotlib (visualization)
  - numpy (numerical operations)
- Jupyter Notebook (interactive development)

## Setup Instructions

### Prerequisites
- Python 3.x installed
- pip package manager

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation
   ```

##Step-by-Step Work Done
**Data Loading**

* Imported the Mall Customers dataset from CSV

* Checked for missing values (none found)

**Feature Selection**

* Selected relevant features: Annual Income and Spending Score

* Converted data to numpy array for processing

**Data Visualization**

* Created scatter plots to identify natural groupings

* Saved visualizations as PNG files

**K-Means Clustering**

* Implemented K-Means with K=5 as initial guess

* Visualized clusters with centroid markers

**Optimal Cluster Selection**

* Used Elbow Method to determine best K value

* Validated with Silhouette Analysis

* Confirmed K=5 as optimal number of clusters

**Business Insights**

* Analyzed cluster characteristics

* Generated marketing recommendations per cluster

**Errors Faced**

#### Cluster Centroid Misalignment

Centroids appeared in wrong positions

Solution: Used PCA for consistent 2D visualization

## Final Output
Customer segments identified by K-Means

**Key Findings:**

* 5 distinct customer segments identified

* Clear patterns in income vs. spending behavior

* Average silhouette score: 0.55 (good separation)

## Conclusion / Learnings
* Through this project we learned:

* How to prepare data for clustering

* The importance of visualizing data before analysis

* How K-Means algorithm works in practice

* Methods to validate cluster quality

* Translating technical results into business insights

The project successfully demonstrated how machine learning can provide actionable customer segmentation for businesses.

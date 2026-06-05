# Customer Segmentation using Clustering

## Project Overview

This project applies unsupervised machine learning techniques to segment credit card customers based on their financial behavior.


## Dataset

Dataset: Credit Card Customers Dataset

The dataset contains behavioral information about credit card holders, including:

- Balance
- Purchases
- Cash advances
- Credit limit
- Payment behavior
- Purchase frequency
- Installment purchases

Target variable is not available since this is an unsupervised learning problem.

## Project Workflow

### 1. Data Exploration

- Dataset inspection
- Missing value analysis
- Descriptive statistics
- Correlation analysis

### 2. Data Preprocessing

- Missing value treatment
- Feature selection
- Standardization using StandardScaler

### 3. Dimensionality Reduction

Principal Component Analysis (PCA) was applied to:

- Reduce dimensionality
- Remove redundancy
- Improve clustering performance
- Visualize customer groups

### 4. Clustering

Several clustering algorithms can be evaluated:

- K-Means
- Hierarchical Clustering
- DBSCAN
- Spectral Clustering

### 5. Cluster Evaluation

Clustering quality is assessed using:

- Silhouette Score
- 
### 6. Cluster Profiling

Each cluster is analyzed to understand:

- Spending behavior
- Credit usage
- Payment habits
- Customer value

Business labels are assigned to clusters based on their characteristics.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results

The project identifies distinct customer segments that can be used to support CRM and marketing strategies.

Examples of potential segments:

- High-value customers
- Frequent spenders
- Cash advance users
- Low activity customers
- Balanced customers

## Repository Structure

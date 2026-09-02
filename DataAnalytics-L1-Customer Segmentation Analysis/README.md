# Customer Segmentation Using RFM Analysis and K-Means Clustering

## Project Overview

This project focuses on customer segmentation using transactional data. The goal is to identify different groups of customers based on their purchasing behaviour and provide useful insights for business decision-making.

RFM (Recency, Frequency, Monetary) analysis is used to create customer-level features, followed by K-Means clustering to group customers with similar purchasing patterns.

## Objectives

- Analyse customer purchasing behaviour
- Calculate Recency, Frequency, and Monetary values
- Prepare customer-level RFM features
- Standardize the data for clustering
- Determine the suitable number of clusters using the Elbow Method
- Apply K-Means clustering
- Visualize and compare customer segments
- Identify useful business insights from each segment

## Dataset

The project uses an e-commerce transactional dataset containing customer purchase information.

Important fields include:

- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

### 1. Data Loading

The dataset is loaded into Python using Pandas and its structure is examined.

### 2. Data Cleaning

The data is cleaned by:

- Handling missing values
- Removing duplicate records
- Removing invalid transactions
- Checking data types
- Preparing transaction data for analysis

### 3. RFM Analysis

Three important customer metrics are calculated:

- **Recency** – How recently a customer made a purchase
- **Frequency** – How often a customer made purchases
- **Monetary** – How much a customer spent

### 4. Data Standardization

The RFM features are standardized using `StandardScaler` so that the variables can be used effectively for clustering.

### 5. Elbow Method

The Elbow Method is used to determine a suitable number of clusters for the K-Means algorithm.

### 6. K-Means Clustering

K-Means clustering is applied to divide customers into groups with similar purchasing behaviour.

### 7. Cluster Visualization

The resulting customer segments are visualized using charts to understand the differences between the clusters.

### 8. Customer Segment Analysis

Each cluster is analysed based on its RFM characteristics to understand customer behaviour and identify valuable customer groups.

## Key Insights

The segmentation helps identify different types of customers, such as:

- High-value and frequent customers
- Recently active customers
- Customers with lower purchase frequency
- Customers who may require re-engagement

These insights can help businesses improve customer targeting and marketing strategies.

## Conclusion

Customer segmentation using RFM analysis and K-Means clustering provides a practical way to understand customer purchasing behaviour. The identified segments can support targeted marketing, customer retention, and business decision-making.

## Project Files

- `Customer_Segmentation.ipynb` – Jupyter Notebook containing the complete analysis
- `README.md` – Project documentation
- `Screenshots` – Important analysis outputs and visualizations

## Author

**Jeevitha**

## Internship

**Oasis Infobyte (OIBSIP) – Data Analytics Internship**

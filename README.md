# Online Retail Analysis

## Overview
This project performs exploratory data analysis (EDA) and visualization on an online retail dataset. The goal is to uncover key business insights such as sales trends, customer behavior, and product performance using Python and various data analysis tools.

## K-means clustering
K-means algorithm is used to segregate customers into different groups so a suitble strategy can be applied.

<img width="794" height="812" alt="image" src="https://github.com/user-attachments/assets/77d17d9a-f8ac-4035-9cb5-bc4cd07800b4" />

### Customer Segmentation Overview

- This project segments customers into four clusters for targeted engagement strategies:

- Cluster 0 (Blue) – Retain
High-value, regular customers. Focus on retention through loyalty programs, personalized offers, and regular engagement.

- Cluster 1 (Orange) – Re-Engage
Low-value, infrequent buyers who haven’t purchased recently. Focus on re-engagement with targeted campaigns, discounts, and reminders.

- Cluster 2 (Green) – Nurture
Low-value but recent buyers. Focus on nurturing with relationship-building, excellent service, and incentives for more frequent purchases.

- Cluster 3 (Red) – Reward
High-value, frequent buyers. Focus on rewarding loyalty through exclusive offers, recognition, and robust loyalty programs.

## Files
1. **main.ipynb**: The primary Jupyter Notebook containing the data analysis and visualization workflows.
2. **online_retail.xlsx**: The dataset used for the analysis, containing information about transactions, products, customers, and invoices.
3. **requirements.txt**: A list of dependencies required to run the project.

## Libraries Used
- **Python**
- **pandas**: Data manipulation and analysis.
- **matplotlib** and **seaborn**: Data visualization.
- **scikit-learn**: Machine learning for customer segmentation.
- **openpyxl**: Handling Excel files.

## Dataset
The dataset (online_retail.xlsx) includes transactional data with the following columns:
- InvoiceNo: Unique invoice number.
- StockCode: Product code.
- Description: Product description.
- Quantity: The number of items sold.
- InvoiceDate: Date and time of the transaction.
- UnitPrice: Price per unit of the product.
- CustomerID: Unique customer identifier.
- Country: Country of the customer.

## Acknowledgements
Special thanks to the creators of the dataset and the open-source community for the tools used in this project.


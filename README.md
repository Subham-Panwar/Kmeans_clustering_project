# Online Retail Analysis

## Overview
This project performs exploratory data analysis (EDA) and visualization on an online retail dataset. The goal is to uncover key business insights such as sales trends, customer behavior, and product performance using Python and various data analysis tools.

## Files
1. **main.ipynb**: The primary Jupyter Notebook containing the data analysis and visualization workflows.
2. **online_retail.xlsx**: The dataset used for the analysis, containing information about transactions, products, customers, and invoices.
3. **requirements.txt**: A list of dependencies required to run the project.

## Features
- Data cleaning and preprocessing.
- Exploratory data analysis (EDA) with visualizations.
- Sales performance analysis.
- Customer segmentation using machine learning techniques.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/online-retail-analysis.git
   cd online-retail-analysis
   ```
2. Create a virtual environment (optional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
2. Run the cells sequentially to execute the analysis.
3. Modify the code as needed to customize the analysis.

## Technologies Used
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


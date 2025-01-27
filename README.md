# Ecommerce Analysis

## Overview

This assignment involves performing exploratory data analysis (EDA), building predictive models, and deriving actionable insights from an eCommerce Transactions dataset. The dataset consists of three files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. This project evaluates data analysis, machine learning, and business insights generation skills.

### Dataset Links:
- [Customers.csv](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)
- [Products.csv](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)
- [Transactions.csv](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)

## Files Description:

### 1. Customers.csv
- **CustomerID**: Unique identifier for each customer.
- **CustomerName**: Name of the customer.
- **Region**: Continent where the customer resides.
- **SignupDate**: Date when the customer signed up.

### 2. Products.csv
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Product category.
- **Price**: Product price in USD.

### 3. Transactions.csv
- **TransactionID**: Unique identifier for each transaction.
- **CustomerID**: ID of the customer who made the transaction.
- **ProductID**: ID of the product sold.
- **TransactionDate**: Date of the transaction.
- **Quantity**: Quantity of the product purchased.
- **TotalValue**: Total value of the transaction.
- **Price**: Price of the product sold.

## Assignment Tasks:

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
1. Perform exploratory data analysis (EDA) on the provided dataset.
2. Derive at least 5 business insights from the EDA:
    - Write these insights in short point-wise sentences (maximum 100 words per insight).

**Deliverables:**
- A Jupyter Notebook/Python script containing your EDA code.
- A PDF report with business insights (maximum 500 words).

### Task 2: Lookalike Model
Build a Lookalike Model that:
- Takes a user's information as input.
- Recommends 3 similar customers based on their profile and transaction history.
- The model should use both customer and product information.
- Assign a similarity score to each recommended customer.

**Deliverables:**
- Provide the top 3 lookalikes with their similarity scores for the first 20 customers (CustomerID: C0001 - C0020) in `Customers.csv`.
- Form a “Lookalike.csv” which maps `cust_id` to a list of `[cust_id, score]`.
- A Jupyter Notebook/Python script explaining your model development.

**Evaluation Criteria:**
- Model accuracy and logic.
- Quality of recommendations and similarity scores.

### Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques with both profile information (from `Customers.csv`) and transaction data (from `Transactions.csv`).

- You can choose any clustering algorithm and select between 2 and 10 clusters.
- Calculate clustering metrics, including the **Davies-Bouldin Index**.
- Visualize your clusters using relevant plots.

**Deliverables:**
- A report on your clustering results, including:
    - The number of clusters formed.
    - DB Index value.
    - Other relevant clustering metrics.
- A Jupyter Notebook/Python script containing your clustering code.

**Evaluation Criteria:**
- Clustering logic and metrics.
- Visual representation of clusters.

## Installation Instructions

To run this project locally, please follow these steps:

1. **Clone this repository:**
    ```bash
    git clone <repository-url>
    ```

2. **Install required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook:**
    - Open the Jupyter Notebook and run each cell sequentially.
    - Alternatively, you can execute the Python script if you prefer.

## Libraries Used
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For data visualization.
- **seaborn**: For statistical data visualization.
- **scikit-learn**: For machine learning algorithms and clustering.
- **numpy**: For numerical operations.


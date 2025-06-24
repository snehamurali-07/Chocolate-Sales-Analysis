# Chocolate-Sales-Analysis
Data analysis of chocolate sales, focusing on sales trends, product performance, geographic distribution, and salesperson effectiveness.

## Project Overview

This project provides an exploratory data analysis (EDA) of a chocolate sales dataset. The analysis aims to uncover key insights into sales performance, identify patterns and trends over time, evaluate the performance of different products and salespersons, and understand geographical sales distribution. This work showcases data cleaning, preprocessing, and various analytical techniques to derive actionable business intelligence.

## Dataset

The dataset used for this analysis is "Chocolate Sales", typically found on Kaggle. It contains transactional data for chocolate sales with the following columns:

* `Sales Person`: The individual responsible for the sale.
* `Country`: The country where the sale occurred.
* `Product`: The specific chocolate product sold (e.g., Mint Chip Choco, 85% Dark Bars).
* `Date`: The date of the transaction.
* `Amount`: The revenue generated from the sale.
* `Boxes Shipped`: The quantity of chocolate boxes sold.

**Kaggle Dataset Link:** [https://www.kaggle.com/datasets/atharvasoundankar/chocolate-sales](https://www.kaggle.com/datasets/atharvasoundankar/chocolate-sales)

## Analysis Objectives & Key Questions Addressed

This analysis addresses several core questions, including:

* **Overall Sales Performance:** Calculating the total revenue generated and the total quantity of chocolate sold across the entire dataset.
* **Average Price Analysis:** Determining the overall average price per unit and analyzing how this price varies across different products.
* **Product Performance:** Identifying the top-performing products by total quantity and revenue.
* **Salesperson Performance:** Ranking salespersons based on their total revenue and quantity of boxes shipped.
* **Geographic Sales:** Understanding which countries contribute most to sales revenue and quantity.
* **Temporal Trends:** (Implied analysis, though not explicitly shown in snippets, often a part of this dataset's analysis) Exploring sales trends over time to identify seasonality or significant sales periods.

## Technologies Used

* **Python**
* **Pandas:** For efficient data manipulation and analysis.
* **NumPy:** For numerical operations, often used in conjunction with Pandas.
* **Matplotlib:** For creating static, high-quality visualizations.
* **Seaborn:** For generating informative and attractive statistical graphics, built on Matplotlib.

## How to Run the Analysis

To replicate this analysis on your local machine:

1.  **Clone the repository:**
    ```
    git clone https://github.com/snehamurali-07/Chocolate-Sales-Analysis.git
    cd Chocolate-Sales-Analysis
    ```
2.  **Create a virtual environment (recommended):**
    ```
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```
3.  **Install the required libraries:**
    ```
    pip install pandas numpy matplotlib seaborn
    ```
4.  **Download the Dataset:**
    Download the `Chocolate Sales.csv` file from the Kaggle link provided above and place it in the same directory as the `Chocolate Sales Analysis.ipynb` notebook.
5.  **Open and Run the Jupyter Notebook:**
    Launch Jupyter Notebook or JupyterLab from your terminal:
    ```
    jupyter notebook
    ```
    Then, open `Chocolate Sales Analysis.ipynb` and run all cells to execute the analysis.

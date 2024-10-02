

## **ETFs Data Analysis and Manipulation**
### **Introduction**
This repository contains a data analysis task focusing on Exchange-Traded Funds (ETFs). The analysis demonstrates various data manipulation techniques using **Pandas** and **scikit-learn**. This task is structured to meet all the requirements provided, ensuring data cleaning, reshaping, and aggregation practices, while also handling missing values with advanced imputation techniques.

### **Dataset**
*The dataset is retrieved from Kaggle: [US Funds dataset from Yahoo Finance](https://www.kaggle.com/datasets/stefanoleone992/mutual-funds-and-etfs)*


The dataset used in tasks contains detailed information about various Exchange-Traded Funds (ETFs). Each row represents an individual ETF, with columns providing details about its characteristics, performance metrics, and categorization. The key attributes include:

- **fund_symbol**: The ticker symbol representing the ETF.
- **quote_type**: The type of the financial instrument (e.g., ETF).
- **region**: Geographical region where the ETF is traded.
- **fund_short_name / fund_long_name**: The abbreviated and full name of the fund.
- **currency**: The currency in which the ETF is traded (e.g., USD).
- **fund_category**: Categorization of the fund, such as sector or asset class.
- **fund_family**: The organization managing the ETF (e.g., Virtus, American Century).
- **exchange_code / exchange_name**: Code and name of the exchange where the ETF is listed (e.g., NYSEArca).
- Performance Metrics

   (for 5 and 10-year periods):

  - **fund_stdev**: Standard deviation of the fund's returns (a measure of volatility).
  - **fund_sharpe_ratio**: The risk-adjusted return.
  - **fund_alpha**: Measure of the fund's active return on investment.
  - **fund_beta**: Sensitivity to market movements.
  - **fund_r_squared**: Percentage of fund movement explained by the benchmark index.
  - **fund_mean_annual_return**: The average annual return.
  - **fund_treynor_ratio**: A measure of return relative to systematic risk.

This dataset has 142 columns that provide extensive information about the performance and characteristics of various ETFs.

### **Task Requirements**
This project fulfills the following requirements:
- Inspecting the dataframe (`df.head()`, `df.tail()`, `df.info()`, `df.describe()`).
- Handling missing values and introducing new ones for demonstration.
- Modifying Pandas display options using `pd.set_option()`.
- Renaming columns and modifying indexes.
- Reshaping dataframes using `df.melt()` and `df.pivot()`.
- Combining datasets using `df.merge()` and `pd.concat()`.
- Applying functions using `df.apply()` and `df.applymap()`.
- Querying specific data using `df.query()`.
- Performing groupby and aggregation operations.
- Removing or filling missing values (`df.dropna()`, `df.fillna()`).
- Implementing imputation using `SimpleImputer` from `scikit-learn`.
- Cleaning text data using regex.


### **Key Features**
- **Data Inspection**: Methods to inspect and understand the structure of the dataset.
- **Missing Data Handling**: Demonstrates multiple strategies for handling missing data (dropping, filling, imputing).
- **Data Reshaping**: Utilizes Pandas for reshaping (pivoting, melting).
- **Combining Data**: Showcases how to merge and concatenate multiple datasets.
- **Text Data Cleaning**: Uses regex to clean and sanitize text fields.
- **Scikit-learn Integration**: Implements the `SimpleImputer` for advanced imputation tasks.

### **Installation**
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/RLirri/Etfs-Data-Analysis.git
   ```

2. Navigate to the project directory, install the required dependencies::

   ```bash
   pip install pandas, numpy, scikit-learn
   ```

# Accounts & Branch Performance Dashboard

## Overview

This Power BI dashboard project provides a comprehensive analysis of account balances, interest rates, and branch performance within a financial institution. The dashboards are designed to give insights into customer segmentation, account performance across various branches, and key metrics such as average balance and interest rates.

## Features

### 1. **Accounts Dashboard**
   - **Total Accounts:** Displays the total number of accounts in the dataset.
   - **Max Balance & Average Balance:** Highlights the highest account balance and the average balance across all accounts.
   - **Mean Interest Rate by Balance Category:** Shows the average interest rate applied across different balance categories (Silver, Bronze, Platinum, Gold).
   - **Mean Balance and Max Balance by Balance Category:** Compares the mean and maximum balances across different balance categories, providing insights into the distribution of funds.
   - **Customers per Balance Category & Interest Category:** Pie charts illustrating the distribution of customers based on their balance and interest rate categories.

### 2. **Branches Performance Dashboard**
   - **Number of Customers in Each Category:** Displays the number of customers segmented by balance and interest categories across different branches.
   - **Mean and Max Balance by Branch:** Compares the mean and maximum balances for each branch, highlighting performance differences.
   - **Current Performance (Gauges):** Shows the ratio of average to maximum balance and interest, providing a quick overview of branch performance.
   - **Number of Accounts by Branch:** A donut chart visualizing the distribution of accounts across various branches.

## Data

The dataset includes the following fields:
- `accountID`: Unique identifier for each account.
- `accountTypeCode`: Code representing the type of account.
- `customerID`: Unique identifier for each customer.
- `balance`: The balance of the account.
- `interestRate`: The interest rate applied to the account.
- `branchCode`: Code representing the branch where the account is held.
- `Interest Rate Category`: Categorization of interest rates (e.g., Low, Mid, High).
- `Balance Category`: Categorization of balances (e.g., Bronze, Silver, Gold, Platinum).
- `Earned Interest`: The interest earned on the account.

## Project Highlights

- **Data Segmentation:** The dataset was segmented by balance categories and interest rate categories to better understand customer distribution and account performance.
- **Branch Performance Analysis:** The dashboard enables a detailed comparison of branch performance based on key metrics such as mean and maximum balances.
- **Customer Insights:** Visualization of customer distribution across different balance and interest categories helps in identifying key customer segments.

## Usage

1. **Exploration:** Use the interactive features of the dashboards to explore different aspects of account and branch performance.
2. **Decision-Making:** Leverage insights from the dashboard to make data-driven decisions, such as identifying high-performing branches or understanding customer segmentation.
3. **Performance Monitoring:** Track key performance indicators like average balance, interest rates, and the number of accounts to monitor the financial health of the institution.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yehiaz2409/Bank-Progress-Dashboard.git
2. **Open Power BI:**
   - Import the `.pbix` file from the cloned repository.
   - Explore the dashboard by interacting with the visualizations.

3. **Data Refresh:**
   - Ensure that the dataset is updated with the latest account information for accurate analysis.

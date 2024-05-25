# Data-Science-Project
# Customer Segmentation and Revenue Insights for a Retail Business

## Introduction

This project focuses on analyzing customer behavior and revenue insights using a dataset from a retail company. The primary objective is to understand the dataset, clean it, and employ clustering techniques to segment customers based on their buying behavior. Customer segmentation helps the company tailor its marketing strategies, understand customer preferences, and improve overall business performance.

## Table of Contents

- [Modules Used](#modules-used)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [Data Set Link](#data-set-link)
- [Report Link](#report-link)

## Modules Used

1. **Data Cleaning (STEP 1):**
   - Handle missing values
   - Identify and remove canceled invoices
   - Perform other data preprocessing tasks

2. **Feature Extraction (STEP 2):**
   - Extract date-related information
   - Calculate total price
   - Measure description length

3. **RFM Analysis (STEP 3):**
   - Calculate Recency, Frequency, and Monetary (RFM) metrics for each customer
   - Use RFM metrics for customer segmentation and behavior analysis

4. **Exploratory Data Analysis (EDA):**
   - Visualize revenue by country, month, and day of the week
   - Identify top customers by revenue

5. **Market Basket Analysis (Optional):**
   - Identify associations between products often purchased together
   - Improve product recommendations and sales strategies

6. **Customer Segmentation (Clustering):**
   - Use K-means clustering to segment customers based on their behavior
   - Group customers into distinct clusters

7. **Outlier Detection (Optional):**
   - Identify and remove outliers from the dataset

8. **Customer Lifetime Value (CLV):**
   - Calculate Customer Lifetime Value for each customer
   - Gain insights into the long-term value of customers

## Visualizations

1. **Scatter Plot for UnitPrice by Quantity:**
   ![UnitPrice by Quantity](plots/scatter_plot_quantity_unitprice.png)

2. **Line Plot for Revenue by InvoiceDate:**
   ![Revenue by InvoiceDate](plots/line_plot_revenue_invoicedate.png)

3. **Bar Plot of CLV by Customer:**
   ![CLV by Customer](plots/bar_plot_clv_customer.png)

4. **Scatter Plot for CLV vs. Average Order Value:**
   ![CLV vs. Average Order Value](plots/scatter_plot_clv_avgorder.png)

5. **Distribution of TotalPrice (After Removing Outliers):**
   ![Distribution of Total Price](plots/hist_totalprice_after_outliers.png)

6. **Revenue by Country:**
   ![Revenue by Country](plots/bar_plot_revenue_country.png)

7. **Revenue by Month:**
   ![Revenue by Month](plots/bar_plot_revenue_month.png)

8. **Revenue by Day of the Week:**
   ![Revenue by Day of the Week](plots/bar_plot_revenue_dayofweek.png)

9. **Top 10 Customers by Revenue:**
   ![Top 10 Customers by Revenue](plots/bar_plot_top10_customers.png)

10. **3D Scatter Plot of Clusters:**
    ![3D Scatter Plot of Clusters](plots/3d_scatter_plot_clusters.png)

## Conclusion

In conclusion, this data analysis project has provided valuable insights into customer
behavior and revenue patterns for the retail business. By cleaning the data and removing
missing values, we ensured the accuracy and reliability of the dataset. Overall, this
project has provided actionable insights for the retail business, allowing for informed
decision-making, tailored marketing strategies, and improved customer relationship
management. By understanding customer behavior, identifying high-value customers,
and analyzing revenue patterns, the business can enhance its performance, increase
revenue, and foster long-term customer loyalty.
The relevance of this work lies in its ability to provide actionable insights for the retail
business, including tailored marketing strategies based on RFM segments, identification
and retention of high-value customers through CLV analysis, accurate insights by
removing outliers, and understanding revenue patterns for improved decision-making
and targeted marketing campaigns.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.

## Data Set Link
https://drive.google.com/file/d/18mM7Fq3tqtJHq9wBGaF8E6pyuIgY4-fq/view?usp=drive_link

## Report Link
https://drive.google.com/file/d/1irrAhszVys2Pd9qgnMTQXNBHxx6mFzA_/view?usp=drivesdk

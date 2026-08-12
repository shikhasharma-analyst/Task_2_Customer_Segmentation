# Customer Segmentation using RFM Analysis and K-Means

## Project Overview

This project focuses on customer segmentation using retail sales data. 
The analysis uses RFM (Recency, Frequency, Monetary) analysis and K-Means 
clustering to identify different customer groups and generate business insights.

## Objectives

- Analyze retail customer purchasing behavior
- Calculate Recency, Frequency, and Monetary metrics
- Identify meaningful customer segments
- Use K-Means clustering for customer segmentation
- Visualize and compare customer segments
- Provide business recommendations for each segment

## Dataset

The dataset contains retail transaction information including:

- Transaction ID
- Sale Date
- Sale Time
- Customer ID
- Gender
- Age
- Category
- Quantity
- Price per Unit
- COGS
- Total Sale

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

### 1. Data Loading and Inspection

The retail sales dataset was loaded using Pandas and inspected for:
- Dataset dimensions
- Column names
- Data types
- Missing values
- Duplicate records

### 2. Data Cleaning

Missing numerical values were handled and the dataset was prepared 
for further analysis.

### 3. RFM Analysis

Customer behavior was analyzed using three important metrics:

- **Recency:** Number of days since the customer's last purchase
- **Frequency:** Number of purchases made by the customer
- **Monetary:** Total amount spent by the customer

### 4. K-Means Clustering

K-Means clustering was applied to the RFM metrics.

The Elbow Method was used to determine an appropriate number of clusters.

### 5. Customer Segmentation

The resulting clusters were interpreted into meaningful business segments.

## Customer Segments

| Customer Segment | Customers |
|---|---:|
| New / Low Value Customers | 77 |
| Potential Loyal Customers | 56 |
| At Risk Customers | 17 |
| High Value Loyal Customers | 5 |

## Cluster Profiles

| Segment | Recency | Frequency | Monetary |
|---|---:|---:|---:|
| At Risk Customers | 352.00 | 6.00 | 2790.88 |
| High Value Loyal Customers | 10.20 | 71.40 | 29694.00 |
| New / Low Value Customers | 56.36 | 8.53 | 3289.74 |
| Potential Loyal Customers | 24.38 | 15.79 | 8266.88 |

## Business Recommendations

### High Value Loyal Customers
These customers have high purchase frequency and high monetary value.

**Recommendation:** Provide loyalty rewards, exclusive offers, and premium services.

### Potential Loyal Customers
These customers show good purchasing activity and can potentially become loyal customers.

**Recommendation:** Use personalized offers, loyalty programs, and targeted promotions.

### At Risk Customers
These customers have not purchased recently.

**Recommendation:** Use reactivation campaigns, discounts, and personalized reminders.

### New / Low Value Customers
These customers have relatively low purchase frequency and monetary value.

**Recommendation:** Use introductory offers, product recommendations, and engagement campaigns.

## Key Insights

Customer segmentation can help businesses:

- Understand customer purchasing behavior
- Improve customer retention
- Personalize marketing campaigns
- Identify high-value customers
- Reactivate customers who may be at risk
- Improve marketing resource allocation

## Project Files

- `Customer_Segmentation.ipynb` – Complete Python analysis and visualizations
- `Customer_Segmentation_Final.csv` – Final customer segmentation dataset
- `Retail_Sales.csv` – Retail sales dataset

## Conclusion

The project demonstrates how RFM analysis and K-Means clustering can be 
used to segment customers based on purchasing behavior. These segments 
can support personalized marketing strategies, customer retention, 
and better business decision-making.

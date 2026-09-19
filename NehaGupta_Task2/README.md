# Customer Segmentation Analysis

## Objective

The objective of this project is to segment an e-commerce company's customers into distinct groups based on their purchasing behaviour using RFM analysis and K-Means clustering.

## Dataset

The Online Retail dataset was used for this analysis.

The dataset contains online retail transaction records with information such as:
- Invoice Number
- Stock Code
- Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

The following data-cleaning steps were performed:

- Removed records with missing Customer ID.
- Removed records with missing Description.
- Removed duplicate records.
- Removed transactions with negative or zero Quantity.
- Removed transactions with zero or negative Unit Price.

## RFM Analysis

Three behavioural features were selected for customer segmentation:

- Recency – Number of days since the customer's last purchase.
- Frequency – Number of unique invoices/purchases made by the customer.
- Monetary – Total amount spent by the customer.

The RFM features were standardized using StandardScaler before clustering.

## K-Means Clustering

The Elbow Method was used to determine a suitable number of clusters.

Based on the Elbow Method, 4 clusters were selected for the analysis.

## Cluster Profiles

### Cluster 0

The largest customer segment with moderate recency, frequency, and monetary value.

### Cluster 1

Customers with high recency, low purchase frequency, and low monetary value.

### Cluster 2

A very small segment with very low recency, extremely high purchase frequency, and extremely high monetary value.

### Cluster 3

Customers with low recency, relatively high purchase frequency, and high monetary value.

## Marketing Actions

- Cluster 0: Provide personalized recommendations and offers to encourage repeat purchases.
- Cluster 1: Use re-engagement emails, reminders, and special discounts.
- Cluster 2: Provide loyalty rewards and personalized offers to retain high-value customers.
- Cluster 3: Focus on customer retention through loyalty programs and premium offers.

## Key Insights

- RFM analysis identified four distinct customer groups.
- Cluster 0 is the largest segment.
- Cluster 1 contains less recently active customers with lower purchase activity.
- Cluster 2 contains a very small number of highly valuable and frequent customers.
- Cluster 3 contains active and valuable customers.
- Different customer segments can be targeted with different marketing strategies.

## Customer Value Note

Total Spend represents the historical customer value during the observed dataset period. It is used as a customer value proxy for this analysis. A true predictive Customer Lifetime Value would require additional assumptions about future purchases, retention, profit margin, and discounting.

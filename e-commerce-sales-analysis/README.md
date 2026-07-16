# E-commerce Sales Analysis

[View the Jupyter Notebook](./Sales_Forecasting.ipynb)

## 📊 Dataset
- **Source:** [Kaggle / Company Database]
- **Description:** A transactional dataset containing purchases made across an e-commerce platform over the period of one year. Includes features like `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, and `Country`.
- **Size:** [Number of rows] rows x [Number of columns] columns.

## 🔬 Methodology
1. **Data Cleaning:** Removed cancelled orders, handled missing Customer IDs, and formatted datetime columns.
2. **Feature Engineering:** Extracted `Month`, `Day of Week`, and `Hour` from `InvoiceDate`. Calculated total spending per transaction.
3. **Exploratory Data Analysis (EDA):** Visualized sales trends over time, top-selling products, and geographic distribution of customers.
4. **Cohort Analysis / RFM:** Conducted Recency, Frequency, and Monetary (RFM) analysis to segment customers into different behavioral groups.

## 🏆 Hasil (Results)
- **Key Trends:** Discovered a 20% spike in overall sales during the Q4 holiday season.
- **Customer Segmentation:** Identified a 'Champion' customer segment that contributes to 40% of the total revenue.
- **Actionable Recommendation:** Proposed targeted email marketing campaigns for the 'At Risk' customer segment, potentially recovering 10% of lost sales.

## Project Objective
Segment customers based on their purchase behavior using RFM (Recency, Frequency, Monetary) and K-Means Clustering.

---

## Business Problem
The business wants to create customer groups for targeted marketing, but currently lacks data-driven segmentation. This project helps identify high-value, at-risk, and frequent buyers to improve campaign ROI.

---

## Dataset Information

**Data Source:** UCI Online Retail Dataset  
**File Used:** `online_retail_sample.csv`

| Column Name   | Data Type | Description                             |
|---------------|-----------|-----------------------------------------|
| InvoiceNo     | object    | Unique ID per transaction               |
| StockCode     | object    | Product/item code                       |
| Description   | object    | Product name                            |
| Quantity      | int       | Number of units purchased               |
| InvoiceDate   | datetime  | Date and time of purchase               |
| UnitPrice     | float     | Price per unit                          |
| CustomerID    | float     | Unique ID for each customer             |
| Country       | object    | Country of the customer                 |

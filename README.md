# 🛒 UK Store Sales Analysis

This project performs an in-depth exploratory and statistical analysis of retail sales data from a UK-based store. It uncovers customer behavior, revenue trends, and product performance using Python and its data analysis ecosystem.

---

## 📦 Dataset Overview

The dataset contains transactional sales data including:

- `InvoiceNo`: Invoice number for each transaction
- `StockCode`: Product/item code
- `Description`: Product name
- `Quantity`: Number of items purchased
- `InvoiceDate`: Date of purchase
- `UnitPrice`: Price per item
- `CustomerID`: Unique identifier for each customer
- `Country`: Country of the customer (primarily United Kingdom)


---

## 🎯 Objectives

- Clean and preprocess the dataset
- Analyze revenue trends over time
- Segment customers based on spending behavior
- Identify high-performing products and categories
- Visualize key KPIs using Python

---

## 🛠️ Tools & Libraries Used

- **Python 3.x**
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `scipy.stats` – Statistical testing
- `jupyter` – Interactive notebook

---

## 🔍 Key Steps in Analysis

1. **Data Cleaning**
   - Handling missing values in `CustomerID`
   - Removing canceled orders (InvoiceNo starts with 'C')
   - Filtering records for United Kingdom only

2. **Feature Engineering**
   - Calculating `TotalPrice = Quantity × UnitPrice`
   - Extracting time features like Month, Weekday

3. **Revenue Analysis**
   - Monthly revenue trends
   - Top-selling products and revenue contribution

4. **Customer Analysis**
   - Unique customers by month
   - Repeat vs. new customer ratio



---

## 📊 Sample Visuals

- Revenue trends by month
- Top 10 selling products
- Customer segments based on RFM scores
- Distribution of order value and frequency

> 📌 *You can find these charts inside the notebook and dashboard folder.*

---

## 💡 Key Insights

- Most sales occur in **November and December**, indicating a holiday peak.
- A small number of products drive the **majority of revenue**.
- RFM analysis reveals a **loyal core customer group** worth targeting with promotions.
- Majority of canceled transactions were associated with large-quantity orders.

---

## 📁 Project Structure


# 🛒 Supermarket Sales Dashboard

An interactive **Power BI dashboard** developed to analyze supermarket sales performance, product-line performance, customer purchasing behavior, branch-level performance, payment methods, and customer ratings.

The dashboard transforms supermarket transaction data into an interactive business intelligence solution using **Power BI, DAX, Power Query, and data visualization techniques**.

---

## 📊 Dashboard Overview

The **Supermarket Sales Dashboard** consists of four analytical pages:

1. **Overview**
2. **Products**
3. **Customers**
4. **Details**

The report provides interactive filtering and KPI analysis across sales, transactions, profit, ratings, products, customers, branches, payment methods, and time periods.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall supermarket sales performance
- Monitor total sales and transaction volume
- Analyze sales performance across branches
- Identify sales trends over time
- Analyze payment-method preferences
- Evaluate product-line performance
- Compare product-line sales and transaction volumes
- Analyze customer purchasing behavior
- Compare sales between customer types
- Analyze sales by gender
- Compare customer ratings across branches and product lines
- Provide detailed transaction-level information
- Enable interactive business analysis through Power BI filters

---

# 📑 Dashboard Pages

## 1. Overview

The **Overview** page provides a high-level summary of supermarket performance.

### Key KPIs

The page contains four primary KPI cards:

- **Total Sales**
- **Transactions**
- **Profit**
- **Average Rating**

### Visualizations

#### Sales by Branch

A **Clustered Bar Chart** showing Total Sales by Branch.

This allows users to compare the sales performance of different supermarket branches.

#### Sales by Time Period

A **Clustered Column Chart** showing Total Sales by Time Period.

This provides a view of sales performance across different periods of the day.

#### Sales by Payment Method

A **Donut Chart** showing Total Sales by Payment Method.

This helps identify customer payment preferences.

#### Weekly Sales Trend

An **Area Chart** showing Total Sales by Sales Week.

This allows users to observe changes in sales performance over the weeks.

### Filters

The Overview page provides interactive slicers for:

- Sales Month
- Gender
- Customer Type

---

## 2. Products

The **Products** page focuses on product-line performance.

### Key KPIs

The page contains:

- **Total Sales**
- **Transactions**
- **Profit**
- **Average Rating**

### Visualizations

#### Transactions by Product Line

A **Clustered Column Chart** showing the number of Transactions by Product Line.

This allows comparison of transaction volume across product categories.

#### Sales by Product Line

A **Clustered Bar Chart** showing Total Sales by Product Line.

This identifies product lines contributing the most to overall sales.

#### Average Rating by Product Line

A **Clustered Column Chart** showing Average Rating by Product Line.

This enables comparison of customer ratings across product categories.

### Filters

The Products page contains slicers for:

- Sales Month
- Customer Type
- Gender

These allow product performance to be analyzed for different customer groups and time periods.

---

## 3. Customers

The **Customers** page focuses on customer-related sales analysis.

### Key KPIs

The page contains:

- **Total Sales**
- **Transactions**
- **Profit**
- **Average Rating**

### Visualizations

#### Sales by Gender

A **Pie Chart** showing Total Sales by Gender.

This provides a comparison of sales contributions from different genders.

#### Sales by Customer Type

A **Clustered Column Chart** showing Total Sales by Customer Type.

This allows comparison between different customer categories.

#### Average Rating by Branch

A **Clustered Column Chart** showing Average Rating by Branch.

This helps compare customer ratings across supermarket branches.

### Filters

The Customers page provides slicers for:

- Sales Month
- Customer Type
- Gender

---

## 4. Details

The **Details** page provides a transaction-level view of the supermarket sales data.

### Key KPIs

The page contains:

- **Total Sales**
- **Transactions**
- **Profit**
- **Average Rating**

### Detailed Transaction Table

The Details page contains a table with the following fields:

- Invoice ID
- Branch
- City
- Customer Type
- Payment
- Total Sales
- Date
- Product Line
- Average Rating

This provides a more granular view of the underlying supermarket transactions.

### Filters

The Details page provides slicers for:

- Gender
- Sales Month
- Customer Type

The page also contains report-level filtering related to:

- Time Period
- Total Sales
- Product Line
- Branch

---

# 📊 Key Performance Indicators

The dashboard uses four main analytical measures throughout the report:

| KPI | Description |
|---|---|
| **Total Sales** | Overall sales/revenue generated |
| **Transactions** | Number of supermarket transactions |
| **Profit** | Gross profit/income generated |
| **Average Rating** | Average customer rating |

These KPIs are consistently presented across the dashboard pages to provide a common performance view.

---

# 📈 Analytical Dimensions

The dashboard analyzes supermarket performance across the following dimensions:

### 🏪 Branch

Sales performance and customer ratings are compared across branches.

### 🏙️ City

The detailed transaction view includes city-level information.

### 🛍️ Product Line

Product lines are analyzed based on:

- Transactions
- Total Sales
- Average Rating

### 👥 Customer Type

Sales performance is compared across customer types.

### ⚥ Gender

Sales performance can be analyzed by gender.

### 💳 Payment

Total Sales are analyzed by payment method.

### 📅 Date & Time

Sales are analyzed through:

- Date
- Sales Month
- Sales Week
- Time Period

### ⭐ Customer Rating

Average customer ratings are analyzed overall, by product line, and by branch.

---

# 🔄 Data Analysis Workflow

The project follows a typical business intelligence workflow:

```text
Supermarket Transaction Data
            ↓
      Data Preparation
            ↓
      Data Transformation
            ↓
       Data Modeling
            ↓
      DAX Measures
            ↓
    Interactive Visualizations
            ↓
      Business Analysis
```
# 🧮 Power BI Measures

The report uses dedicated measures for its core KPIs, including:

- **Total Sales**
- **Transactions**
- **Profit**
- **AVG Rating**

These measures are used throughout the four dashboard pages to maintain consistent KPI calculations.

> The PBIX report references these measures directly throughout its visuals.

---

# 🗂️ Main Data Fields

The dashboard uses the following fields in its analysis and detailed reporting:

### Transaction Information

- Invoice ID
- Date
- Time

### Store Information

- Branch
- City

### Customer Information

- Customer Type
- Gender

### Product Information

- Product Line

### Payment Information

- Payment

### Performance Metrics

- Total Sales
- Transactions
- Profit
- Average Rating

### Time Analysis Fields

- Sales Month
- Sales Week
- Time Period

---

# 🎛️ Interactive Features

The dashboard provides interactive analysis through:

- Slicers
- Dropdown filters
- Cross-filtering
- KPI cards
- Interactive charts
- Page navigation
- Detailed transaction table via drill-through

Users can combine filters such as **Sales Month + Customer Type + Gender** to investigate specific segments of supermarket performance.

---

# 💡 Business Questions Addressed

The dashboard can be used to answer questions such as:

### Sales

- What is the overall sales performance?
- Which branch generates the highest sales?
- How do sales change across time periods?
- How does sales performance change week by week?

### Products

- Which product line has the highest sales?
- Which product line generates the most transactions?
- Which product line receives the highest customer ratings?

### Customers

- Which gender contributes more to sales?
- How do different customer types compare in sales?
- Which branch has the highest average customer rating?

### Payments

- Which payment method contributes the most to sales?

### Transactions

- What are the details of individual transactions?
- Which branch, city, product line, customer type, and payment method are associated with each transaction?

---

# 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **Business Intelligence**

---

# 📌 Project Highlights

- ✅ 4-page interactive Power BI report
- ✅ Sales performance analysis
- ✅ Branch-level sales analysis
- ✅ Product-line performance analysis
- ✅ Customer behavior analysis
- ✅ Gender-based sales analysis
- ✅ Customer-type analysis
- ✅ Payment-method analysis
- ✅ Weekly and time-period sales analysis
- ✅ Customer rating analysis
- ✅ Transaction-level detail analysis
- ✅ Interactive slicers and filtering
- ✅ KPI-based business reporting

---

# 📷 Dashboard Pages

## 📊 Dashboard Preview

### Overview

![Overview Dashboard](Screenshots/overview.png)

### Products

![Products Dashboard](Screenshots/products.png)

### Customers

![Customers Dashboard](Screenshots/customers.png)

### Details

![Details Dashboard](Screenshots/details.png)

---

# 🎓 Project Context

This project was developed as a **Power BI dashboard project** to demonstrate the practical application of data analytics and business intelligence techniques to supermarket transaction data.

The project demonstrates the ability to transform transactional data into an interactive analytical dashboard that supports business performance monitoring and data-driven decision-making.

---

# 👨‍💻 Author

## Saranga Rathnayaka

**BSc in Industrial Statistics and Mathematical Finance**  
University of Colombo


---

⭐ **If you find this project useful, feel free to explore the repository and connect with me.**




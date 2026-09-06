# 📱 Mobile Sales Performance & Customer Analytics Dashboard

> **Interactive Power BI analytics solution for evaluating mobile sales performance, product demand, customer satisfaction, payment behavior, geographic performance, and time-based sales trends.**

![Mobile Sales Dashboard](dashboard.png)

---

## 📌 Executive Summary

This project analyzes mobile sales transactions across multiple brands, mobile models, cities, payment methods, customer ratings, and time periods to identify the factors shaping overall sales performance.

The analysis combines **Power Query data transformation, dimensional data modeling, DAX measures, and interactive Power BI reporting** to convert transactional data into a management-oriented sales analytics solution.

The dashboard provides visibility into:

- Overall sales and transaction performance
- Brand and mobile-model contribution
- Monthly, quarterly, yearly, and daily sales patterns
- Month-to-date performance
- Same-period-last-year comparisons
- Geographic sales distribution
- Payment-method behavior
- Customer rating distribution
- Quantity trends
- Product-level sales concentration

### Business Outcome

The analysis provides a single interactive view through which decision-makers can identify **which products and brands are driving revenue, where sales are concentrated, how demand changes over time, and where customer experience may require attention.**

---

# 📊 Key Results

The full-period dashboard reports:

| KPI | Result |
|---|---:|
| **Total Sales** | **$769.20M** |
| **Total Quantity Sold** | **19,150** |
| **Total Transactions** | **3,835** |
| **Average Price** | **$40.11K** |

These results establish the overall scale of the analyzed sales portfolio and provide the baseline for product, customer, geographic, and time-based analysis.

---

# 🔎 Key Business Insights

## 1. Apple Leads Brand-Level Sales

Apple generated approximately **$162M in sales**, the highest among the five analyzed brands.

| Brand | Sales | Transactions |
|---|---:|---:|
| **Apple** | **$162M** | 783 |
| Samsung | $160M | 775 |
| OnePlus | $154M | 768 |
| Vivo | $150M | 766 |
| Xiaomi | $144M | 743 |
| **Total** | **$769M** | **3,835** |

### Business Impact

The relatively narrow transaction-volume range across brands, combined with the difference in sales, indicates that **sales performance is not determined by transaction count alone**.

This creates an opportunity to investigate differences in product mix, selling price, and units sold when evaluating brand performance.

![Brand Sales Performance](dashboard.png)

---

# 📱 2. Product Performance Is Concentrated Among a Few Models

The three highest-selling models by sales were:

| Rank | Mobile Model | Sales |
|---:|---|---:|
| 🥇 1 | **iPhone SE** | **$59.57M** |
| 🥈 2 | **OnePlus Nord** | **$57.89M** |
| 🥉 3 | **Galaxy Note 20** | **$56.01M** |

### Business Impact

A relatively small group of models accounts for a significant portion of sales.

This provides a basis for:

- Prioritizing inventory for high-performing models
- Focusing promotional activity on proven products
- Monitoring stock availability for high-value models
- Comparing top-model performance against the broader product portfolio

![Top Selling Models](dashboard.png)

---

# 💳 3. Payment Behavior Is Highly Balanced

Transaction distribution across payment methods is remarkably even:

| Payment Method | Share of Transactions |
|---|---:|
| **UPI** | **26.36%** |
| Debit Card | 24.72% |
| Credit Card | 24.69% |
| Cash | 24.22% |

### Business Impact

No single payment method dominates the transaction mix.

UPI has the largest share, but the difference between the four payment methods is relatively small. This suggests that the business should **continue supporting a broad payment mix rather than relying heavily on a single payment channel.**

![Payment Method Distribution](dashboard.png)

---

# ⭐ 4. Customer Ratings Reveal a Majority of Positive Feedback — But a Meaningful Poor-Rating Segment Remains

Customer ratings were grouped into three analytical categories:

| Rating | Category | Transactions |
|---:|---|---:|
| 5 | **Good** | **2,331** |
| 4 | **Good** | Included above |
| 3 | **Average** | **652** |
| 1–2 | **Poor** | **852** |

Approximately **61% of transactions fall into the Good rating category**, while approximately **22% fall into the Poor category**.

### Business Impact

The majority of customer interactions fall into the positive category, but the size of the Poor segment is large enough to warrant investigation.

The dashboard therefore creates an opportunity to drill further into:

- Product-level satisfaction
- City-level satisfaction
- Brand-level rating patterns
- Payment-method relationships
- Customer demographics

Importantly, the dataset identifies **where lower ratings occur**, but does not by itself establish *why* customers gave lower ratings.

![Customer Rating Distribution](rating_dimension.png)

---

# 📅 5. Sales Performance Changes Meaningfully Across Days of the Week

Sales vary considerably by day.

| Day | Sales |
|---|---:|
| Monday | **$113.54M** |
| Tuesday | $109.57M |
| Wednesday | $104.91M |
| Thursday | $106.72M |
| Friday | $111.75M |
| **Saturday** | **$114.62M** |
| Sunday | $108.08M |

### Business Impact

Saturday records the highest sales among the seven days, while Wednesday records the lowest.

This creates a potential opportunity for **day-specific inventory planning, promotions, staffing, and campaign timing**, particularly around higher-volume periods.

![Sales by Day](dashboard.png)

---

# 📈 6. Monthly Demand Shows Clear Fluctuations

Quantity sold varies throughout the year.

| Month | Quantity Sold |
|---|---:|
| January | 1,672 |
| February | 1,451 |
| March | 1,696 |
| April | 1,528 |
| May | 1,625 |
| June | 1,597 |
| **July** | **1,700** |
| August | 1,592 |
| September | 1,521 |
| October | 1,577 |
| November | 1,582 |
| December | 1,609 |

July records the highest quantity sold, while February records the lowest.

### Business Impact

The monthly pattern demonstrates that demand is not uniform throughout the year.

This can support:

- Seasonal inventory planning
- Campaign scheduling
- Procurement decisions
- Sales-target setting
- Monitoring unexpected demand changes

![Quantity Sold by Month](dashboard.png)

---

# 🌍 7. Geographic Analysis Enables City-Level Performance Monitoring

Sales were analyzed across cities throughout India.

The geographic view allows users to identify areas where sales activity is concentrated and compare performance across locations.

### Business Impact

Geographic visibility can support:

- Regional sales planning
- Inventory allocation
- Market expansion analysis
- Identification of high-performing cities
- Further investigation of underperforming markets

![Sales by City](dashboard.png)

---

# 📊 8. Time-Intelligence Analysis Enables Performance Benchmarking

The dashboard incorporates:

- **MTD — Month-to-Date**
- **QTD — Quarter-to-Date**
- **YTD — Year-to-Date**
- **Same Period Last Year**

This allows current performance to be evaluated against historical benchmarks rather than viewed in isolation.

![Same Period Last Year Analysis](same_period_last_year_24.png)

### Business Impact

Time-intelligence analysis makes it possible to distinguish between:

> **"How much did we sell?"**

and

> **"How is current performance tracking against the corresponding historical period?"**

This is significantly more useful for management decision-making because it introduces a performance benchmark.

---

# 📈 Month-to-Date Performance

The MTD report tracks cumulative sales progression throughout the selected month.

The August 2022 example demonstrates cumulative sales increasing from approximately **$0.5M at the beginning of the month to $23.1M by month-end**.

![MTD Report](mtd_report_aug_22.png)

### Business Impact

Cumulative MTD tracking provides an early indication of whether sales are progressing toward the expected period performance.

It can be used to:

- Monitor sales momentum
- Detect slow periods early
- Compare progress against historical periods
- Support short-term sales decisions

---

# 📊 Dashboard Overview

The primary dashboard consolidates multiple analytical perspectives into a single interactive interface.

### Main capabilities

- KPI monitoring
- Brand filtering
- Mobile-model filtering
- Payment-method filtering
- Year selection
- Month selection
- Monthly sales comparison
- Quarterly comparison
- Yearly comparison
- City-level analysis
- Payment distribution
- Customer-rating analysis
- Model-level sales ranking

![Main Dashboard](dashboard.png)

---

# 🧭 Dashboard Pages

## 1. Executive Dashboard

The main dashboard provides the overall sales picture and allows users to move from high-level KPIs into product, geographic, customer, payment, and time-based analysis.

![Executive Dashboard](dashboard.png)

---

## 2. MTD Analysis

The MTD page focuses on cumulative sales progression throughout the selected month.

![MTD Analysis](mtd_report_aug_22.png)

---

## 3. Same Period Last Year Analysis

The comparison page evaluates current performance against the corresponding historical period.

![Same Period Last Year](same_period_last_year_24.png)

---

# 🧱 Data Architecture

The solution uses a **dimensional data model** centered around the transactional Mobile Sales Fact table.

![Power BI Data Model](data_model.png)

### Model Structure

```text
                    ┌─────────────────────┐
                    │    Calendar Table   │
                    │                     │
                    │ Date                │
                    │ Day Name            │
                    │ Day Number          │
                    │ Month               │
                    │ Quarter             │
                    │ Year                │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Mobile Sales Fact  │
                    │                     │
                    │ Transaction ID      │
                    │ Date                │
                    │ Units Sold         │
                    │ Price Per Unit      │
                    │ Customer            │
                    │ City                │
                    │ Payment Method      │
                    │ Customer Rating     │
                    │ Mobile Model        │
                    └──────┬───────┬──────┘
                           │       │
                ┌──────────┘       └──────────┐
                ▼                             ▼
      ┌────────────────────┐       ┌────────────────────┐
      │ Mobile Brand       │       │ Rating Dimension   │
      │ Dimension          │       │                    │
      │ Brand              │       │ Customer Ratings   │
      │ Mobile Model       │       │ Rating Category    │
      └────────────────────┘       └────────────────────┘
```

---

# 🗃️ Data Preparation & Power Query

Power Query was used to transform the source data into an analytical structure suitable for reporting.

The preparation process included:

- Promoting headers
- Correcting data types
- Creating the Date field
- Building a Calendar dimension
- Creating the Mobile Brand dimension
- Removing duplicate dimension records
- Creating customer-rating categories
- Structuring the transactional fact table
- Preparing fields for time-intelligence analysis

---

## Mobile Sales Fact

The transactional table forms the analytical foundation of the model.

![Mobile Sales Fact Power Query](power_query_sales_fact.png)

---

## Calendar Table

The Calendar table provides the date hierarchy required for monthly, quarterly, yearly, MTD, QTD, YTD, and prior-period analysis.

![Calendar Table Power Query](power_query_calendar_table.png)

---

## Mobile Brand Dimension

The Mobile Brand dimension separates brand and model attributes from the transactional fact table.

![Mobile Brand Dimension Power Query](power_query_mobile_dimension.png)

---

## Rating Dimension

Customer ratings were transformed into analytical categories to simplify customer-satisfaction analysis.

![Rating Dimension Power Query](power_query_rating_dimension.png)

---

# 🧮 DAX & Analytical Measures

The reporting layer uses DAX measures to create reusable business metrics rather than relying solely on raw columns.

### Core Measures

```text
Sales Amount
Total Quantity
Total Transactions
Average Price
```

### Time-Intelligence Measures

```text
MTD
QTD
YTD
Same Period Last Year
```

The use of measures allows the dashboard calculations to dynamically respond to slicers and filter selections.

---

# 🧠 Analytical Approach

The project follows a structured analytical workflow:

```text
Raw Transaction Data
        ↓
Data Cleaning & Validation
        ↓
Power Query Transformation
        ↓
Dimensional Data Modeling
        ↓
DAX Measures
        ↓
Time Intelligence
        ↓
Interactive Power BI Dashboard
        ↓
Business Interpretation
```

This approach separates **data preparation, data architecture, analytical calculations, and visualization**, making the solution easier to maintain and extend.

---

# ❓ Business Questions Answered

The dashboard was designed around practical business questions:

1. What is the overall sales performance?
2. How many units and transactions were generated?
3. Which brands generate the highest sales?
4. Which mobile models are the strongest revenue contributors?
5. How does sales volume change throughout the year?
6. Which days generate the highest sales?
7. Which cities contribute to overall sales?
8. Which payment methods are most frequently used?
9. What proportion of customers fall into each rating category?
10. How is current performance tracking against the same period last year?
11. How does cumulative MTD performance evolve throughout the month?
12. Which products should receive greater attention based on sales contribution?

---

# 💡 Business Impact

The dashboard transforms a transaction-level dataset into a management-oriented analytical tool.

### 1. Improved Sales Visibility

A consolidated KPI layer provides immediate visibility into sales, quantity, transactions, and pricing performance.

### 2. Better Product Prioritization

Model-level sales rankings identify high-performing products that can be prioritized for inventory and promotional decisions.

### 3. Stronger Brand Performance Monitoring

Brand-level comparisons allow management to evaluate sales contribution alongside transaction volume.

### 4. More Effective Time-Based Planning

Monthly, daily, MTD, quarterly, YTD, and prior-year comparisons provide multiple perspectives for monitoring sales momentum.

### 5. Customer Experience Monitoring

The rating dimension highlights the size of the positive, average, and poor-rating segments and creates a starting point for deeper customer-experience investigation.

### 6. Regional Performance Visibility

City-level analysis allows sales activity to be evaluated geographically and provides a basis for regional planning.

### 7. Payment Channel Understanding

The balanced payment-method distribution demonstrates the importance of maintaining multiple payment options while monitoring changes in channel usage.

---

# ⚠️ Analytical Limitations

The results should be interpreted within the scope of the available dataset.

### No profitability analysis

The dataset contains selling-price information but does not provide cost of goods sold, margins, discounts, logistics costs, or operating expenses.

Therefore, **sales revenue should not be interpreted as profit or profitability**.

### No causal customer analysis

The customer rating analysis identifies rating patterns but does not establish the causes behind poor or average ratings.

### No inventory data

The analysis cannot determine whether a product's sales performance was constrained by stock availability.

### No marketing attribution

The dataset does not contain campaign, advertising, or acquisition-source information, so the analysis cannot attribute sales changes to marketing activity.

These limitations define logical opportunities for future analysis rather than weaknesses in the dashboard itself.

---

# 🚀 Potential Extensions

The solution could be expanded with additional business data to support:

- Gross-margin analysis
- Discount and promotion effectiveness
- Inventory availability and stock-outs
- Customer segmentation
- Repeat-purchase analysis
- Customer lifetime value
- Marketing-channel attribution
- Sales forecasting
- Product profitability
- Regional target vs. actual analysis

---

# 🛠️ Tools & Technologies

| Technology | Application |
|---|---|
| **Microsoft Power BI** | Dashboarding, visualization & interactive reporting |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and time-intelligence calculations |
| **Microsoft Excel** | Source transaction data |
| **Dimensional Modeling** | Analytical data architecture |

---

# 📁 Project Structure

```text
Mobile-Sales-PowerBI/
│
├── README.md
├── Mobile Sales Data.xlsx
├── Mobile Sales Dashboard.pbix
│
├── Screenshots/
│   ├── dashboard.png
│   ├── dashboard_with_data_pane.png
│   ├── mtd_report_aug_22.png
│   ├── same_period_last_year_24.png
│   ├── data_model.png
│   ├── sales_fact.png
│   ├── calendar_table.png
│   ├── mobile_dimension.png
│   ├── rating_dimension.png
│   ├── power_query_sales_fact.png
│   ├── power_query_calendar_table.png
│   ├── power_query_mobile_dimension.png
│   └── power_query_rating_dimension.png
│
└── Documentation/
    └── Mobile Sales Analysis Report.pdf
```

> **Note:** File names in the structure above should match the actual files committed to the repository.

---

# 📷 Supporting Evidence

## Data Model

![Data Model](data_model.png)

## Mobile Sales Fact

![Sales Fact](sales_fact.png)

## Calendar Table

![Calendar Table](calendar_table.png)

## Mobile Brand Dimension

![Mobile Dimension](mobile_dimension.png)

## Rating Dimension

![Rating Dimension](rating_dimension.png)

---

# 🔍 Power Query Transformation Evidence

### Sales Fact Transformation

![Power Query Sales Fact](power_query_sales_fact.png)

### Calendar Transformation

![Power Query Calendar](power_query_calendar_table.png)

### Mobile Brand Dimension Transformation

![Power Query Mobile Dimension](power_query_mobile_dimension.png)

### Rating Dimension Transformation

![Power Query Rating Dimension](power_query_rating_dimension.png)

---

# 📊 Full Dashboard Views

### Executive Dashboard

![Dashboard](dashboard.png)

### Dashboard with Power BI Data Pane

![Dashboard with Data Pane](dashboard_with_data_pane.png)

### MTD Report

![MTD Report](mtd_report_aug_22.png)

### Same Period Last Year

![Same Period Last Year](same_period_last_year_24.png)

---

# 🔐 Data Privacy

Customer names in the publicly shared project files and screenshots have been **masked/anonymized** for portfolio and demonstration purposes.

The dataset should therefore be treated as a demonstration dataset rather than a production customer database.

---

# 🎯 Conclusion

This project demonstrates how transactional sales data can be transformed into an interactive business intelligence solution that moves beyond descriptive reporting.

The final solution combines:

**Data Preparation → Data Modeling → DAX → Time Intelligence → Visualization → Business Interpretation**

The resulting dashboard provides a unified view of **$769.20M in analyzed sales across 3,835 transactions and 19,150 units**, while allowing users to investigate product, brand, customer, geographic, payment, and time-based performance.

More importantly, the analysis provides a framework for moving from:

> **"What happened?"**

to:

> **"Where did it happen, which products and segments contributed to it, how does it compare with historical performance, and where should management investigate next?"**

---

# 🔗 Project Links

### 📊 Interactive Power BI Dashboard

**[View Live Power BI Dashboard](YOUR_POWER_BI_PUBLIC_LINK_HERE)**

### 💻 GitHub Repository

**[View Complete Project on GitHub](YOUR_GITHUB_REPOSITORY_LINK_HERE)**

---

# 👤 Author

**Your Name**

Data Analyst | Business Intelligence | Power BI | SQL | Excel

[LinkedIn](YOUR_LINKEDIN_PROFILE_LINK_HERE) • [GitHub](YOUR_GITHUB_PROFILE_LINK_HERE)

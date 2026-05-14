# Tata Data Visualization Virtual Internship (Forage)

## Project Overview

This project was completed as part of the Tata Forage Data Visualization Virtual Internship. The objective was to analyze an online retail dataset and generate business insights to support strategic decision-making for the CEO and CMO.

The analysis focused on identifying revenue trends, customer behavior, high-performing regions, and potential business expansion opportunities using data visualization techniques.

---

## Business Objectives

- Analyze revenue trends and seasonality
- Identify top-performing countries and products
- Understand customer purchasing behavior
- Provide data-driven recommendations for business expansion

---

## Data Cleaning and Preparation

To ensure accurate analysis, the dataset was cleaned and transformed before visualization.

### Data Cleaning Steps

- Removed records where `Quantity < 1`
- Removed records where `Unit Price < 0`
- Handled missing Customer IDs
- Created a new `Revenue` column using:

```text
Revenue = Quantity × UnitPrice
```

These steps improved data quality and ensured meaningful insights.

---

## Tools Used

- Power BI
- Power Query
- Excel / CSV

---

## Dashboard Insights

### 1. Revenue Trend Analysis (2011)

- Revenue showed strong seasonal patterns throughout the year
- Significant growth was observed during November and December
- Sales performance increased during holiday periods

#### Insight

Seasonal demand trends can help improve forecasting, inventory planning, and marketing strategies.

---

### 2. Country Performance Analysis

Top-performing countries outside the UK included:

- Eire (~124.72K)
- Netherlands (~104.23K)
- Germany (~95.39K)

Lower-performing countries included:

- Saudi Arabia
- USA
- Bahrain

#### Insigh_1

Revenue is concentrated in a few strong international markets, making them suitable targets for expansion and focused marketing efforts.

---

### 3. Product Performance Analysis

- The highest revenue-generating product was `POST` (~27,203.94)
- Another strong-performing product was `M` (~19,492)
- Some products contributed very little revenue

#### Insigh_2

Businesses can optimize inventory and improve profitability by focusing on high-performing products and reviewing low-performing items.

---

### 4. Customer Analysis

- Customer ID `1300` had the highest purchase frequency
- A small group of customers contributed a significant share of total revenue

#### Insight_3

Customer retention strategies and loyalty programs can help maintain and grow revenue from high-value customers.

---

## Key Recommendations

- Expand operations in high-performing countries
- Focus on customer retention and loyalty programs
- Optimize low-performing products
- Use seasonal trends for inventory and marketing planning

---

## Project Structure

```bash
├── dataset.csv / .xlsx
├── PowerBI_Dashboard.pbix
├── README.md
├── certificate_tata.pdf

```

---

## Conclusion

This project demonstrates how data visualization and business analytics can support strategic decision-making. It highlights practical data analyst skills including:

- Data cleaning
- Data transformation
- Dashboard development
- Business insight generation
- Data storytelling

The project reflects real-world business analysis scenarios and showcases the use of Power BI for generating actionable insights.

---

## Acknowledgment

This project was completed as part of the Tata Forage Data Visualization Virtual Internship Program.

# SAS-Visual-Analytics-Dashboard-Customer-Location-Analysis
An interactive SAS Visual Analytics project analyzing customer behavior, sales channels, and global profitability using filters, drill-downs, and location-based insights for strategic decision-making.

<img width="501" height="222" alt="image" src="https://github.com/user-attachments/assets/62318dad-4ed9-452b-ac2d-07d90fdea8ea" />

🗂 Project Structure
1. Customer Analysis Page

Key Value Object (Profit): Instant snapshot of overall profitability.

Donut Chart – Quantity Ordered by Age Group: Visualizes customer demographics and purchasing patterns.

Bar Chart – Profit by Order Date (Hierarchy): Tracks profitability trends over time (Year → Quarter → Month → Day).

Prompts & Actions:

Sales channel filter (Catalog, Internet, Retail Store)

Drill-downs for deeper analysis

Interactive links to related visuals

Why it’s included: To give managers insight into customer behavior, profit trends, and sales channels.

2. Retail & Dashboard Evaluation

Dashboard follows 8 SAS guidelines for effective reporting:

Know your audience

Highlight key findings

Use appropriate detail

Enable interactivity

Support storytelling layout

Use effective visuals

Filter for relevance

Keep the report clean

Improvements Suggested:

Add titles to charts without labels

Improve contrast and font sizes for better readability

3. Data Exploration

Dataset size: 491,826 rows and 38 columns

Key fields:

Transactions (TransactionId, OrderType, ItemQuantity, Profit)

Customer demographics (Age, CustomerName, Email)

Geography (CountryName, StateRegion, CityName)

Sales channel (OrderChannel)

Steps Performed:

Checked dataset structure in SAS Viya

Identified missing values (notably in StateRegion and Email)

Validated data types and formats

4. Location Analysis Page

Designed for Chocolate Enterprise senior management, highlighting global and regional profitability.

Objects Used:

🌍 Geo Map: Item Quantity by Country (highlights strong/weak markets)

📊 Crosstab Table: Country-level sales summary

📈 Bar Chart (Drill-down): Profit by Country → State → City

Business Questions Answered:

Where are we making the most profit globally?

Which regions should we target for marketing investment?

Are retail outlets efficiently utilized?

Which regions are underperforming?

5. Bonus: Overview Page

A summary page linking Customer, Retail, and Location analysis

Uses text, images, and page links for seamless navigation

✅ Features

Interactive dashboards (filters, prompts, drill-downs)

Visual storytelling (profit summary → demographics → time trends → geography)

Clean, organized layouts following SAS guidelines

Insightful for marketing, operations, and strategy teams

🚀 Future Enhancements

Add KPIs like Customer Lifetime Value (CLV)

Predictive analytics (e.g., demand forecasting, churn prediction)

Automated anomaly detection in profit trends

Cloud-based deployment for wider accessibility

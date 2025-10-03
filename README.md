# SAS Visual Analytics Dashboard – Customer & Location Analysis  

## 📌 Overview  

<img width="501" height="222" alt="image" src="https://github.com/user-attachments/assets/399fb513-97d9-48c0-b52d-23687c06c5c4" />

An interactive **SAS Visual Analytics project** analyzing customer behavior, retail performance, and global profitability.  
- Built in **SAS Viya**  
- Includes interactive **filters, prompts, drill-downs, and geo-maps**  
- Provides actionable insights for business decision-making  

---

## 🗂 Project Structure  

### 1. Customer Analysis Page  
- **Key Value Object (Profit)**: Instant snapshot of overall profitability  
- **Donut Chart – Quantity Ordered by Age Group**: Visualizes demographics and purchasing patterns  
- **Bar Chart – Profit by Order Date (Hierarchy)**: Tracks trends by Year → Quarter → Month → Day  
- **Interactive Features**:  
  - Sales channel filters (Catalog, Internet, Retail Store)  
  - Drill-down functionality for deeper analysis  
  - Page links to navigate across dashboards  

---

### 2. Dashboard Evaluation (Following SAS Guidelines)  
- **Strengths**:  
  - Clean layout with focused visuals  
  - Drill-downs and interactive filters for exploration  
  - Storytelling flow from summary → segmentation → trends  
- **Improvements Suggested**:  
  - Add chart titles where missing  
  - Improve color contrast and font sizes for readability  

---

### 3. Data Exploration  
- Dataset size: **491,826 rows × 38 columns**  
- Includes **transactions, customers, geography, product details, and sales channels**  
- Key fields:  
  - `TransactionId`, `OrderType`, `ItemQuantity`, `Profit`  
  - `Age`, `CustomerName`, `Email`  
  - `CountryName`, `StateRegion`, `CityName`  
  - `OrderChannel`  
- Issues Identified: Missing values in **State/Region** and **Email** fields  

---

### 4. Location Analysis Page  
- Designed for **Chocolate Enterprise senior management**  
- **Objects Used**:  
  - 🌍 **Geo Map** – Item Quantity by Country  
  - 📊 **Crosstab Table** – Country-level sales summary  
  - 📈 **Bar Chart (Drill-down)** – Profit by Country → State → City  

**Business Questions Answered:**  
- Where are we making the most profit globally?  
- Which regions should we target for marketing investment?  
- Are retail outlets being utilized efficiently?  
- Which regions are underperforming?  

---

## ✅ Features  
- Interactive dashboards with filters, prompts, and drill-downs  
- Visual storytelling layout for clarity and decision-making  
- Clean design with minimal clutter  
- Business insights for **marketing, operations, and strategy teams**  

---

## 🚀 Future Enhancements  
- Add KPIs like **Customer Lifetime Value (CLV)**  
- Predictive analytics (e.g., demand forecasting, churn prediction)  
- Automated anomaly detection in profit trends  
- Cloud deployment for accessibility and scalability  

---

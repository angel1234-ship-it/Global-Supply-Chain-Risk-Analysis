# 📊 Global  Supply Chain & Risk Analysis Dashboard (Power BI)

## 📌 Overview

This project presents a **Power BI dashboard** designed to analyze shipment operations, performance, and disruption risks across multiple dimensions such as weather, transport modes, product categories, and locations.

The objective is to transform raw shipment data into meaningful insights that support operational and strategic decision-making.

---

## 📁 Dataset

* Source: Kaggle
* Format: Single-sheet dataset
* The dataset was cleaned, validated, and transformed into a structured format suitable for analysis

---

## 🧱 Data Modeling

The dataset was redesigned using a **star schema model** for efficient analysis.

### Dimension Tables:

* `Dim_Weather`
* `Dim_Port`
* `Dim_Transport`
* `Dim_Product`
* `Dim_Date`

### Fact Table:

* `Fact_shipments`

### Data Preparation:

* Removed duplicates
* Ensured correct data types
* Checked data consistency
* Established relationships between fact and dimension tables

---

## 📐 DAX Measures

### 🔹 Operational Metrics

* Total Shipments
* Total Distance
* Total Weight
* Average Lead Time
* Total Product Categories
* Total Ports

### 🔹 Performance Metrics

* Average Reliability Score
* Most Reliable Product Category
* Most Reliable Port

### 🔹 Risk Metrics
* Disruption Rate
* Average Disruption Rate
* Total Disrupted Shipments
* Average Geopolitical Risk Score
* Highest Risk Product Category 
* Weather Condition with Highest   Disruption
* Product Category with Highest Disruption

### 🔹 Logistics & Flow Metrics
* Most Shipped Product Category
* Top Exporting Port
* Top Importing Port 
---

## 📊 Power BI Features Used

* Slicers:

  * Shipment Start (Origin Port)
  * Shipment End (Destination Port)
  * Transport Mode
  * Date Hierarchy (Year, Quarter, Month, Day)
  * Year

* Interactive filters

* Drill-down functionality

* Tooltips for additional insights

* Cross-filtering between visuals

* Page Navigator for easy navigation

---

## 🔍 Key Analysis & Insights

### 🚚 Shipment Patterns

* Highest shipments occurred during **fog conditions (20.7%)**, followed by storms
* **Air transport** handled the highest shipment volume (1,320 shipments), followed by sea
* **Electronics** was the most shipped product category

---

### 📦 Product Performance
* **Electronics**  is the most shipped product category
* **Electronics** is the  most reliable product category

* **Textiles** recorded the highest disruption rate (64.85%)
* **Perishables, textiles, and pharmaceuticals** showed the highest average lead times

---

### 🌍 Location Performance

* **Busan** was the busiest origin port (667 shipments)
* **Shanghai and Rotterdam** had the highest average lead time among origin ports (21 days)
* **Busan, Singapore, and Marseille** had the highest lead time among destination ports (21 days)

---

### ⚠️ Risk & Disruption Analysis

* **Hurricane conditions** resulted in the highest disruption rate
* **Air transport mode** showed the highest disruption rate
* Total disrupted shipments: **3,063**
* Geopolitical risk peaks observed in:

  * February, April, July, November, December

---
## 💡 Recommendations

### 🚚 Transport Improvement
- Air transport has more disruptions, so try using other transport methods for important shipments  

### 🌦 Weather Planning
- Plan shipments carefully during  hurricane  and storm conditions to avoid delays  

### 📦 Product Handling
- Improve handling of textiles since they have the highest disruption rate  
- Focus on reducing delivery time for perishables and pharmaceuticals  

### 🌍 Port Efficiency
- Check and reduce delays in ports like Shanghai and Rotterdam  
- Improve operations in busy ports like Busan and Singapore  

### ⚠️ Risk Management
- Pay more attention to high-risk months (Feb, Apr, Jul, Nov, Dec)  
- Create backup plans to handle disruptions  
---
## 📂 Project Files


| File Type             | Description              | Link              |
| --------------------- | ------------------------ | ----------------- |
| 📊 Power BI Dashboard | Interactive `.pbix` file | [Open](your-link) |
| 📄 Project Report     | Detailed analysis report | [View](https://github.com/angel1234-ship-it/Global-Supply-Chain-Risk-Analysis/blob/main/Main_project.pdf) |
| 📽 Presentation       | Project summary slides   | [View](your-link) |

---

## 🛠 Skills Demonstrated

* Data Modeling (Star Schema)
* Data Cleaning & Validation
* DAX (Data Analysis Expressions)
* Data Visualization
* Business Insight Generation

---

## ▶️ How to Use

1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Use slicers to filter and explore data
4. Navigate between pages using the page navigator

---

## 📌 Conclusion

This project demonstrates how structured data modeling and interactive dashboards can provide deep insights into shipment operations, performance, and risks. It highlights the importance of data-driven decision-making in supply chain management.

---


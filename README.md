# Personal Finance Dashboard - Data Analysis Project

## 📌 Project Overview
This project is an end-to-end data analytics solution built entirely in Microsoft Excel. It transforms a messy dataset of over 21,000+ financial transactions into a clean, interactive, and fully dynamic dashboard to track income, expenses, and net balance over time.

## 🛠️ Tools & Technologies Used
* **Microsoft Excel** (Data Visualization, Advanced Formatting)
* **Power Query** (ETL - Extract, Transform, Load)
* **PivotTables & PivotCharts** (Data Modeling & Aggregation)

## 🧹 Data Cleaning (The ETL Process)
The raw dataset was intentionally unstructured and contained severe spelling inconsistencies. I used Power Query to extensively clean and standardize the data:
* Cleaned the `category` and `payment_mode` columns by applying over 140+ targeted 'Replace Value' steps.
* Handled dozens of spelling variations (e.g., merging "Upii", "Upupi", "Pui" into a single "UPI" category, and fixing multiple variations of "Bank Transfer" and "Cash").
* Streamlined the dataset to focus only on actionable, categorical data.

## 📊 Dashboard & Visualizations
* **Dynamic KPI Cards:** Clean summary boxes calculating Total Income, Total Expense, and Net Balance, dynamically linked to the backend PivotTables.
* **Expense Breakdown:** A horizontal Bar Chart displaying top expenses by category.
* **Trend Analysis:** A Line Chart illustrating transaction trends over multiple years.
* **Interactive Filtering:** Integrated Excel Timelines (for sliding date ranges) and Slicers (for payment modes). Used "Report Connections" to sync all charts and KPIs for real-time interactivity.

## 📸 Dashboard Preview
![Dashboard Preview](Screenshot-Name.jpg)

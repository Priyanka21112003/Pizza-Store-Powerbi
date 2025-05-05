# 🍕 Pizza Shop Power BI Dashboard

This repository contains an interactive **Power BI dashboard** project that analyzes a pizza shop's sales performance. It uses dynamic visuals, slicers, and navigation buttons to offer actionable business insights.

---

## 🔄 1. Data Processing

Before importing the data into Power BI, the following preprocessing steps were performed:

- ✅ Cleaned raw data (removed null values, handled inconsistent entries)
- ✅ Split and reformatted columns (e.g., extracted date, time, pizza category)
- ✅ Created new calculated fields to assist in trend analysis
- ✅ Ensured the dataset was in a structured and analysis-ready format

---

## 🧠 2. DAX Measures & Calculations

In Power BI, I wrote several **DAX (Data Analysis Expressions)** queries to power the insights:

- `Total Revenue`
- `Order Count`
- `Top 5 Best-Selling Pizzas`
- `Worst Performing Pizzas`
- Time-based filters: Weekday, Hour, Month
- Dynamic category-based aggregations

These measures update automatically based on slicers and bookmarks.

---

## 📊 3. Dashboard Design

The report is divided into **three main interactive views**, controlled by **buttons** using **bookmarks and the selection pane**:

| Home View | Best/Worst View | Summary View |
|-----------|------------------|--------------|
| ![Home](https://github.com/user-attachments/assets/e0e3675d-2c89-4d45-951a-4012ad992c92) | ![Best/Worst](https://github.com/user-attachments/assets/5ccae573-4765-4019-a82b-2a04476328c9) | ![Summary](https://github.com/user-attachments/assets/5ee35517-1db4-4e78-996c-8d4dfdba937e) |

---

### 🎛️ Button Navigation
- **Home** – General overview: sales trend, revenue, order distribution
- **Best/Worst** – Displays best- and worst-selling pizzas
- **Summary** – Highlights key KPIs and pizza category comparisons

Bookmarks and selection pane allow each button to control page content dynamically.

---

## 🧩 4. Features

- 📌 Interactive buttons for smooth navigation
- 📌 Clean UI with consistent layout and colors
- 📌 Dynamic DAX calculations
- 📌 Custom bookmarks for content switching
- 📌 Responsive slicers and filters
- 📌 Visual types: bar charts, pie charts, line graphs, cards

---

## 🛠 5. Tools & Technologies Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Excel/CSV for data preprocessing
- Power BI Bookmarks & Selection Pane

---

## 📈 6. Key Insights

- 🍕 Identified the most and least popular pizzas
- ⏰ Analyzed peak order hours and weekdays
- 💰 Tracked monthly revenue trends
- 🧀 Compared performance across pizza categories

---

# 📊 Superstore Sales Analysis — Power BI Dashboard

> 🎯 A fully interactive **Business Intelligence Dashboard** created using the **Sample Superstore dataset** to help analyze core KPIs such as sales, profit, discount rates, and customer trends — brought to life with modern visuals, slicers, DAX measures, and clean UX in **Power BI Desktop**.

---

## 🧾 Project Overview

This dashboard project aims to showcase how **Power BI** can be leveraged to transform raw business data into **meaningful insights** that help stakeholders make better decisions.

Key goals:
- Identify **high-performing categories and regions**
- Understand **sales and profit patterns** over time
- Provide an **interactive user experience** with slicers and filters
- Leverage **custom DAX measures** to calculate insights like **Profit Margin %** and **Average Discount**

---

## 🏗️ Tools & Technologies

| Tool               | Purpose                                                  |
|--------------------|----------------------------------------------------------|
| 🧮 Power BI Desktop | Data modeling, dashboard development & DAX               |
| 📊 DAX             | Custom measures like `Profit Margin`, `Total Discount`   |
| 📁 CSV File        | Raw data source: `Sample - Superstore.csv`               |
| 📦 Power Query     | Data cleaning and transformation                          |

---

## 🎞️ Dashboard Snapshots (Animated Ready)

> 💡 *All screenshots are static here, but animations or GIFs can be added later for a full visual experience showing slicer interactions, dynamic filtering, and bookmarks.*

| 🔍 Visual Section | 📸 Preview |
|------------------|------------|
| **Total Sales KPI + Slicers** | ![Total Sales Card](./1.png) |
| **Sales by Category – Bar Chart** | ![Sales by Category](./2.png) |
| **Line Chart – Sales Over Time** | ![Sales over Time](./3.png) |
| **Profit Margin Card + Filter View** | ![Profit Margin Card](./4.png) |
| **Final Integrated Dashboard Layout** | ![Final Dashboard](./5.png) |

📽️ *To be added: Animated walkthroughs via GIFs showcasing slicer transitions, navigation buttons, and visual interactivity.*

---

## 📁 Dataset Details

File Used: `Sample - Superstore.csv`

Contains the following major columns:
- `Order Date`, `Ship Date`
- `Region`, `State`, `City`
- `Customer Name`, `Segment`
- `Category`, `Sub-Category`
- `Sales`, `Profit`, `Discount`, `Quantity`

✅ Preprocessed in Power Query to clean column names, extract `Order Year`, and prepare date formats for time intelligence functions.

---

## 📐 DAX Measures Implemented

| Measure             | Description                                             |
|----------------------|---------------------------------------------------------|
| `Total Sales`        | Total revenue generated — `SUM(Sales)`                 |
| `Total Profit`       | Total net profit — `SUM(Profit)`                       |
| `Profit Margin %`    | Profitability ratio — `DIVIDE([Total Profit], [Sales])`|
| `Avg Discount`       | Average discount offered — `AVERAGE(Discount)`         |
| `Total Discount`     | Total discount amount — `SUM(Sales * Discount)`        |

Additional calculated columns and time-based fields include:
- `Order_Years` (Year from `Order Date`)
- `Month_Name` (Custom column for monthly trend analysis)

---

## 🎛️ Slicers, Filters & Interactivity

This dashboard supports **dynamic exploration** through both **standard slicers** and **custom button slicers** using bookmarks.

### ✔️ Standard Slicers:
- 📅 **Order Year** — Filter visuals by year
- 🌍 **Region** — Analyze region-specific metrics
- 👤 **Customer First Name** — Drill down into customer-level details

### 🔘 Button Slicers (with Bookmarks):
- Toggle between **Sales View** and **Profit View**
- Switch between **Charts and Tables**
- Reset filters or apply specific scenarios with a single click

These elements enhance user experience by **mimicking app-like navigation** inside Power BI.

---

## 📊 Visuals Used

| Visual Type          | Use Case                                                 |
|-----------------------|-----------------------------------------------------------|
| **Cards**             | Display KPIs: Total Sales, Total Profit, Avg Discount     |
| **Clustered Bar Chart** | Compare sales across Categories & Sub-Categories        |
| **Line Chart**        | Analyze Sales Trends over Time                            |
| **Pie Chart**         | Segment data by Region visually                           |
| **Matrix/Table**      | Drill into raw transaction data for details               |
| **Bookmarks & Buttons** | Enable navigation and dynamic layouts                    |

✅ All visuals are formatted with **consistent color themes**, **rounded corners**, and **modern layout alignment** to ensure a clean presentation.

---

## 🚀 How to Use

> Make the most out of this dashboard by following these quick steps:

1. **Open the `.pbix` file** in Power BI Desktop
2. **Interact** with standard and button-based slicers
3. **Explore visual relationships** by drilling into categories, customers, and time periods
4. **Use tooltips** and hover states to understand deeper insights
5. Optionally, publish to **Power BI Service** for web-based access and sharing

---

## 📌 Future Enhancements

- 🎞️ Add animated walkthroughs (`.gif`) showing interactions
- 🌐 Embed to Power BI Service with public share
- 📥 Include downloadable `.pbix` file and raw dataset
- 📊 Add RLS (Row-Level Security) setup for user-based access

---

## 🌟 Why This Project Matters

This Power BI dashboard is a great example of:
- 📈 Turning static data into **insightful stories**
- 🧠 Leveraging DAX for **powerful calculated insights**
- 🖱️ Building **user-friendly, interactive dashboards**
- 🧩 Incorporating both **technical depth** and **design thinking**

It can serve as a **portfolio project**, a **learning resource**, or even be adapted for **real-world use cases** in retail and sales analytics.

---

## 🙌 Let’s Connect!

If you liked this dashboard or want help creating one like this:

📩 **Contact Me:**
- [LinkedIn](#) • [GitHub](#) • [Email](#)

💼 Open to collaborations, internships, and freelance Power BI gigs!

---

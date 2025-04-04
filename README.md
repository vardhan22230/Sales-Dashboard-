# 📊 Sales Analysis Dashboard - Power BI

## 📝 Project Overview
This Power BI **Sales Analysis Dashboard** provides insights into sales performance using interactive visualizations. It helps businesses analyze sales trends, customer distribution, and revenue patterns over time.

## 📂 Datasets Used
We used two datasets for this project:
- **Sales Data**: Contains sales transactions with columns like `Sales_ID`, `Customer_ID`, `Product`, `Sales_Amount`, and `Order_Date`.
- **Customer Data**: Includes `Customer_ID`, `Customer_Name`, and `Location`.

### 🔄 Data Processing in Power Query
- **Merged Tables**: Sales and Customer datasets were merged on `Customer_ID`.
- **Data Cleaning**: Converted data types (e.g., `Sales_Amount` to Decimal, `Order_Date` to Date).
- **Derived Columns**:
  - `Order_Year`: Extracted from `Order_Date`.
  - `Sales_Category`: Categorized sales into **Low, Medium, High**.

## 📊 Dashboard Features
### 🔹 Visuals Included:
1️⃣ **Total Sales by Location (Stacked Bar Chart)**
2️⃣ **Sales Category Breakdown (Pie Chart)**
3️⃣ **Total Sales Over Time (Line Chart)**
4️⃣ **Filters (Slicers)** for **Year** and **Location**
5️⃣ **KPI Cards**:
   - Total Sales 💰
   - Total Orders 📦
   - Average Sales per Order 📊

## 🚀 How to Use
1️⃣ Open **Power BI** and load `Sales_Analysis_Dashboard.pbix`.
2️⃣ Use **Slicers** to filter sales data by **Location** and **Year**.
3️⃣ Analyze trends with interactive charts.
4️⃣ Export as **PDF** if needed for reports.

## 🔧 Setup Instructions
1️⃣ Install **Power BI Desktop** [Download Here](https://powerbi.microsoft.com/)
2️⃣ Clone this repository:
```bash
  git clone https://github.com/your-username/sales-dashboard.git
```
3️⃣ Open `Sales_Analysis_Dashboard.pbix` in Power BI.

## 📌 Future Enhancements
- Add **Profit Analysis** to track revenue vs. cost.
- Implement **Customer Segmentation** insights.
- Automate **data refresh** from a live source.

## 📎 Repository Link
🔗 [GitHub Repository](https://github.com/your-username/sales-dashboard)

## 💡 Conclusion
This project demonstrates the **power of Power BI** in sales data visualization, helping businesses gain actionable insights into their revenue trends. 🚀

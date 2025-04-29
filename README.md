# Superstore Sales Analysis Project

## 📊 **Overview**
This Power BI project analyzes sales data from the Superstore dataset (kaggle), leveraging interactive visualizations and advanced analytics. The primary goal is to derive actionable insights into sales performance, regional trends, and product profitability. 

This project was completed as part of a Simplilearn free course and showcases skills in **DAX functions** and **dashboard design**.

---

## 🚀 **Project Highlights**
### 1️⃣ **Dashboard Pages**
- **Page 1: Overall Sales Overview**
  - KPIs for Total Sales, Total Profit, and Total Revenue.
  - Slicer for `Order Date` to filter data dynamically.
  - Visualizations:  
    - **Line and Stacked Column Chart**: Yearly sales trends and profit.
    - **Clustered Column Chart**: Sales by year and quarter.
    - **Donut Chart**: Distribution of sales and profit by segment.
    - **Pie cahrt**: for profit and sales by category.
    - **Slicer**: for filering by order date.

- **Page 2: Regional and State-Level Analysis**
  - Slicer for `Sub-category`, `Region`, and `Year` to analyze data at different levels.
  - Visualizations:  
    - **Table**: City-wise sum of quantity and profit.
    - **Clustered Bar Chart**: Top-performing states by sales and category.
    - **Area Chart**: Maximum Profit trends by year and category.
    - **Funnel Chart**: Sales distribution across customer segments.

- **Page 3: Category and Subcategory Insights**
  - Focused on product categories and subcategories.
  - Visualizations:  
    
    - **Tree Map**: Sales and Profit by region and Segment.
    - **Pie Chart**: Quantity and Sales by Segment.
    - **Scatter Plot**: Relationship between sales, quantity, and profit.

---

### 2️⃣ **Key Features**
- **Custom Calculated Columns**:
  - Extracted `Month`, `Day`, `Weekday`, `Year`, and `Weekend` using DAX functions.
  - Calculated the total shipment time using `DATEDIFF`.
  - Converted sales values to currency format for better representation.
  
- **Dynamic Slicers**:
  - Applied slicers for `Order Date`, `State`, and `Region` to filter visuals dynamically.

- **Interactive Visualizations**:
  - Created dashboards using charts like **Pie Chart**, **Donut Chart**, **Line and Stacked Column Chart**, **Clustered Column Chart**, **Clustered Bar Chart**, **Funnel Chart**, **Tree Map**, and more.
  - Incorporated a **Matrix** for detailed tabular analysis.

---

## 🛠️ **Technologies and Tools Used**
- **Power BI**: For creating interactive dashboards and visualizations.
- **DAX (Data Analysis Expressions)**: For custom calculated columns and measures.
- **Sample Superstore Dataset**: As the data source.

---

### 🔍 Insights

- The **Consumer segment** contributed the **highest sales and profit**, highlighting it as the most lucrative customer group compare to corporate and home office.
- **Sales and profit have shown a consistent year-over-year increase**, with **Quarter 4 outperforming** all other quarters — possibly due to holiday season demand.
- **California led all states in total sales**, followed by **New York**, suggesting a concentration of high-value customers in these regions.
- The **Technology category** generated the **highest profit and sales**, while **Furniture** had the **lowest overall profitability**.
- Within subcategories:
  - **Copiers** (Technology) stood out with the **highest subcategory sales**.
  - **Tables** (Furniture) exhibited **declining or negative profit**, making it a potential area for cost or pricing optimization.
- The **West region** achieved the **highest regional sales**, totaling approximately **$150K**, indicating strong market performance in that geography.

---

## 🧠 **Learning Outcomes**
- Gained proficiency in Power BI's features like slicers, calculated columns, and advanced visualizations.
- Developed strong analytical skills by interpreting trends and making data-driven recommendations.
- Enhanced understanding of data visualization principles for storytelling.

---


## 📥 **How to Access the Project**
1. **Download Power BI Desktop**:  
   If you don’t already have it, download and install Power BI Desktop from [here](https://powerbi.microsoft.com/en-us/desktop/).

2. **Download the .pbix File**:  
   Clone this repository to your local machine or directly download the `.pbix` file from this repository.

3. **Open the .pbix File**:  
   Launch Power BI Desktop, open the `.pbix` file, and explore the dashboards.

4. **Interactive Visualization**:  
   Use the built-in slicers, filters, and charts to interact with the data and discover insights.

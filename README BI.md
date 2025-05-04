# **Ecommerce Sales Analysis**

![](https://github.com/worksakshi/Ecommerce-Sales-Analysis-PowerBI-Dashboard/blob/main/Data%20Model%20View.PNG)

### **Interactive Dashboard**  
![Insight_1](https://github.com/worksakshi/Ecommerce-Sales-Analysis-PowerBI-Dashboard/blob/main/image%201.PNG)
![Insight_2](https://github.com/worksakshi/Ecommerce-Sales-Analysis-PowerBI-Dashboard/blob/main/image%202.PNG)

---

## **Objective**  
Design a scalable, interactive dashboard for an e-commerce business to monitor sales, payment insights, and product performance across countries and time periods. The dashboard is built on a robust data model and supports strategic decision-making by offering insights into revenue trends, payment behaviors, and regional performance.
---

## **Action**  

### **Key Features**   
- **Central Fact Table**: factEcommerce contains core transactional data like sales, orders, dates, country, product, and payment details.
- **Dimensional Tables**: Linked dimension tables (e.g., dimProducts, dimCountry, dimPayment Method, and Calendar) support flexible 
  filtering and drill-down.
- **Interactive Dashboards**: Users can explore KPIs with slicers by product, continent, payment method, and time.
- **Custom Visualizations**: Used maps, bar charts, and card visuals to highlight sales by country, category, and time.
- **Dynamic DAX Measures**: Calculated revenue, total orders, average order value, and monthly trends.
- **Image Integration**: Displayed product and country flag images directly within the dashboard using image URLs from external CSV files.

### **Technology Stack**  
- **Data Sources:** PostgreSQL, MySQL, Excel, CSV, PDF.  
- **Tools:** Power BI, Power Query, DAX.  
- **Gateway:** Power BI Gateway for scheduled refresh.

### **Execution Steps**  

1. **Data Modeling**: Built a star schema with factEcommerce as the central table, ensuring referential integrity through one-to-many relationships.
2. **Data Cleaning & Transformation**: Cleaned data using Power Query, standardized naming, and ensured data types and keys were consistent.
3. **Visualization**: Developed multi-page reports with performance metrics, including maps for regional analysis and charts for payment trends.
4. **Image Mapping**: Merged product and country flag images using Product ID and Country as keys, allowing for enriched visuals.
5. **Time Intelligence**: Used the Calendar table to support YoY and MoM growth analysis.
6. **User Experience Design**: Included bookmarks for better usability.



## **Impact**  

The dashboard provides clear and actionable insights into sales, profits, and product performance, enabling the XGRIP team to make data-driven decisions. It offers users a visually appealing interface with interactive features and seamless data updates, significantly improving the efficiency of business reporting and analysis.

---

## **Key Learnings**  

---

## **Final Output**  

### **Screenshots**  
**Sales Overview Dashboard**  
![Sales Overview](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20dashboard.png)  

**Product Analysis Dashboard**  
![Product Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/product.png)  

**Map Analysis Dashboard**  
![Map Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20map.png)  

**Light and Dark Mode Example**  
![Light and Dark Mode](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/light%20dashboard.png)

---

## **Access the Dashboard**  
Explore the live dashboard here: **[Link to Online Reports Page](https://app.powerbi.com/view?r=eyJrIjoiMDE5N2U2ZTAtZDA2Zi00MDgyLWI0MjMtZTlkYjc1ODc0MWVkIiwidCI6ImY3NDM5NmYzLTgwMTUtNGI3NC1iNDY4LWNkYTA0NTEzZDg0YyJ9)**  

---

## **How to Use the Dashboard**  
1. Use slicers to filter data by region, product category, or time period.  
2. Navigate between pages using bookmarks and buttons.  
3. Drillthrough on products or returns charts for detailed insights.  
4. Toggle between light and dark modes for your viewing preference.

---

### **Copyright:**  
Project dataset created by ZeroAnalyst; it is a simulated company for learning purposes.

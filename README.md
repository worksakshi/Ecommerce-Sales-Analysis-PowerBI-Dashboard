# **Ecommerce Sales Analysis**

### **Data Model** 
![](https://github.com/worksakshi/Ecommerce-Sales-Analysis-PowerBI-Dashboard/blob/main/Data%20Model%20View.PNG)

### **Interactive Dashboard**  
![Insight_1](https://github.com/worksakshi/Ecommerce-Sales-Analysis-PowerBI-Dashboard/blob/main/image%201.PNG)
![Insight_2](https://github.com/worksakshi/Ecommerce-Sales-Analysis-PowerBI-Dashboard/blob/main/image%202.PNG)

---

## **Objective**  
Designed a scalable, interactive dashboard for an e-commerce business to monitor sales, payment insights, and product performance across countries and time periods. The dashboard is built on a robust data model and supports strategic decision-making by offering insights into revenue trends, payment behaviors, and regional performance.

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
- **Data Sources:**  CSV 
- **Tools:** Power BI, Power Query, DAX.  

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
1. Importance of a clean, star-schema data model for high performance in Power BI.
2. Techniques for using DAX to calculate time-based metrics and profit-related KPIs.
3. How to integrate external media like product and flag images dynamically.




   

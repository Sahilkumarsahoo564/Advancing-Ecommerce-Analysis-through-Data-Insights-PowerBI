z# **Advancing Ecommerce Analysis through Data Insights PowerBI**
![Image](https://github.com/user-attachments/assets/42c4ddd6-2278-44d1-ab4a-fb3cbee75791)

## **Objective**

The primary goal of this project is to create a comprehensive and interactive Power BI dashboard that:

- Explores the relationships between customer demographics and preferences to tailor personalized marketing strategies.
- Segment customers into meaningful groups to improve targeting and retention..
- Identify product performance trends, such as bestsellers and underperforming items.
- Analyze customer spending patterns to maximize sales opportunities and predict future behavior.
- Examine order fulfillment processes to reduce shipping costs and improve delivery times.
- Detect high-value orders and patterns in spending to allocate resources more effectively.

---

## **Key Features**

1. **Data Cleaning and Modeling**:
   - Addressed missing data, duplicate entries, and irrelevant data points.
   - Merged two datasets using the `CustomerID` as the key.
   - Created calculated columns and measures using DAX.
2. **Advanced Analysis**:
   - Categorised customers into spending tiers based on their total spending.
   - Analysed customer demographics (e.g., country distribution) and correlating these with spending habits.
   - Investigated the impact of membership status (e.g., VIP vs. Premium) on spending patterns and order frequency.
   - Identified top-selling products and analyzing their popularity across countries.
3. **Interactive Dashboard**:
   -  Allowed users to filter data by country to analyze regional sales performance and customer behavior.
   - Enabled filtering by membership type (e.g., VIP, Premium) to study spending patterns and loyalty.
   - Filtered sales, popularity, and trends based on product categories or specific products.
   - Provided a slicer for selecting custom date ranges (e.g.years) to analyze trends.
4. **Data Storytelling**:
   - Highlighted significant insights and trends through engaging visual elements.
   - Summarized findings in a narrative format to support decision-making.

---

## **Datasets**

### **EcommerceDataset1.xlsx**

- Contains Customer Name, Product details,Order details.  
**Key Columns**: `OrderID`, `CustomerName`, `Product`, `Quantity`, `UnitPrice`, `OrderDate`, `ShippingCost`, `CustomerID`.

### **EcommerceDataset2.xlsx**

- Includes Customer details, Purchase Date.  
**Key Columns**: `CustomerID`, `Customer Email`, `Country`, `Membership`, `Signup Date`, `Last Order Date`,`Total spent`,`Communication log`.

---

## **Dashboard Highlights**

### **Key Metrics**:

- The dashboard shows a breakdown of sales by country and product.
- It also shows the total value of sales by product.
- The dashboard provides insights into customer spending habits.

### **Advanced Insights**:

- Sales Trends and Seasonality.
- Customer Segmentation and Behaviour.
- Product Performance and Inventory.

### **Interactive Visualizations**:

- Year-over-Year Total Spent.
- Total Spent by Membership.
- Country Wise Purchased Quantity.
- Customer Spent Capacity.

---

## **Technologies Used**

- **Power BI**: Data modeling, DAX calculations, and interactive visualizations.
- **Excel**: Data preparation and cleaning.
- **DAX**: Advanced measures and calculated columns.

---

## **Future Enhancements**

1. **Automating Data Updates Using Power BI Service**  
   - Implement scheduled refresh in Power BI Service to ensure the dashboard always displays up-to-date data without manual intervention.

2. **Integrating More Datasets for Deeper Insights**  
   - Incorporate additional datasets, such as Customer feedback, Product claims, and regional Product metrics, to enhance the scope of analysis and provide a more comprehensive view.

3. **Enhancing the Predictive Model for Recovery Ratings**  
   - Improve the DAX-based predictive model by integrating machine learning models using Python or R scripts in Power BI.  
   - Add features like Product purchase history to increase prediction accuracy.

4. **Adding Real-Time Analytics for Hospital Capacity Needs**  
   - Leverage real-time data streams to predict Product occupancy and capacity requirements dynamically.  
   - Use tools like Azure Stream Analytics to feed real-time data into Power BI dashboards for actionable insights.



📊ZOMATO SALES PERFORMANCE ANALYSIS
==============================

Prepared by: [Your Name]  
Date: [Submission Date]  
Tool Used: Power BI  
File Type: Combined ZIP (.zip) containing all necessary project files

This project investigates Zomato’s order, menu, and restaurant data to evaluate business performance, understand customer purchasing behavior, and recommend strategies for growth. Power BI is used for cleaning, transforming, and visualizing the data. The dashboard includes dynamic filters, key performance indicators (KPIs), and multiple visuals to support decision-making.

🧾 FILES INCLUDED
==============================

- `Zomato_Report.pdf`: Full project report with executive summary, goals, visuals, and business recommendations  
- `dashboard_link.txt`: Link to published Power BI dashboard  
- `dashboard_instructions.txt`: Notes about filters, relationships, DAX logic (if needed)  
- `Zomato_Final.csv`: Final cleaned and joined dataset used in the dashboard (merged orders, restaurant, menu)  

🧪 DATA PREPARATION SUMMARY
==============================

**Original Tables:**
- `orders.csv`  
- `menu.csv`  
- `restaurant.csv`  

**Steps Taken:**
1. Joined tables using the `r_id` field:
   - `orders` joined to `restaurant`
   - `menu` joined to `restaurant`
2. Created a separate table `Avg Price` to calculate the average food price per restaurant
3. Estimated revenue using:  
   `Estimated Revenue = sales_qty * Avg Menu Price`
4. Cleaned data:
   - Converted `order_date` to date format
   - Ensured price and quantity fields were numeric
5. Created calculated measures and KPIs:
   - `Total Revenue`
   - `Total Orders`
   - `Total Quantity`
   - `Average Rating`

📈 VISUALIZATIONS IN DASHBOARD
==============================

**KPI Cards:**  
- Total Revenue (INR)  
- Total Orders  
- Total Quantity Sold  
- Average Rating

**Charts & Graphs:**
- **Revenue by City (Map Chart):** Highlights cities like Old Gurgaon and Electric City as top-performing locations  
- **Revenue by Restaurant (Bar Chart):** Identifies the highest-grossing restaurants in the dataset  
- **Top-Selling Food Items (Bar Chart):** Shows best-selling menu items such as North Indian Chinese  
- **Revenue Over Time (Line Chart):** Reveals seasonal trends—higher sales in January–April, dips from June–September  
- **Interactive Slicers:** Allow filtering by City, Restaurant, and Date  

📌 KEY INSIGHTS & RESULTS
==============================

- **City Performance:** Certain cities significantly outperform others in revenue generation  
- **Restaurant Contribution:** A small number of restaurants drive the majority of sales  
- **Popular Menu Items:** Sales are concentrated around a few popular dishes  
- **Time-Based Trends:** Seasonal dips suggest marketing opportunities during low periods  
- **Revenue Estimation:** Despite no `price` column in `orders`, revenue was reliably estimated using joined average prices  

💡 BUSINESS RECOMMENDATIONS
==============================

1. Expand efforts in top cities and strengthen those restaurant partnerships  
2. Feature high-performing dishes in promotions across regions  
3. Target low-sales periods with marketing campaigns  
4. Encourage high-performing restaurant practices across other partners  
5. Introduce loyalty programs focused on best-selling items  

🔧 DASHBOARD INSTRUCTIONS
==============================

1. Open Power BI link (from `dashboard_link.txt`)  
2. Use slicers (City, Restaurant, Date) to filter visuals  
3. Hover over visuals for tooltips and deeper insight  
4. All revenue is shown in INR (Indian Rupees)

⚠️ NOTES
==============================

- Data is cleaned and transformed within Power BI  
- All calculations are dynamic and update with slicer selections  
- Dashboard size and fields were optimized for performance and clarity  

END OF README
==============================

This README provides context for reviewers to understand the dataset, visuals, logic, and insights shared in the Power BI dashboard and project report.

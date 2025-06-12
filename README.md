Zomato Sales Performance Analysis
📊 Project Title: Zomato Sales Performance Analysis
This project investigates Zomato’s order, menu, and restaurant data to evaluate business performance, understand customer purchasing behavior, and recommend strategies for growth. Power BI is used for cleaning, transforming, and visualizing the data. The dashboard includes dynamic filters, key performance indicators (KPIs), and multiple visuals to support decision-making.

🧾 Files Included
Zomato_Report.pdf: Full project report with executive summary, goals, visuals, and business recommendations


dashboard_link.txt: Link to published Power BI dashboard


dashboard_instructions.txt: Notes about filters, relationships, DAX logic (if needed)


Zomato_Final.csv: Final cleaned and joined dataset used in the dashboard (merged orders, restaurant, menu)



🧪 Data Preparation Summary
Original Tables:
orders.csv


menu.csv


restaurant.csv


Steps Taken:
Joined tables using the r_id field:


orders joined to restaurant


menu joined to restaurant


Created a separate table Avg Price to calculate the average food price per restaurant


Estimated revenue using:
 Estimated Revenue = sales_qty * Avg Menu Price


Cleaned data:


Converted order_date to date format


Ensured price and quantity fields were numeric


Created calculated measures and KPIs:


Total Revenue


Total Orders


Total Quantity


Average Rating



📈 Visualizations in Dashboard
KPI Cards:
Total Revenue (INR)


Total Orders


Total Quantity Sold


Average Rating


Charts & Graphs:
Revenue by City (Map Chart): Highlights cities like Old Gurgaon and Electric City as top-performing locations


Revenue by Restaurant (Bar Chart): Identifies the highest-grossing restaurants in the dataset


Top-Selling Food Items (Bar Chart): Shows best-selling menu items such as North Indian Chinese


Revenue Over Time (Line Chart): Reveals seasonal trends—higher sales in January–April, dips from June–September


Interactive Slicers: Allow filtering by City, Restaurant, and Date



📌 Key Insights & Results
City Performance: Certain cities significantly outperform others in revenue generation


Restaurant Contribution: A small number of restaurants drive the majority of sales


Popular Menu Items: Sales are concentrated around a few popular dishes


Time-Based Trends: Seasonal dips suggest marketing opportunities during low periods


Revenue Estimation: Despite no price column in orders, revenue was reliably estimated using joined average prices



💡 Business Recommendations
Expand efforts in top cities and strengthen those restaurant partnerships


Feature high-performing dishes in promotions across regions


Target low-sales periods with marketing campaigns


Encourage high-performing restaurant practices across other partners


Introduce loyalty programs focused on best-selling items



🔧 Dashboard Instructions
Open Power BI link (from dashboard_link.txt)


Use slicers (City, Restaurant, Date) to filter visuals


Hover over visuals for tooltips and deeper insight


All revenue is shown in INR (Indian Rupees)



⚠️ Notes
Data is cleaned and transformed within Power BI


All calculations are dynamic and update with slicer selections

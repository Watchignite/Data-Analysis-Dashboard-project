# Data-Analysis-Dashboard-project
![zomato_logo](https://github.com/Watchignite/Data-Analysis-Dashboard-project/blob/main/zomato.svg)
## Overview
This project is an interactive Power BI dashboard built using Zomato’s sales, orders, category, and city-level data.
It visualizes key business metrics such as total sales, order quantity, ratings, category performance, top cities, and yearly sales trends using clean and modern UI elements.
## 🚀 Project Overview
The objective of this project is to analyze Zomato’s business performance using Power BI.
The dashboard provides insights into:
● Total Sales Amount<br>
● Total Quantity Sold<br>
● Total Ratings<br>
● Total Orders<br>
● Category-wise performance (Veg, Non-Veg, Others)<br>
● City-wise sales ranking<br>
● Yearly sales trend<br>
● Dynamic toggle between Amount & Quantity<br>
This dashboard helps users quickly understand customer behavior, top-performing locations, and overall business growth trends.
## 📈 Key Insights
● Electronic City ranks highest in sales quantity.<br>
● Veg category has the strongest performance with 156K quantity.<br>
● Sales peaked in 2018 and declined slightly after.<br>
● Strong customer engagement with 148K ratings.<br>
● Total sales amount crosses 987M.
## 🛠️ Technologies Used
● Power BI Desktop<br>
● Power Query<br>
● DAX (Data Analysis Expressions)<br>
● CSV Files/Excel  (Orders, Menu, Food Data)
## 📂 Project Files
Datasets are provided in the files of the repository
## 📷 Dashboard Preview
![image](https://github.com/Watchignite/Data-Analysis-Dashboard-project/blob/main/zomato_power%20BI.png)
## 📐 DAX Measures Used
● Total_Amount = SUM(Measure_Table[Sale_Value])<br>
● Total_Quantity = SUM(orders[Order_Count])<br>
● Total_Ratings = SUM(orders[Rating_Count])<br>
● Total_Orders = COUNT(orders[order_id])<br>
● TopN_values = RANKX(ALL(orders[city]),[Sale_value],,DESC)<br>                                                                                                      
etc
## 🌟 Features
● KPI Cards (Sales, Quantity, Ratings, Orders)<br>
● Category Images + Ratings<br>
● Top N City Bar Charts<br>
● Yearly Sales Line Chart<br>
● Modern UI with icons and custom visuals<br>
● Dynamic measures for Amount vs Quantity
## 📌 Future Enhancements
● Add map-based city analysis<br>
● Add forecast analytics<br>
● Add restaurant-level performance<br>
● Add user-level behavioral segmentation
## ✅ Conclusion & Findings
The Zomato Power BI Dashboard provides a clear and insightful overview of business performance across sales, orders, ratings, and city-wise demand. The analysis highlights the key areas contributing to growth and customer engagement while also revealing patterns in ordering behavior.<br>

Key Findings:<br>
● High Sales Performance:<br>
The total sales amount reached 987M, indicating strong business volume and high customer demand.<br>
● Top-Performing Cities:<br>
Electronic City leads in overall sales quantity, followed by Old Gurgaon and Gorakhpur, showing strong regional performance.<br>
● Category Insights:<br>
Veg category performs best with 156K+ orders,<br>
Non-Veg maintains a strong share with 140K,<br>
Other items contribute moderately.<br>
This indicates a balanced preference among customers with a slight inclination toward Veg items.<br>
● Customer Engagement:<br>
With 148K ratings, Zomato shows high customer interaction and feedback activity.<br>
● Yearly Sales Trend:<br>
Sales peaked in 2018 with 1M+,<br>
Gradual decline seen after 2018,<br>
Indicates potential market distribution changes or seasonal fluctuations.<br>
● Strong Operational Volume:<br>
Over 150K orders show consistent platform usage and strong user retention.
## ✅ Conclusion
This Power BI dashboard successfully consolidates complex Zomato datasets into a visually intuitive format that helps in understanding overall business health. It highlights customer preferences, top-performing locations, and yearly growth patterns. These insights can assist decision-makers in:<br>
● Improving regional marketing strategies<br>
● Strengthening food category offerings<br>
● Tracking business performance over time<br>
● Identifying high-potential locations for expansion<br>
Overall, the dashboard provides a comprehensive, data-driven view of Zomato’s operational and sales performance.
## 👨‍💻 Author
## Charan Reddy
💼 LinkedIn Profile : [Charan Kothur](https://www.linkedin.com/in/charankothur/)<br>
Data Analyst | Power BI Developer<br>
📍 India

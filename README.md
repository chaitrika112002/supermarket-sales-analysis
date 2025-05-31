📊 Supermarket Sales Analysis using Power BI
📌 Project Overview
This Power BI project provides a comprehensive analysis of supermarket sales data collected over a period of three months. The goal is to uncover key business insights around sales trends, customer behavior, payment preferences, product performance, and branch-level performance. This dashboard enables decision-makers to quickly interpret and act on sales data through interactive visualizations and slicers.

📁 Dataset
Source: Kaggle – Supermarket Sales Dataset

Format: CSV

Fields: Invoice ID, Branch, City, Customer Type, Gender, Product Line, Unit Price, Quantity, Tax, Total, Date, Time, Payment, COGS, Rating

⚙️ Tools & Technologies Used
Power BI

Power Query – for data cleaning and transformation

DAX – for calculated measures (e.g., Total Sales, Total Transactions)

Interactive Slicers – for dynamic filtering of dashboard views

🧠 Key Insights
Total Transactions: 1000

Total Sales: ₹322.97K

Sales Trend: February shows a dip in sales compared to January and March.

Customer Segmentation:

Sales from Female customers (53.68%) are slightly higher than Male (46.32%).

Member customers contribute more to total sales than Normal.

Product Line Performance:

Best-Selling: Food and Beverages (56K)

Lowest-Selling: Health and Beauty (49K)

Branch Performance:

Chennai leads with ₹110.57K in sales.

All three branches (Chennai, Hyderabad, Bangalore) contribute almost equally.

Payment Preferences:

Credit Card is the most used payment method (34.74%).

Cash is the least preferred method (31.2%).

🧭 Dashboard Features
| Section                      | Description                                                                   |
| ---------------------------- | ----------------------------------------------------------------------------- |
| **KPIs**                     | Total Transactions and Total Sales                                            |
| **Slicers**                  | Customer Type (Member/Normal)- Branch (Chennai, Hyderabad, Bangalore)         |
| **Sales Trend Analysis**     | Line chart showing monthly sales fluctuations                                 |
| **Customer Segmentation**    | 100% stacked bar chart for Gender and Customer Type-wise sales                |
| **Product Line Performance** | Horizontal bar chart comparing total sales by product line                    |
| **Branch Performance**       | Pie chart displaying branch-wise contribution to total sales                  |
| **Payment Method Analysis**  | Donut chart highlighting usage of different payment methods                   |


🛠️ Project Workflow
Data Import
Imported the dataset into Power BI as a single flat table.

Data Cleaning (Power Query)

Checked and corrected data types

Handled inconsistencies

Created DAX measures for Total Sales, Total Transactions

Visualization

Used cards, bar charts, pie charts, line graphs, and donut charts

Applied consistent color schemes and intuitive layout

Interactivity

Enabled dynamic filtering using slicers for Customer Type and Branch

🧾 File Structure
text
Copy
Edit
📁 supermarket-sales-powerbi
├── 📊 Supermarket Sales Dashboard.pbix
├── 📄 README.md
├── supermarket_sales.csv
└── 📷 supermarket-sales-dashboard.png
🚀 How to Use
Download or clone this repository.

Open the .pbix file in Power BI Desktop.

Refresh the data if needed.

Use the slicers to interactively explore insights by city and customer type.

🙋‍♀️ Author
Muthyala Chaitrika – Aspiring Data Analyst
📫 Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/chaitrikamuthyala/).
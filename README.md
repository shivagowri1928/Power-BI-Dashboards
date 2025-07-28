# Power-BI-Dashboards
Blinkit Sales Anaysis Dashboard
Problem Statement
The Blinkit Sales Analysis Power BI project aims to provide an insightful and interactive dashboard for analyzing sales performance across various dimensions. ​

This project will facilitate data-driven decision-making by visualizing key metrics, identifying trends, and uncovering actionable insights within Blinkit's sales data.​

The project will empower stakeholders with valuable insights into sales performance, enabling informed decision-making and strategic planning.​


Metrics = {
("Total Sales", NAMEOF('BlinkIT Grocery Data'[Total Sales]), 0),
("Avg Sales", NAMEOF('BlinkIT Grocery Data'[Avg Sales]), 1),
("Avg Rating", NAMEOF('BlinkIT Grocery Data'[Avg Rating]), 2),
("No of Items", NAMEOF('BlinkIT Grocery Data'[No of Items]), 3)
}


Insights
A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

[1] Total Number of Sales = $1.20M
Highest number of Sales = Fruits & Vegetables ($178.12K)

Lowest number of Sales = Seafoods ($9.08K)

Highest number of Sales by outlet size = Medium size($507.9K)

Lowset number of Sales by outlet size = High ($248.99K)

[2] Average Ratings
a) Meat - 4.0/5

b) Fruits & Vegetables - 3.91/5

c) Hpousehold - 3.95/5
d) Health & Hygiene - 3.93/5
e) Soft Drinks - 3.89/5
f) Hard Drinks - 3.84/5
g) Baking Goods - 3.95/5
h) Frozen Foods - 3.93/5
i) Dairy - 3.92/5
j) Seafood - 3.91/5
k) Starchy Foods - 3.91/5
l) Breads - 3.83/5
m) Breakfast - 3.90/5
n) Snack Foods - 3.90/5
o) Canned - 3.95/5
p) Others - 3.93/5
while calculating average rating, null values have been ignored as they were not relevant for some customers.

These ratings will change if different visual filters will be applied.

[3] Some other insights
Total 8523 items sold by different outlets at different location.​

Items with Low fat content have the highest sales of 776.32K compared to regular fat i.e., 425.36K.​

Data reveals that sales reached their peak in 2018, highlighting it as the highest-performing year in terms of revenue generation.​

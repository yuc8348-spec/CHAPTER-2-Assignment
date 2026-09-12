CHAPTER-2-Assignment
Problem-AI Solution Worksheet
Part 1 — Understand the Business Problem
A grocery store needs to know how much milk customers will buy each day. The manager currently uses past experience to decide how much milk to order. Sometimes, the store orders too much milk, and it expires. Sometimes, the store orders too little milk and runs out. AI could use past sales data to help predict how much milk customers will buy.
2. Why is this problem important to the organization?
This problem affects the store’s costs and sales. The store loses money when it throws away expired milk. Customers may shop somewhere else if milk is not available. Better forecasts can help the store order the right amount. This can reduce waste and keep customers happy.
3. Who is affected by this problem?
Customers: They want milk to be available.
Managers: They decide how much milk to order.
Employees: They stock shelves and remove expired milk.
Finance team: They track costs, sales, and profit.
Suppliers: They prepare and deliver the store’s orders.
Part 2 — Identify the Data
Question
What data would you need?
Daily milk sales, prices, discounts, milk available in the store, and dates when milk sold out.
Where could the data come from?
Sales records, inventory records, order records, discount plans, and a holiday calendar.
How much historical data might be useful?
Two to three years of daily data could be useful, if available. This could show patterns across different weeks and seasons.
What would be the most important variables?
Recent sales, day of the week, month, holidays, planned prices, and planned discounts.
What could be missing or inaccurate?
Some sales could be missing or recorded twice. Prices could be wrong. The store might not record when milk sold out.
Part 3 — Identify Features and Target
What information would you give the model?
The features would be: Number of milk cartons sold yesterday.
Average daily milk sales during the past seven days.
Tomorrow’s day of the week. Month of the year.
Whether tomorrow is a holiday.
Planned milk price for tomorrow.
Whether a discount is planned for tomorrow.
All these features would be available before the model makes its forecast.
What would you want the model to determine?
The target is the number of milk cartons customers are expected to buy tomorrow, if the store has enough milk.
For training, the store could use daily sales from days when milk did not sell out. Sales on days when milk sold out may not show how much customers wanted to buy.
Part 4 — Select the AI/ML Approach
Would you use supervised or unsupervised learning?
Supervised Learning
I choose supervised learning because past sales provide known results. The model connects these results with features such as prices and holidays. It learns patterns to estimate future demand. Days when milk sold out need checking because sales may be lower than demand.
Classification or prediction: Prediction
I choose prediction because the output is a number. The model estimates tomorrow’s milk demand. For example, it may predict 80 cartons. A regression model can predict this amount.
Part 5 — Data Quality and Business Impact
Three possible data-quality problems
Missing sales: Some purchases are not recorded.
Duplicate records: The same purchase is recorded twice.
Incorrect inventory: Records show milk is available when it has sold out.
What could happen if the data is poor? Poor data can cause wrong forecasts. Missing sales may lead the manager to order too little milk. Duplicate sales may lead the manager to order too much milk. These mistakes can cause shortages, waste, and lost profit. 
Part 6 — AI Solution Summary Business Problem Predict daily milk demand. Data Needed Sales, prices, discounts, inventory, stockout dates, and calendar data. AI/ML Approach Regression to predict a quantity. Type of Learning Supervised learning. Model Output Expected milk cartons purchased tomorrow, assuming enough stock. Business Benefit Less waste, fewer shortages, and happier customers. Potential Risk Wrong forecasts may cause poor orders. Managers should also check stock, expiration dates, and delivery times.

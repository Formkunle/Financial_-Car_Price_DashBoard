# Financial_Car_Price_DashBoard
# Introduction
The automotive industry relies heavily on data to track vehicle sales, pricing trends, and market demand. This project aims to analyze a dataset containing vehicle sales information, including details such as the year, make, model, trim, body type, transmission, VIN, state, condition, odometer reading, color, interior features, seller, market value (MMR), selling price, and sales date. By leveraging this data, we seek to uncover insights that can assist in pricing strategy, demand forecasting, and market trends analysis.
# Exploration of the Dataset
The dataset contains vehicle-related information, including details about their specifications, conditions, and sales transactions. The dataset comprises the following key columns:
1.	Year – The manufacturing year of the vehicle.
2.	Make – The brand or manufacturer of the vehicle (e.g., Toyota, Honda).
3.	Model – The specific model of the vehicle (e.g., Camry, Civic).
4.	Trim – The version or sub-model of the vehicle with different features.
5.	Body – The body type of the vehicle (e.g., Sedan, SUV, Truck).
6.	Transmission – The type of transmission system (e.g., Automatic, Manual).
7.	VIN (Vehicle Identification Number) – A unique identifier assigned to each vehicle.
8.	State – The location where the vehicle was sold or registered.
9.	Condition – The state of the vehicle at the time of sale (e.g., new, used, damaged).
10.	Odometer – The mileage of the vehicle, indicating how much it has been driven.
11.	Color – The exterior color of the vehicle.
12.	Interior – The color or material of the vehicle’s interior.
13.	Seller – The individual or organization that sold the vehicle.
14.	MMR (Manheim Market Report) – A market value estimate for the vehicle based on auction data.
15.	Selling Price – The final price at which the vehicle was sold.
16.	Sales Date – The date when the vehicle transaction took place.

# Initial Observations
•	The dataset provides insights into vehicle sales patterns, pricing trends, and vehicle conditions.
•	Some columns, such as VIN and seller, may contain unique values, making them useful for tracking individual transactions.
•	The sales date column enables time-series analysis, allowing us to examine trends in vehicle sales over time.
•	The odometer and condition fields help determine how mileage and vehicle condition influence pricing.
•	The MMR and selling price fields can be used to compare expected market value vs. actual selling price.
# Objectives
The primary objectives of this project include:
1.	Data Cleaning & Preparation: Ensure the dataset is structured, complete, and free from inconsistencies.
2.	Price Analysis: Determine how various factors influence car prices and market values.
3.	Demand Insights: Identify the most popular car makes, models, and trims based on sales trends.
4.	Condition vs. Pricing: Assess the impact of car condition and mileage on pricing.
5.	Market Trends: Analyze regional sales patterns to understand geographic demand variations.

# Interpretation
![Car Dashboard](./Car%20Price%20Dashboard.png)
1. Key Performance Indicators (KPIs)
- Total Cars Sold: 331K units.
- Total Sales Price: 4541M (or $4.541 billion).
- Average Sales Price: 13.70K ($13,700 per car on average).
2. Most Profitable Car Models
- Top 3 Most Profitable Models:
-	Rolls-Royce (155,254 in revenue).
-	Ferrari (131,250 in revenue).
-	Lamborghini (111,500 in revenue).
-	Luxury brands dominate the list, indicating that high-end cars contribute significantly to profits.
3. Most Sold Car Brands
-	Ford (56,321 units) is the highest-selling brand, followed by Chevrolet (7,861 units) and Toyota (6,154 units).
-	Ford dominates in volume, but luxury brands dominate profitability.
4. Total Car Sales Over the Years
-	Sales increased from 36,253 in 2014 to 295,094 in 2015.
-	This is an increase of +258,841 sales, which is about 714% growth.
5. Most Profitable Car Models by State
-	The top states contribute between 10K - 29K in total revenue, suggesting an uneven distribution of profitability across different regions.
6. Seller Contribution to Total Sales
-	Ford Motor Credit Company LLC (12,665 units), Hertz (10,962 units), and Nissan Infiniti (10,277 units) are the leading sellers.
-	Indicates that corporate sales play a crucial role in total volume.
7. Impact of Mileage on Price
-	Low-mileage cars (0 - 20K miles) fetch the highest average price (21.48K).
-	Cars with over 100K miles have the lowest price (~5K).
-	Depreciation is significant as mileage increases, meaning lower-mileage cars are valued more.
# Conclusion
1.	High-end luxury brands (Rolls-Royce, Ferrari, Lamborghini) are the most profitable, but economy brands (Ford, Chevrolet, Toyota) dominate in sales volume.
2.	Sales peaked in 2015 and dropped sharply, suggesting external factors like market conditions or consumer demand shifts.
3.	Corporate sellers (Ford Motor Credit, Hertz, Nissan Infiniti) contribute significantly to total sales, indicating strong reliance on fleet or leasing markets.
4.	Lower mileage cars (0 - 20K miles) retain higher prices, while higher-mileage vehicles experience significant depreciation.
# Recommendations
# For Increasing Sales
-	Diversify sales strategies: Since luxury cars dominate profitability but not volume, consider targeting a broader customer base with mid-range cars.
-	Revisit marketing and sales tactics: The sharp drop in sales post-2015 suggests that either demand declined or competition increased.
-	Strengthen partnerships with fleet companies: Fleet sales (Ford Credit, Hertz, Nissan Infiniti) drive a large portion of sales—expanding partnerships with leasing/rental companies could boost sales.
# For Profit Maximization
-	Capitalize on luxury brand sales: Since high-end brands dominate profitability, focus on marketing and after-sales services for luxury buyers.
-	Leverage low-mileage car demand: Since cars with 0 - 20K miles sell at the highest prices, promote certified pre-owned (CPO) vehicles to attract buyers looking for near-new cars.
-	Consider pricing strategies for high-mileage cars: Cars with 100K+ miles sell for very low prices, so alternative revenue streams like extended warranties or financing options could increase margins.
# Final Thought
-	This dashboard provides valuable insights into sales trends, profitability, and pricing factors. By refining sales strategies, marketing focus, and pricing models, the business can boost both total sales and profit margins.

# Thanks
Email :- adekunletimothy92@gmail.com
Linkedin :- www.linkedin.com/in/timothyadekunle1992

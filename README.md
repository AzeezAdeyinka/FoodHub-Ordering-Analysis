# FoodHub-Ordering-Analysis

### Table of Contents
- [Background of study](background-of-study)
- [Objective](objective)
- [Tools](tools)
- [Data Dictionary](data-dictionary)
- [Data Analysis](data-analysis)
- [Results](result)
- [Recommendation](recommendation)

### Background of Study
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app. 
The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants. 

### Objective
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Analyst in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business.

### Tools
- Microsoft Excel

### Data Dictionary
- order_id: Unique ID of the order
- customer_id: ID of the customer who ordered the food 
- restaurant_name: Name of the restaurant 
- cuisine_type: Cuisine ordered by the customer 
- cost: Cost of the order 
- day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday) 
- rating: Rating given by the customer out of 5 
- food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation. 
- delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

### Data Analysis
Rating Analysis of Customers
How many customers did not rate?
=COUNTIF(G1:G1899, "not given") 736

### Results
- The analysis of the FoodHub dataset provides valuable insights into customer behavior,
restaurant performance, and cuisine preferences. The transaction data shows a clear distribution
of orders, customers, and restaurants, giving a solid understanding of food ordering patterns.
- The top four customers who placed the highest number of orders were identified, highlighting
their loyalty to FoodHub. Specific meals stood out as the most popular during weekends,
reflecting customer preferences and a significant increase in orders on Saturdays and Sundays.
This suggests an opportunity to focus on marketing and resources during these peak periods.
- Restaurants with ratings below 4 were flagged for potential removal due to their impact on
customer satisfaction. In contrast, highly-rated restaurants, like Shake Shack, which emerged as
the most frequently ordered and highest-rated, were prioritized for operations.
- Cuisine analysis revealed the most commonly ordered types and their average preparation times,
providing actionable insights to streamline kitchen processes and improve delivery efficiency.

### Recommendation
I noticed good ordering during weekends to weekdays, I will Implement a weekend-specific
marketing strategy to capitalize on high-demand meals. Secondly, I will introduce a discount to
the top customers to retain customers and increase orders, I will recommend a change in cost
around cuisine with a high average cost and a change in the variety of meals to attract more
customers in areas with low orders. I will recommend proper logistics methods to avoid delays in
delivery time.



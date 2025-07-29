# Transportation Cost And Delivery Analysis

## Project Overview
This project analyzes transportation cost and delivery time using supply chain data from a fashion and beauty startup. It focuses on the flow of goods across two main segment:

1. From manufacturer to supplier distribution centre
2. From supplier distribution centre to customers

An interactive Power BI dashboard help monitors and break down the transportation cost spending, determine the cost patterns, delivery performance and highlighted areas of improvement.

## Objectives

- Identify total transportation cost by transportation mode and routes.

- Determine the most frequently transportation mode used for deliveries to distribution centres.

- Compare the cost and delivery lead time of each transportation mode.

- Compare the average shipping cost and delivery time to customers.

## Data Source
 
 - Dataset Name: Supply Chain Data
- Source: Kaggle
- Data Format: CSV
- Raw Data Download Link: [*Supply Chain Data (Kaggle)*](https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis/data) 
- Cleaned Data Download: [*Supply Chain Cleaned Data*](https://github.com/azerinnan/Transportation_cost_and_delivery_analysis/blob/main/supplychain_cleaned_data.csv)

The original data is cleaned and formated in a previous project.
Click [*here*](https://github.com/azerinnan/EDA_supplychain) to view the project.






## Key Visuals and Features
- **Slicer - Distribution Centre Location**

	Filter all visual by location to compare transportation cost to and from distribution centre.

- **Cards - Cost Summary**
	
	Displays the total and average of transportation and shipping cost, and average shipping times.

- **Line and Clustered Column  – Cost Distribution and Transportation Mode Usage**

	Visualizes percentage of total cost per transportation mode and the frequency of usage for each mode.

- **Pivot table – Transportation Mode vs Route**
	
	Shows the cost and average lead time for each transpotation mode across different routes.

- **Clustered Column Chart - Average Shipping Cost and Times by Carrier**

	Compare average shipping costs and delivery times accross different carriers.


## Visual Analysis

![Transportation Cost and Delivery Analysis Dashboard](1_cost_delivery_dashboard.png)

View the Transportaion Cost and Delivery Analysis here: [*Dashboard*](https://github.com/azerinnan/Transportation_cost_and_delivery_analysis/blob/main/transportation_cost_and_delivery_analysis.pbix)

Insights: 

- The total cost of transportation to distribution centre is Rupees 52.92k, with an average of Rupees 529.25 per shipment.

- Road is the most commonly used transportation mode, contributing 30.32% of total cost to distribution centres, followed by train at 28.66%. Due to geographical factors and infrastructural lanscape of India, these two modes serve as the main transports for economic activities.

- The average delivery lead time to distribution centre is 16 days and around 18 days for air freight. Customs clearance, security checks and complexity of procedure using air freight are likely caused for longer delivery period.

- Since road and rail are the most utilized and flexible transport modes, Route C (Road) and Route A (Rail) are the most efficient option due to their faster delivery times and lower costs compared to the other routes.

- For deliveries from distribution centre to customers, the average cost per delivery is Rupees 5.55, with an average of shipping times of 6 days. 

- Distribution centre in Bangalore and Delhi benefits from using Carrier B which offers lower costs and faster delivery compared to other carriers.

- In Mumbai, although the delivery cost to customers are similar across carriers, Carrier A is preferable for faster delivery.


## Recommendations

1. Adopt Multimodal Transports strategies
 
	- Combine road and sea transport for deliveries to distribution centres located near seaports.
	- Sea transport has the lowest average cost among all modes, integrating it with road transports helps optimize cost efficiency and delivery times.

2. Prioritize Sea Transport for Non-Urgent Shipments
	- Increase the use of sea transport for non-urgent deliveries to distribution centre help to reduce logistics costs.
	- This inidcates cost analysis provides significant cost saving when delivery urgency is low.

3. Carrier optimization for final delivery

	- Each distribution centre should assign a primary carrier based on lowest cost per delivery and fastest average lead time.
	- A backup carrier should be designated for urgent orders and peak seasons to ensure contuinity of service to customers.


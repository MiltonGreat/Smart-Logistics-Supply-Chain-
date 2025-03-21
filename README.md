# Smart Logistics Supply Chain

## Project Overview

This project optimizes supply chain operations by analyzing various aspects of logistics management. The dataset includes real-time data from IoT sensors, environmental conditions, traffic statuses, and user behaviors, enabling advanced analytics and machine learning applications to improve logistics efficiency. The goal is to identify key factors contributing to delays, optimize asset utilization, and enhance overall supply chain performance.

### Dataset Description

The dataset provides real-time data for smart logistics operations over the past year (2024). It includes information on asset tracking, inventory levels, shipment statuses, environmental conditions, traffic, and user behaviors. The data is enriched with IoT sensor data, such as temperature, humidity, and asset utilization, to facilitate advanced logistics optimization and decision-making.

Key Features:

- Timestamp: Date and time of logistics activity.
- Asset_ID: Unique identifier for logistical assets (e.g., trucks).
- Latitude & Longitude: Geographical coordinates for asset tracking.
- Inventory_Level: Current inventory level associated with the asset or shipment.
- Shipment_Status: Status of the shipment (e.g., In Transit, Delivered, Delayed).
- Temperature: Temperature recorded during transportation.
- Humidity: Humidity level at the time of recording.
- Traffic_Status: Current traffic condition (e.g., Clear, Heavy, Detour).
- Waiting_Time: Time spent waiting during logistics (in minutes).
- User_Transaction_Amount: Monetary amount associated with user transactions.
- User_Purchase_Frequency: Frequency of purchases made by the user.
- Logistics_Delay_Reason: Reason for delays (e.g., Weather, Mechanical Failure).
- Asset_Utilization: Percentage of asset utilization.
- Demand_Forecast: Predicted demand for logistics services.
- Logistics_Delay (Target): Binary variable indicating whether a delay occurred (1 for delay, 0 for no delay).

### Project Objectives

1. Exploratory Data Analysis (EDA):
- Analyze the distribution of key features such as delays, asset utilization, and environmental conditions.
- Identify patterns and correlations between variables.

2. Clustering:
- Group data into clusters based on environmental conditions, traffic status, and asset utilization to identify common delay scenarios.

3. Association Rule Mining:
- Discover relationships between traffic conditions, delay reasons, and other factors to improve delay prediction.

4. Anomaly Detection:
- Identify unusual patterns in waiting times, asset utilization, and delays using Isolation Forest and Autoencoder models.

5. Predictive Modeling:
- Build classification models to predict shipment status and regression models to optimize inventory levels.
- Evaluate model performance and identify areas for improvement.

6. Geospatial Analysis:
- Analyze regional delays and recommend strategies to improve logistics efficiency in high-delay areas.

7. Customer Behavior Analysis:
- Segment users based on transaction amounts and purchase frequency to understand their impact on logistics delays.

### Key Findings

High Logistics Delay Rate (56%):
- The most common delay reasons are weather, traffic, and mechanical failure.
- Heavy traffic causes the most severe delays (100% logistics delay).

Clustering Analysis:
- Three clusters were identified based on temperature, humidity, asset utilization, and traffic conditions, highlighting the interplay between environmental factors and operational efficiency.

Association Rule Mining:
- Strong associations were found between traffic conditions and delay reasons, particularly weather and traffic congestion.

Anomaly Detection:
- Anomalies in waiting times and asset utilization were detected, indicating inefficiencies in logistics operations.

Shipment Status Prediction:
- Models achieved moderate accuracy (76%), with traffic status and waiting time being the most influential features.

Inventory Level Optimization:
- Regression models performed poorly, indicating weak relationships between features and inventory levels.
- The 75th percentile of asset utilization (89.43%) was identified as a benchmark for optimal performance.

Geospatial Analysis:
- Regions with the highest delays were identified, with weather and traffic being the primary causes.

Customer Behavior Analysis:
- High spenders and frequent users experienced fewer delays, while rare and occasional users faced higher delays.

### Recommendations

1. Mitigate Delays:
- Focus on regions and conditions with the highest delays, particularly those caused by weather and traffic.
- Implement real-time monitoring systems to predict and mitigate delays.

2. Optimize Asset Utilization:
- Aim to achieve the 75th percentile benchmark (89.43%) for asset utilization by improving inventory management and demand forecasting.

3. Improve Predictive Models:
- Enhance feature selection and engineering to improve the performance of predictive models for shipment status and inventory levels.

4. Enhance Customer Experience:
- Prioritize logistics resources for rare and occasional users to reduce delays and improve satisfaction.

5. Leverage Geospatial Insights:
- Focus on high-delay regions by improving weather-related contingency planning and maintenance systems.

6. Address Anomalies:
- Investigate instances of unusually long waiting times and underutilized assets to identify and resolve inefficiencies.

### Source

https://www.kaggle.com/datasets/ziya07/smart-logistics-supply-chain-dataset

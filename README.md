 Zomato Data Analysis Project
This project involves analyzing customer and restaurant behavior on Zomato's food delivery platform, which serves an average of 1.75 million monthly transaction customers and hosts over 208,000 to 226,000 monthly active food delivery restaurants.
The analysis focuses on answering key business questions related to customer preferences, restaurant performance, and ordering behavior, enabling Zomato to make data-driven decisions for improving its platform.
📊 Objective
As a data professional, your task is to analyze the provided Zomato dataset using exploratory data analysis (EDA) and visualization techniques to extract meaningful insights and answer business-critical questions.
📌 Business Questions to Answer
Which restaurants receive the majority of customer orders?
How many votes has each type of restaurant received from customers?
What are the common ratings that the majority of restaurants have received?
What type of cuisine or restaurant do couples prefer to order the most from online?
Which restaurants that offer online delivery have received the highest ratings?
Which type of restaurants receive more offline orders compared to online ones?
📁 Dataset Overview
The dataset includes (but may not be limited to) the following columns:
Restaurant Name
Cuisines
Votes
Aggregate Rating
Online Order (Yes/No)
Table Booking
Cost for Two
Type (e.g., Casual Dining, Café, Quick Bites)
Location
Meal for Couple (Yes/No)
📌 Note: Column names and structure may vary slightly based on the source dataset. Preprocessing and cleaning are part of the workflow.
🧰 Tech StackLanguage: Python
Libraries:
Pandas, NumPy for data manipulation
Matplotlib, Seaborn, Plotly for data visualization
IDE: Jupyter Notebook / Google Colab
📊 Key Tasks Performed
Data cleaning: null handling, data type conversion
Feature engineering: deriving new columns for analysis
Exploratory Data Analysis (EDA)
Visualizations: bar charts, pie charts, scatter plots, heatmaps
Business insights and recommendations
project Structure
zomato-data-analysis/
├── data/
│   └── zomato_dataset.csv
├── notebooks/
│   └── zomato_eda.ipynb
├── images/
│   └── rating_distribution.png
├── README.md
└── requirements.txt
📌 Final Conclusion
1.The majority of restaurants on Zomato fall under the Dining category.
2.Most restaurants have received ratings between 3.5 and 4, indicating overall good customer satisfaction.
3.Couples primarily prefer restaurants with an approximate cost of ₹300, making affordability a key factor.
4.Restaurants that accept offline orders tend to receive lower ratings compared to those offering online delivery.
5.Dining restaurants are more likely to accept offline orders, whereas cafés predominantly receive online orders.
6.This suggests that customers prefer to dine in at full-service restaurants, while they favor online ordering when it comes to casual and quick-service places like cafés.



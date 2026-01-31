me file

# Food Delivery Data Analysis 


This project focuses on integrating and analyzing food delivery data collected from multiple sources. The objective is to combine transactional, user, and restaurant data to generate meaningful insights related to user behavior, revenue trends, city-wise and cuisine-wise performance, and membership impact.

The entire analysis is performed using **Google Colab**, **Python**, and **Pandas**.



The project uses three different data formats to simulate real-world systems:

- **orders.csv** – Transactional order data  
- **users.json** – User master data (membership, city, user details)  
- **restaurants.sql** – Restaurant master data (cuisine, rating, restaurant info)



The datasets are merged using **LEFT JOINs** to ensure all orders are retained.

:
- `orders.user_id` → `users.user_id`
- `orders.restaurant_id` → `restaurants.restaurant_id`



- Python  
- Google Colab  
- Pandas  
- SQLite  
- GitHub  

- Order trends over time  
- User behavior patterns  
- City-wise and cuisine-wise performance  
- Membership impact (Gold vs Regular users)  
- Revenue distribution and seasonality  
- MCQ-based and numerical business analysis  


- **Final merged dataset:** `final_food_delivery_dataset.csv`
- **Analysis Notebook:** Jupyter Notebook (`.ipynb`)



1. Open the Jupyter Notebook in Google Colab or Jupyter Lab  
2. Upload the datasets (`orders.csv`, `users.json`, `restaurants.sql`)  
3. Run all cells sequentially  
4. View analysis results and insights  


- Handling multiple data formats (CSV, JSON, SQL)
- Performing data joins using Pandas
- Exploratory Data Analysis (EDA)
- Generating insights from real-world-like datasets
- 
This project was developed as part of a hackathon / internship assessment to demonstrate practical data analysis and integration skills.

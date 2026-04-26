# Swiggy Restaurant Analytics & Interactive BI Dashboard

This project analyzes the Indian food delivery landscape using a dataset of over 8,600 restaurants from Swiggy. It combines cloud‑based data processing in Google Colab with interactive visualization in Power BI to explore culinary trends, pricing strategies, and customer ratings across major Indian cities.

## Project Overview

The goal of this project is to identify the key factors that contribute to a restaurant’s success on the Swiggy platform. By analyzing city‑wise distribution, average meal prices, and rating patterns, it provides a data‑driven overview of the competitive food delivery market.

## Key Features

- Automated Data Cleaning: Developed in Google Colab, the Python pipeline handles missing values, standardizes restaurant metadata, and performs feature engineering (for example, Restaurant_name_length).  
- Geographic Analysis: Insights grouped by City and Area (e.g., Bangalore, Ahmedabad, Pune) to assess regional market saturation and demand.  
- Statistical Profiling: Exploration of relationships between Price for Two, Average Ratings, and Total Ratings to understand customer behavior.  
- Interactive Power BI Dashboard: A Final Dash report featuring:
  - Slicers for City and Food type (e.g., Biryani, Chinese, North Indian).  
  - Heatmaps and bar charts for price vs. rating distribution.  
  - Leaderboards of top‑performing restaurants.

## Tech Stack

- Environment: Google Colab  
- Analysis: Python (Pandas, NumPy)  
- Visualization: Power BI Desktop  
- Data structure: ID, Area, City, Restaurant, Price, Avg ratings, Total ratings, Food type, Address, Restaurant_name_length

## File Structure

- swiggy.ipynb – Primary Google Colab notebook with data exploration and cleaning logic.  
- swiggy_cleaned_data.csv – Cleaned dataset containing 8,600+ records, ready for analysis or modeling.  
- final_dash.pbix – Power BI dashboard file that delivers the final visual storytelling layer.

## Key Insights

- Price vs. Rating: Identification of an optimal sweet spot price range associated with higher review volumes and positive ratings.  
- Cuisine Popularity: Mapping which food types (e.g., North Indian vs. Chinese) dominate specific urban areas.  
- Operational Metrics: Initial analysis of how listing attributes (such as restaurant name complexity and location) may correlate with total rating counts.

## How to Use

- Process: Open swiggy.ipynb in Google Colab to reproduce the full data‑cleaning and transformation pipeline.  
- Visualize: Open final_dash.pbix in Power BI Desktop to interact with city‑wise filters and performance metrics.  
- Explore: Use swiggy_cleaned_data.csv for further statistical analysis or machine‑learning experiments.

This project demonstrates a complete Data Analyst workflow: Cloud‑based EDA (Python/Colab) → Data Refinement → Business Intelligence (Power BI).

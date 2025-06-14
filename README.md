# Data Analysis Projects

 # Overview
 
 This repository contains various data analysis projects covering different domains such as sports, sales, customer behavior, entertainment, and global demographics. The projects leverage Python and its powerful libraries to extract insights from datasets, visualize trends, and generate meaningful conclusions.

 # Projects
 # 1. Apple Sales Analysis
  
   <h3>Objective : </h3>Analyze Apple product sales data to understand market trends and revenue distribution.
    <h3>Key Insights : </h3>
   Yearly sales trends<br>
   Most profitable products<br>
   Regional sales variations<br>
   <h3>Tools Used:</h3>Pandas, Matplotlib, Seaborn

  # 2. 🍽️ Zomato Data Analysis Project

This project performs an exploratory data analysis (EDA) on a Zomato restaurant dataset to extract insights about restaurant types, ratings, cost preferences, and online ordering behavior in India.

## 📊 Objective

To uncover patterns and insights from restaurant data that can help customers, business owners, or marketing strategists understand user preferences and operational trends.

## 🧰 Tools & Libraries Used

- **Python** 🐍
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Advanced visualization and statistical plotting

## 📁 Dataset Overview

The dataset used is `Zomato data.csv` and contains details such as:
- Restaurant names
- Ratings
- Votes
- Type of service (Delivery, Dine-out, etc.)
- Average cost for two
- Online ordering availability
- Cuisine and locality info

## 🧪 Key Steps Performed

### 1. Data Cleaning & Preparation
- Removed unnecessary columns
- Converted rating data from string (e.g., `"4.1/5"`) to float
- Handled null and inconsistent values

### 2. Data Visualization & Insights
- **Restaurant Type Analysis:** Majority are in the *Dining* category.
- **Votes by Type:** Dining restaurants receive the highest number of votes.
- **Rating Distribution:** Most ratings fall between 3.5 to 4.5.
- **Cost Analysis:** Couples prefer restaurants with average cost around ₹300.
- **Online vs Offline Rating:** Online orders receive better ratings than offline.
- **Heatmap:** Online order preference by restaurant type.

## 📌 Conclusions

- **Dining** is the most popular and highest-rated type of restaurant.
- People tend to spend moderately (around ₹300) when dining.
- Online ordering generally leads to better customer satisfaction.
- Visual tools like boxplots and heatmaps helped confirm trends.

## 📎 How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/zomato-analysis.git
   cd zomato-analysis

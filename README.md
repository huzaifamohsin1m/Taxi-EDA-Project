# Taxi-EDA-Project
Exploratory Data Analysis on NYC Taxi Dataset (March 2019)
# 🚖 NYC Taxi EDA Project — March 2019

Exploratory Data Analysis (EDA) of NYC Yellow Taxi rides for March 2019, uncovering hidden patterns in passenger behavior, fare distribution, tip trends, and peak ride times.

## 📊 Project Overview

This project explores a real-world NYC Taxi dataset through Python-based data analysis and visualization. The goal is to extract actionable insights from taxi ride data using techniques such as univariate, bivariate, and multivariate analysis, while also polishing and visualizing the results for presentation-ready output.

📌 **Key Techniques Used**:
- Pandas for data manipulation
- Matplotlib & Seaborn for customized plotting
- Feature engineering (e.g., ride duration, hour of day, day of week)
- Outlier detection & visualization
- Insight storytelling via PowerPoint with Canva-themed visuals

## 📁 Dataset Description

**File:** `taxis.csv`  
**Rows:** 6,433  
**Columns:** 14  
**Source:** Provided for learning purposes (March 2019 rides only)

### 📌 Features Included:
| Column           | Description                              |
|------------------|------------------------------------------|
| pickup           | Pickup timestamp                         |
| dropoff          | Drop-off timestamp                       |
| passengers       | Number of passengers                     |
| distance         | Distance of the ride (in miles)          |
| fare             | Fare amount (excluding tip/toll)         |
| tip              | Tip amount                               |
| tolls            | Toll charges                             |
| total            | Total ride amount                        |
| color            | Taxi color (e.g., yellow)                |
| payment          | Payment method (credit card, cash)       |
| pickup_zone      | Zone of pickup                           |
| dropoff_zone     | Zone of dropoff                          |
| pickup_borough   | Borough of pickup                        |
| dropoff_borough  | Borough of dropoff                       |

## 🔍 Analysis Summary

### ✅ Data Cleaning:
- Removed/handled null values in categorical columns
- Verified no duplicates
- Checked types and converted timestamps

### ✅ Univariate Analysis:
- Most trips had **1 passenger**
- Average fare: **\$13.09**  
- Tip distribution: mostly under \$5  
- Trip distances range from **0.5 to 36.7 miles**

### ✅ Bivariate/Multivariate Analysis:
- **Fare vs Distance**: strong linear correlation
- **Tips only given via Credit Card** — none in cash
- **Peak ride hour**: **18:00 (6 PM)**
- **Top ride day**: **Friday**
- **Most frequent pickup zone**: **Midtown Centre**

### ✅ Outlier Handling:
- High fares and long-distance rides were visualized and retained (not unrealistic)
- Ensured insights were not skewed by outliers

## 📈 Visualizations

All graphs were designed using a **custom pastel-orange Canva theme** for presentation purposes.

📊 Key plots:
- Fare vs Distance (scatter)
- Average Tip by Payment Method (bar)
- Average Tip by Hour (bar)
- Ride Frequency by Day of Week (bar)

## 📄 Presentation

A final PowerPoint presentation was designed in Canva based on the insights, graphs, and storytelling approach of this notebook.

🧾 Presentation Highlights:
- Clear flow from question to insight
- Theme-consistent visuals
- Executive summary slide with key takeaways

## 💼 Skills Demonstrated

- Data Cleaning & Wrangling
- Exploratory Data Analysis (EDA)
- Insight communication
- Matplotlib/Seaborn customization
- Presentation skills for stakeholders

## 🧑‍💻 Author

**Muhammad Huzaifa Mohsin**  
📫 huzaifamohsinkhan1@gmail.com  



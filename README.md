# 🎮 Video Game Sales Analysis Project

## 📌 Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of global video game sales data. Using **Python**, I analyzed a dataset of over 5,900 records to identify market trends, consumer preferences, and the most successful publishers and platforms in the gaming industry.

The goal of this analysis is to provide actionable insights into:
- Which genres generate the most revenue?
- Who are the dominant publishers in the market?
- How have sales trends evolved over time?
- Which regions contribute most to global sales?

## 🛠️ Tools & Technologies Used
- **Language:** Python 3.x
- **Libraries:**
  - **Pandas:** For data manipulation, cleaning, and aggregation (`groupby`, `pivot_table`).
  - **NumPy:** For numerical operations.
  - **Matplotlib:** For data visualization (Line charts, Bar charts, Pie charts).

## 📂 Dataset Description
The dataset contains historical sales data with the following key attributes:
- **Rank:** Global ranking of the game.
- **Name:** Title of the game.
- **Platform:** Console (e.g., Wii, PS2, X360).
- **Year:** Year of release.
- **Genre:** Category (e.g., Action, Sports).
- **Publisher:** Company that published the game.
- **Sales Columns:** NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales (in millions).

## 📊 Key Insights & Findings

### 1. Market Leaders 🏆
- **Top Game:** *Wii Sports* is the highest-selling game in the dataset with **82.74M** global copies sold.
- **Dominant Publisher:** **Nintendo** leads the market with a **32.4%** share of total sales, followed by Electronic Arts (17.6%) and Activision (11.1%).

### 2. Genre & Platform Trends 🕹️
- **Best-Selling Genre:** **Action** games generate the highest revenue globally, followed closely by **Sports** titles.
- **Top Platforms:** The **PS2** and **Wii** are the most commercially successful platforms in this dataset.

### 3. Regional Analysis 🌍
- **North America (NA)** is the largest market for video game sales, significantly outpacing Europe and Japan.
- Regional preferences vary, with Role-Playing games performing exceptionally well in Japan compared to other regions.

### 4. Sales Volatility 📉
- A **Year-over-Year (YoY) growth analysis** revealed significant volatility in the industry.
- Sales peaked around **2008-2009**, followed by a decline (likely due to the shift towards digital sales which might not be fully captured in older datasets).

### 5. Performance Segmentation 🏷️
- Using a custom Lambda function, I segmented games into "High" vs. "Low" performance based on median sales.
- **2,953 games** were classified as "High Performers," performing above the global median.

## 📷 Visualizations
*(Note: You can upload screenshots of your charts to a folder named 'images' and link them here)*

- **Year-wise Global Sales Trend:** Visualizing the industry boom and subsequent stabilization.
- **Publisher Market Share:** A pie chart highlighting Nintendo's dominance.
- **Top 5 Genres:** Bar chart comparison of global revenue by genre.

 ## 👤 Author

**Nadir**

- GitHub: https://github.com/NADIR789259
- LinkedIn: www.linkedin.com/in/nadir-khan-086864299


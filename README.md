
# 🏏 ICC Cricket Stats Dashboard

## 📊 Overview

This Power BI Dashboard presents an interactive and comprehensive analysis of ICC Cricket data, focused on **Indian players' performance**. The dashboard uses curated datasets (sourced from Kaggle) to explore and visualize batting statistics, player rankings, and comparative insights.

## 📌 Features

- **Player Statistics**  
  View detailed career stats for individual players including:
  - Batting Average  
  - Strike Rate  
  - 100s & 50s  
  - Total Innings  
  - Career Runs  
  - Ducks & Not Outs  
  - Impact Score (custom metric based on performance)

- **Top 5 Run Scorers**  
  Visualizes the most prolific Indian run-scorers in Test cricket with a bar graph.

- **Player Comparison Table**  
  Compares players based on:
  - Highest Score  
  - Milestone Achievements (100s, 50s)  
  - Consistency metrics (Not Outs, Ducks)  
  - Strike Rate  

- **Interactive Filters**  
  Slice data using buttons and filters like jersey number, country, or performance brackets (on other pages).

## 📁 Dataset

Source: [Kaggle - ICC Cricket Dataset](https://www.kaggle.com/datasets/mahendran1/icc-cricket)  
File used: `Bowling Test.csv` and `Batting Test.csv`  
Data was cleaned and transformed using Power Query within Power BI.

## 🧰 Tools & Tech

- Power BI (Data Modeling, DAX, Visualization)
- Power Query (Data Cleaning)
- Custom Measures (DAX-based Impact Score)
- Microsoft Excel (initial inspection)
- Kaggle Dataset

## 📌 Pages in the Dashboard

1. **Landing Page** – Stylish homepage with navigation
2. **Test Player Stats** – (Screenshot above) detailed breakdown of Indian batsmen
3. **Bowling Stats** – (Not shown) insights into wicket takers
4. **Filters & Dynamic View** – Explore by span, country, performance
5. **Visual Highlights** – Charts for century count, strike rate trend, consistency index

## 📈 Impact Score Calculation

> A custom DAX measure that considers runs, strike rate, 100s/50s, and number of innings to compute a score out of 100 for each player. Scaled to match comparative performance.

## 🙋‍♂️ Author

- **Name:** Girish  
<!-- - **Registration Number:** [Your Registration Number]   -->
<!-- - **Company:** Cozentus (Internship Project)   -->
<!-- - **Mentor:** [Mentor’s Name] -->

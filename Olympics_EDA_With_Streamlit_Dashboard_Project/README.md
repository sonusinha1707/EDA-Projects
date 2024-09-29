# Olympic Data Analysis using Python

<img src="https://github.com/sonusinha1707/EDA-Projects/blob/main/Olympics_EDA_With_Streamlit_Dashboard_Project/logo.png" height="400" width="800" >

## Overview
This project performs exploratory data analysis (EDA) on the Olympic athletes dataset. The goal is to uncover trends and insights related to the participation, performance, and distribution of athletes over the years. The analysis includes demographic information such as age, height, weight, as well as comparisons between different sports and events.

## Objectives

- Analyze the demographics of athletes participating in Olympic games.
- Explore relationships between height, weight, and age for different sports.
- Identify trends in athlete participation across different years and seasons (Summer vs. Winter).
- Analyze the distribution of medals among countries and identify top-performing countries.
- Examine differences in athlete participation and performance by gender.

## Dataset

The data used for this project is sourced from Kaggle:

- **Dataset Link:** [120 Years of Olympic History](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results/data)

## Data Preprocessing

The dataset is cleaned to handle missing values and data types:

- Missing values in `Age`, `Height`, and `Weight` are filled with their respective mean values.
- Data types are adjusted for better analysis.

## Analysis Summary

### 1. Distribution of Athlete Height and Weight

- A scatter plot is used to show the distribution of height and weight for athletes, with the size representing age and the color representing different sports.

### 2. Seasonal Differences

- A scatter plot with trend lines compares the relationship between height and weight for male and female athletes across Summer and Winter Olympic games.

### 3. Age Variation over the Years

- Box plots show how the age of athletes has varied over different Olympic years, broken down by gender.

### 4. Country-Level Analysis

- The number of participating teams and countries is analyzed across different Olympic editions, and the top-performing countries are identified by medal count.

### 5. Medal Analysis for the USA

- A detailed analysis of medals won by the USA, including the number of gold, silver, and bronze medals, is presented using pie charts and bar charts.

### 6. Gender-Based Participation

- Histograms and scatter plots are used to illustrate the differences in participation between male and female athletes across various sports and seasons.

### 7. Women in the Olympics

- Participation trends for female athletes in the Summer Olympics are analyzed over time, showing how gender representation has evolved.

## Findings and Conclusion

- **Demographic Trends:** The dataset reveals distinct trends in the height, weight, and age of athletes in different sports.
- **Seasonal Insights:** Significant differences are found between the participation and performance of athletes in Summer and Winter games.
- **Medal Distribution:** Analysis of medals won by different countries highlights consistent top performers like the USA.
- **Gender Representation:** The participation of female athletes has increased significantly over the years, showcasing progress in gender representation at the Olympic games.

This analysis provides a comprehensive understanding of the dynamics of the Olympic games, enabling deeper insights into athlete characteristics and performance trends.

# Game Sales Research

This project analyzes a dataset of video game sales from an online store. The main goal is to identify patterns that determine the success of a game, based on sales data, critic and user ratings, platform, genre, and region.

## Dataset

The dataset includes the following columns:
- Name: Game title
- Platform: Platform (e.g., PS4, Xbox One, PC)
- Year_of_Release: Release year
- Genre: Game genre
- NA_sales: Sales in North America (millions)
- EU_sales: Sales in Europe (millions)
- JP_sales: Sales in Japan (millions)
- Other_sales: Sales in other regions (millions)
- Critic_Score: Critic score (max 100)
- User_Score: User score (max 10)
- Rating: ESRB rating

## Main Steps

1. Data preprocessing: handling missing values, converting data types, removing duplicates, and adding a total sales column.
2. Exploratory data analysis: analyzing sales trends by year, platform, and genre; investigating the influence of critic and user ratings on sales; and examining regional preferences.
3. Statistical hypothesis testing: comparing user ratings across platforms and genres.
4. Drawing conclusions and identifying factors for a successful game.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- missingno
- scipy

## Project Goal

To process and analyze video game sales data, identify key factors for game success, and provide recommendations for future releases.

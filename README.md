# Cricket-World-Cup-2023-Analysis

Project Overview

This project is based on the ICC Men’s Cricket World Cup 2023.
The main goal of this project is to analyze player performances, bowling performances, stadium conditions, and team results using Python.
In this project, I used different datasets related to batting, bowling, match schedules, and player information to extract meaningful insights from the tournament.
The complete analysis was performed in Google Colab using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.

Tools & Technologies Used -
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab


Datasets Used -
  The project uses four CSV datasets:
    1. batting_summary.csv
    2. bowling_summary.csv
    3. match_schedule_results.csv
    4. world_cup_players_info.csv


Data Cleaning & Preparation ----> 

Before starting the analysis, the datasets were cleaned properly.

  Steps Performed:
    1. Checked missing values using .isnull().sum()
    2. Filled missing values in the Dismissal column with "Not Out"
    3. Removed unnecessary columns like:
    4. image_of_player
    5. description
    6. Filled missing bowling styles with "No Bowling"
    7. Removed duplicate rows
    8. Converted the Date column into proper datetime format


Exploratory Data Analysis (EDA) ---> 

1. Top Scorer Analysis -
  I identified the highest run scorer in every match using groupby and idxmax functions.
  Key Insights:
    Rohit Sharma became top scorer in 3 matches, Daryl Mitchell became top scorer in 3 matches, Quinton de Kock became top scorer in 3 matches
  Bar charts were used to visualize the players with the most top-scorer performances.

2. Best Bowler Analysis - 
  I analyzed the bowler with the highest wickets in each match.
  Key Insights:
    Bas de Leede performed as best bowler in 3 matches, Jasprit Bumrah achieved this 3 times, Mohammed Shami also dominated in multiple matches
  A bar chart was created to compare the best bowling performances.

3. Stadium Analysis - 
  The project also analyzed which stadiums favored:
    Batting first
    Bowling first
  Key Insights:
  Several stadiums showed better results while chasing - Ahmedabad, Bengaluru, Chennai, Mumbai, and Kolkata showed strong bowling-first win trends
  Bar charts were used for better comparison and visualization

4. Team Performance Analysis - 
  I analyzed the overall winning performances of teams in the tournament.
  This helped identify:
    Which teams dominated the World Cup
    Which teams consistently performed better throughout the tournament


Conclusion -->

This project helped in understanding the overall performance trends of the ICC Men’s Cricket World Cup 2023.
The analysis highlighted:
  Top batting performers
  Best bowling performances
  Stadium behavior
  Team winning patterns

Overall, this project demonstrates how Python can be used to perform real-world sports data analysis and generate meaningful insights from raw datasets.
   

# NBA Data Project

## Project Summary:
This project focuses on analyzing basketball team performance using Python. 
It involves creating a DataFrame to aggregate player-level statistics into team-level statistics, visualizing team performance in various aspects, and merging the team DataFrame with player and college information.

## Tasks Completed:

Task 1: Create a Team DataFrame:

1. Aggregated player-level data to create a DataFrame containing team-level statistics.
2. Calculated the sum of numerical columns (excluding 'Games Played') for each team.
3. Removed the 'Games Played' column from the team DataFrame.
4. Added a new column 'Games Played' with a value of 50 for all teams.

## Task 2: Visualise Team Performance:

2. Calculated 'Pts per Game' (Points per Game) for each team and added it as a new column to the team DataFrame.
2. Created three graphs to visualize team performance in different aspects:
3. Graph 1: Displayed teams with the most three-pointers ('3P').
4. Graph 2: Displayed teams with the most assists ('AST').
5. Graph 3: Displayed teams with the most steals ('STL').
Utilized appropriate visualization techniques for effective representation of the data.

## Task 3: Merge Team DataFrame with Player DataFrame:

1. Removed the 'Team' column from the original player DataFrame.
2. Used the merge function to match each player with their respective team based on the 'Team' column.
3, Used the merge function to match each player with their respective college based on the 'College' column.
Conclusion:

This project successfully automated the analysis of basketball team performance using Python.
By aggregating player-level data, visualizing team performance, and merging relevant information, it provides valuable insights into team dynamics and player attributes. 
The automation of these tasks enhances efficiency and facilitates better decision-making in basketball management and coaching.

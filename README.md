# Project-Python
Overview of the Project:

The dataset contains the details of basketball players across various teams , consisting of 458 rows and 9 columns.Key variables such as age, height, weight, salary, and player position are analyzed to identify insights.
The analysis of this Basketball players dataset revealed several key trends , patterns and correlations that provide valuable insights into the Player demoghraphics, Positional Trends and salary structure.

As a initial part of Analysis,Import necessary libraries like Pandas , Numpy ,Matplotlib and Seaborn to the code frame.
Before analysing the data, Preprocessing of the data were done by loading the dataset into a pandas DataFrame,
Correcting the height column by replacing it with random numbers between 150 and 180 using numpy.random.randint() function and also by Ensuring data consistency and integrity by checking for missing values, duplicates and data types. 
Through this preprocessing method, No duplicates were found and also dropped the rows with missing values.

After Data Preprocessing, Various analysis tasks were done like ; 
- Distribution of Players across teams : Used value_counts() functions to calculate the distribution of players across each team and also calculate the percentage split relative to the total number of players by normalising.
- Segregation of players by position : Used groupby() function to segregate players based on their positions .
- Predominant age group : Used the value_counts() function to calculate the players by age group and Identify Predominant Age group .
- Identify team and position with highest salary expenditure :Used groupby() function to calculate the total salary expenditure for each team and position ,Identify team and position with highest salary expenditure. 
- correlation between age and salary: Use corr() function to calculate the correlation between age and salary. created a scatterplot to represent it visually.

After completing the analysis tasks, graphical representation of the data were done.
Created visualizations for each of the analysis tasks using Seaborn visualization library.

- Distribution of Players across teams -  Created a bar chart for visualising distribution using countplot in seaborn.
    ![Screenshot (586)](https://github.com/user-attachments/assets/91f992b7-147a-4f0e-9754-b2a0fb6dda54)
- Segregation of players by position  - Visualise the segregation using countplot in seaborn.
     ![Screenshot (587)](https://github.com/user-attachments/assets/c0fab707-dcba-41fa-bbf4-b93e99f0f29f)

- Predominant age group - Created histplot to visualize the age distribution.
     ![Screenshot (588)](https://github.com/user-attachments/assets/73558d1f-c6f8-4212-8a30-435084490775)

-  Identify team and position with highest salary expenditure - Created a barplot for visualization by seaborn.
     ![Screenshot (589)](https://github.com/user-attachments/assets/d315f5d3-c607-4b95-b861-1861dc34c343)

-  Correlation between age and salary - Created a regplot to visualize the correlation.

 Trends ,patterns and correlations gained from this analysis : The player's are between the ages of 19 to 40. Younger players (aged 20-24) typically include many with less experience, while older players above 30 are often veterans with extensive careers.There's a significant disparity in salaries among the players. 25% of players earn below $1 million, while the top earners exceed $20 million.Point Guards (PG) and Shooting Guards (SG) often have higher salaries compared to other positions like Small Forward (SF) and Power Forward (PF).Teams vary significantly in their overall salary structure.
There is a strong correlation between experience and salary, where, more experienced players generally command higher salaries.Older players tend to have slightly higher salaries, though the correlation is weak.Players aged 30 or older are likely in the higher salary bracket, reflecting experience. Heavier players show a minor positive correlation with higher salaries.

These findings provide a clearer understanding of player characteristics and salary structures in professional basketball . The dataset reveals a wealth of insights into player demographics, salary trends, and positional importance within the NBA.Teams may benefit from analyzing these trends in more granular detail, enabling them to make informed decisions regarding recruitment, player development, and strategic financial planning.




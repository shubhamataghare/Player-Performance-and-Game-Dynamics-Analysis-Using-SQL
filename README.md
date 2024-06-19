# Player Performance and Game Dynamics Analysis Using SQL

Project Description:

This project focused on extracting key performance metrics for players, comparing player performance across different devices and difficulty levels, and identifying trends and patterns in player behavior. Using SQL, I gathered valuable insights to optimize the game experience.

Project Goals:

Analyze Player Performance: Extract key performance metrics for players.

Device and Difficulty Analysis: Compare player performance across devices and difficulty levels.

Game Level Insights: Calculate average performance metrics for different game levels.

Identify Trends and Patterns: Track cumulative player performance over time.

Player Behavior Analysis: Examine player engagement and behavior patterns.

Optimize Game Experience: Suggest improvements based on performance insights.

Dataset Description:

Player Details Table:

• P_ID: Player ID

• PName: Player Name

• L1_status: Level 1 Status

• L2_status: Level 2 Status

• L1_code: Systemgenerated Level 1 Code

• L2_code: Systemgenerated Level 2 Code

Level Details Table:

• P_ID: Player ID

• Dev_ID: Device ID

• start_time (Timestamp): Start Time

•stages_crossed: Stages Crossed

• level: Game Level

• difficulty: Difficulty Level

• kill_count: Kill Count

• headshots_count: Headshots Count

• score: Player Score

• lives_earned: Extra Lives Earned


**Key Questions Addressed:**

1)Extracted player details and difficulty level for all players at Level 0.

2)Analyzed the total number of stages crossed at each difficulty level for Level 2.

3)Identified unique dates for players who played on multiple days.

4)Calculated level-wise sum of kill counts greater than the average for Medium difficulty.

5)Summed lives earned by level, excluding Level 0.

6)Ranked top 3 scores for each device ID in increasing order.

7)Determined the first login datetime for each device ID.

8)Find the device id that is first logged in (based on Timestamp) for each player. Output should contain player id, device id, and first login datetime.

9)Extract the top 3 highest sums of scores for each device_id and the corresponding player.

10)Find the cumulative sum of stages crossed over Timestamp for each player, excluding the most recent Timestamp.


**Key Insights and Recommendations:**

Identified top-performing players and their performance metrics.

Analyzed player performance across different devices and difficulty levels.

Discovered trends and patterns in player engagement and behavior.

Suggested game experience improvements based on data-driven insights.


Next Steps:

Continue exploring additional metrics and dimensions.

Implement recommended changes to optimize the game experience.

Share findings with the game development team for further action.

Technical Skills:

• SQL

• Data Analysis

• BigQuery

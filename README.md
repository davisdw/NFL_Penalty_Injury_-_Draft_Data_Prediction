# Super_Grp_1_Proj_3
Super TEAM!

# Group 1 - Visualization 

DATA:

- Utilizing the NFL Data from Project 1: NFL Teams data, NFL stadiums/weather data and NFL betting data showing over/under line and game spread. 

- NFL Penalties data: detailing penalties for each game showing the quarter, player and time during the game from 2009 to 2022.

- NFL Draft data: python library including draft picks and rounds for each NFL team from 2005-2022.

- NFL Injury data: python library containing injury data including season, player, position and status before the game from 2009 to 2022.


Questions:

- Implement the draft picks data set to determine if specific draft picks or the number of draft picks has an impact on the overall teams record and their probability to make playoffs or even win the super bowl.

- Using the injury data set, we want to determine how a team’s overall record could be impacted by injuries to key players on their team. Which injuries had the highest impact on a team’s outcome? 

- Using the draft picks data set and seasonal nfl data set showing player career stats, we have an exploratory interactive chart to examine the differences between players efficiency based on position and their corresponding draft rounds.

***
### Does Turf has impact on injury based on play type and player positions?
![Screenshot 2024-01-22 194914](https://github.com/davisdw/Super_Grp_1_Proj_3/assets/140672220/c75801cc-5064-44f4-bad0-8fe8ab4338a1)

![Screenshot 2024-01-22 195116](https://github.com/davisdw/Super_Grp_1_Proj_3/assets/140672220/6a3c84fa-0ebf-49c6-9d4a-404e00c7ce23)

Question: What is likely the risk of a player’s injury based on turf type?
![image](https://github.com/davisdw/Super_Grp_1_Proj_3/assets/140672220/f5dd03e5-d42a-47fd-98b4-1a063c58fb80)

Answer: both curves indicated with both significant risk of injuries 

***
## NFL Penalty Data

Looking at penalties that were not offset, or declined in the remaining 2 minutes of the game, and over 15 total penalty yards.

Did these high penalty yards affect the outcome of the game?
![image](https://github.com/davisdw/Super_Grp_1_Proj_3/assets/140672220/2227fed8-2cbb-4011-8faf-e701b3c36460)

The Denver Broncos had the highest overall total penalty yards for games lost. The New York Jets had the highest overall total penalty yards for games won.

![image](https://github.com/davisdw/Super_Grp_1_Proj_3/assets/140672220/4e6df995-14a4-41d4-908b-b6f6f05728a7)

The New York Jets had the highest penalty yards in 1 game @ 50 yards (13 yd DPI, 24 yd DPI, 13 yd DPI) week 5 of the 2019 season against the Dallas Cowboys. Despite these penalties, the Jets won the game 24-22. The Jets were up 24-16 prior to the 2-minute warning.

![Screenshot 2024-01-21 144403](https://github.com/davisdw/Super_Grp_1_Proj_3/assets/140672220/60793ba7-5d7e-41be-a109-e95d80a7e6b9)

***

## NFL Draft Data Interactive Chart

Features:

- Sort by Minimum Number of games played
- Sort by Season year or range of seasons
- Sort by number of pro bowls received
- Sort by Position
- Filter Y-axis by passing, rushing, receiving efficiencies or PPR fantasy points

 Details:

- 4173 total data points 
- 960 total Unique Players
- Looking only at Qb’s, RB’s, WR’s and TE’s
- Seasons 2009 to 2023
Regular Season Stats

![image](https://github.com/davisdw/Super_Grp_1_Proj_3/assets/140672220/e49aabd2-33c7-4f00-a894-c211ca64a678)

### Results from Exploratory Analysis
- Early round draft picks tend to have more games played than later round picks
- Early round draft picks tend to be more inconsistent when it comes to efficiency numbers but generally show a higher average efficiency than later round picks
- QB’s taken in the first round show a significantly higher range of efficiency and 5th round QB’s appear to be very inefficient when it comes to contributing to their team
- Looking at RB’s and WR’s.. the round they were selected in did not appear to significantly impact their efficiency suggesting it would be smart to draft a RB or WR any round and they could show potential.
The best time to draft a TE appears to be the second or third round.

 ***
 
### Sources:
https://scikit-learn.org/stable/

https://docs.profiling.ydata.ai/latest/

https://www.kaggle.com/code/bryanb/survival-analysis-with-cox-model-implementation

https://bokeh.org/

https://seaborn.pydata.org/

https://pypi.org/project/nfl-data-py/

https://www.kaggle.com/datasets/tobycrabtree/nfl-scores-and-betting-data/

https://www.kaggle.com/datasets/mattop/nfl-penalties-data-2009-2022-season

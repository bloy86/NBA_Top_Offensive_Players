# Top NBA Offensive Players

#### -- Project Status: Completed

## Project Objective
The purpose of this project was to use a variety of basketball statistics to determine what National Basketball Association (NBA) player had the most dominant offensive season.  Our team decided to undertake this project because we missed sports debates during the COVID-19 pandemic, and wanted to use available data to better answer an age-old debate. 

### Methods Used
* Data Visualization
* Statistical Analysis

### Technologies
* Python
* Pandas, Jupyter 

## Project Description
We obtained NBA player data from the website Kaggle (https://www.kaggle.com/drgilermo/nba-players-stats) and verified it's accuracy by randomly checking the statistics of several players in the Kaggle dataset against statistics posted by teams on their official websites.  This orignal dataset was 24,690 rows, including seasons from 1950-2017.  We decided to only include data from 1980-2017, as offensive play changed dramatically after 1980 with the introduction of the 3-point shot.  Many of the statistics we were interested in exploring were averages (e.g., points per game) so we decided to only include players that had played at least 10 games in a season and averaged 10 minutes per game.  This meant that players were excluded who had high averages in some statistics, but had played very little in a given season. 

The following statistics were considered in evaluating offensive season dominance:
* Points per game
* Effective field goal percentage
* 3-Point field goals made per game
* Assists per game
* Offensive rebounds per game

In order to determine the offensive dominance of players, I took the individual statistics for each player and subtracted them from the median of that statistic across the NBA, and divided by the median. For example, the median points per game in the NBA for included players was about 8.  If player A averaged 16 points per game, the calculation was (16-8)/8 = 2.  Thus, player A had a point total that was two-times greater than the rest of the NBA.  Since all statistics are now weighted against the median, we could then add a player's "weights" of the 5 statistics listed above to determine how much more, or less, dominant that player was in that season, compared to the rest of the NBA. 

## Conclusion
By considering individual player statistics against the median performance in the NBA over 37 seasons, Stephen Curry's 2015-2016 season was the most dominant offensive season. Across the 5 statistics we chose to consider, Curry performed over 40 times greater than the median performance.  Coincidentally, Stephen Curry won the NBA MVP award that year by unanimous vote, the only time this has happened in NBA history. Curry's team, the Golden State Warriors, also set the NBA record for regular season wins. Their season may have been considered the best season in NBA history. But the Cleveland Cavaliers won the NBA title in miraculous fashion to bring the first (and only) NBA championship to Ohio.


## Team Members

|Name     |  GibHub Handle   | 
|---------|-----------------|
|Blaine Gobler | goblebla   |
|Bryan Loy | bloy86   |
|Peter Nguyen | nguyenpe17  |
|Walter Stern | wstern1   |
|Scott Theener | pdx-1491  |

## Contact
* Bryan Loy, linkedin.com/in/bryanloy


# MLBstatTRAX
A tool to easily monitor and visualize the statistical performance of MLB players in real time.  Useful for fantasy baseball research or armchair GMs.

## Two features of MLBstatTrax:

### 1. Compile and update mlb batter gamelog data
#### Goes back to the start of the 2015 season if ran today (in general, will look back five seasons)
#### When you run MLBstatTrax for the first time, batter data will be compiled (using the pybaseball module) then saved on your local machine as a .csv file
#### The next time you run MLBstatTrax, data will be brought current
#### The .csv data file generated by MLBstatTrax is at your disposal for any purpose you wish, for example, aggregating statistics for an entire season

### 2. Player stat graphs
#### Graphs can be easily customized to focus on the stats you care about for any or all seasons
#### Graphs will update themselves automatically using the latest data

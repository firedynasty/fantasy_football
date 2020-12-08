# fantasy_football

## Data Exploration

Are running backs from last year doing as well as this year? Who are the new gems that are into the scene?  

Goal # 1 With the datafile: `combinedrushing2019.csv` will create a Jupyter notebook to remove the duplicates and then sort it to see and compare. 


`turnover_with_wins.xlsx` has wins and turnover differentials.

The websites to get the data:
1. [Turnover Differentials](https://www.footballdb.com/stats/turnovers.html?yr=2020&conf=&sort=differential)
2. [NFL](https://www.nfl.com/standings/division/2019/reg/)


In `turnover_with_wins.xlsx` not sure how to run a linear regression to compare turnovers with wins because turnovers get to a negative number.
Thinking that you can do some sort of proportion from the smallest turnover to the largest turnover.

By setting the number of turnovers into a normalization function "Normalizing Numerical Values in Excel" to get a proportion between the range of 0 and 100 then it is easier to plot the regression line.  For 2020 and 2019 Seasons the regression r^2 is 1.  



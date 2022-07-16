# English-Premier-League-2020-21-Data-Analysis-with-Python
My attempt at analyzing a dataset of football players from the EPL 2020/21 season, including analysis and visualizations of top ten goalscorers, average age per club, most yellow carded players, penalties scored vs not scored, and much more!

The analysis includes the following (in order):
  1). Loading the relevant data and eyeballing it first by looking at first 10 rows
  2). Using .info() and .describe() to get some statistical insights into the data, like number of observations and data types and whether a field is not null
  3). Speaking of which, ensured that there were no null values in the dataset
  4). Added two new columns - Mins Per Match and Goals Per Match for each player in the dataset - which are self-explanatory
  5). First Analysis - % of penalty goals scored vs % of penalty goals not scored, visualized on pie chart
  6). Most commonly represented nationalites in the Premier League 20/21 season, visualized on bar chart
  7). Most and least represented clubs by number of players, visualized on bar charts
  8). Distribution of age groups - <20, 20-25, 25-30, and >30 - visualized on pie chart as percentages
  9). Clubs with most u20 players
  10). Boxplot of average age in all clubs
  11). Plot of clubs vs total goals across the season
  12). Plot of clubs vs total assists across the season
  13). Top 10 goal scorers and assisters across the season
  14). Top 10 goals per match (num of goals divided by num of matches) across the season
  15). seaborn barplot visualization of top 15 most yellow-carded players

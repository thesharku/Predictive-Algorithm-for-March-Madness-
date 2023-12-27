# Predictive-Algorithm-for-March-Madness-
Algorthim that predicts the winners and losers of the Men's NCAA Basketball Tournament : March Madness

This Algorthim was made in 2021 using Python with NumPy and Pandas.
It works by assigning point values to varying basketball metrics, such as 3-Point Percentage, Free Throw Percentage, Points scored, etc, etc.
These statistics were assigned specfic point values according to how valuble or important these metrics were.
The importance was found through numerous SQL queries using 20+ years of data to find the most important basketball statistics in prediciting a winning team.
These metrics were then ranked and assigned point values based on their importance.

For each matchup in the tournament, a team was chosen to be either the negative team or the positive team. 
For each important statistic, the team with the better number, whether it was percetange or not, was given the point value assigned for that statistic.
If the team was negative, the point value would be negative, and vice versa.
After every metric was weighed, the sum of the points for both teams would either be negative or positive.
If it was positive, the positive team would move on(WIN), and vice versa.
In case of a tie, the team with the higher average points scored would win.

This was repeated until there were 4 teams left, otherwise known as the final four.
The accuracy was based off the final four correctness even though the algorthim did go on to predict the winner of the tournament.


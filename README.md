# GABBERT
Machine Learning Meets the NFL

<b>G</b>eneral <br>
<b>A</b>lgorithms for <br>
<b>B</b>ettering <br>
<b>B</b>asic <br>
<b>E</b>valuation and <br>
<b>R</b>esigning <br>
<b>T</b>actics

NFL players are never more expensive than when they hit the open market of free agency. GABBERT is a tool designed to give coaches, general managers, and agents the information necessary to more accurately predict player development in the final year of their rookie contract. Using statistics, advanced analytics, and athletic measures, GABBERT uses the first three years of a player's career in order to predict future success. GABBERT also creates a player comparison system for reference. GABBERT'S predictions are position-based. Specific information on how individual positions are evaluated can be found via the links below.




## Data

GABBERT will utilize the following data sources for the years 1999-2015:
* NFL Box Score data
* Athletic measures from NFL Draft Combine results for years 1999-2015.
* Advanced analytics, both positionally (where available), and team-based performance measures.
* Athletic measures from NFL Draft Combine results for year
* Advanced analytics, both positionally (where available), and team-based.


## Positional Analyses:

Wide Receievers:

Given the large amount of data available for wide receivers, and the relatively large sample size available compared to other positions, we decided to begin our project with wide receivers. The first step in that process required us to create a comprehensive metric for evaluating wide receivers. This metric was useful both for exploratory data analysis and as a target variable for our modeling. A thorough explanation of this metric can be found below.

[CATCHERR Explained](https://github.com/cl65610/GABBERT/blob/master/wide_receivers/catcherr.md)

CATCHERR allowed us to build a predictive model for wide receivers entering the fourth year of their careers. An explanation of our process and results can be found [here](https://github.com/cl65610/GABBERT/blob/master/wide_receivers/wr_results.md).


## Next Steps
* Further positional analyses/models.
* Applying GABBERT to college athletics.
* Investigating Fantasy Football applications.

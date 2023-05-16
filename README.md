
# Major League Baseball Player Data from 2000

I undertook this independent study to get a better grasp on many of the differrent programs data scientists use in their daily lives. I, as someone who plans to work in baseball for the rest of my life, thought it would be interesting to analyze data from Major League Baseball. Specifically, I wanted to look at how switching teams affects players, and which teams are the best at getting the most from players that were received from other teams.

Trading and free agent signings are an integral part of the game. Trades are a mutually beneficial transaction that can help a contending organization get a must needed asset in their playoff push(es), and can help a rebuilding team obtain prospects that will allow them to build toward a better future. As for free agency, this practice allows teams to upgrade, but gives players the freedom to sign the contracts that they have earned in their initial six years with their organization. It is interesting to me how these players perform after switching teams, specifically using the WAR variable. WAR, or Wins Above Replacement, measures the estimated number of Wins a player is worth compared to a replacement level player - who is worth zero wins. 

Using Tableau, I created interactive graphs that can allow the viewer to see any player they would like from the year 2000, see how they have done on each of their teams, and easily visualize their performance. 

Here is a link where you can explore the data in an [interactive dashboard](https://public.tableau.com/app/profile/benjamin.stoopack/viz/BenStoopackData/WARFilterWithSwitch?publish=yes). If not all sheets are showing up, then please click the gear icon in the top right corner, and in the drop down menu turn "Show Sheets" on. 

### Data Dictionary

|variable |class     |description |
|:--------|:---------|:-----------|
|PlayerName|character|Name of Player|
|Age      |Number    |Player's Age  |
|Year ID  |Date      |Season of Stats   |
|team ID  |character |Team Abbreviation        |
|FIP Minus|Number    |Fielding Independent Pitching 100= Average, <100 is above average        |
|FB Plus  |Number    |Fly Balls Given up Compared to league average       |
|GB Plus  |Number    |Ground Balls Given up Compared to league average       |
|LD Plus  |Number    |Line Drives Given up Compared to league average       |   
|WAR      |Number    |Wins Above Replacement         |
|Salary   |Number    |Dollars earned during the season    |



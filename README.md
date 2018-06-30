# HotHand

The HotHand package is a collection of datasets covering the last 3 seasons of NBA basketball; regular season and playoffs (2015-16, 2016-17, 2017-18). The intention of the package is to provide a freely available source of NBA data to R users that is in a simple form for quick manipulation, calculation and visualisation. This package is of particular value as it provides historical betting odds (Pinnacle Sports) which can sometimes be hard to obtain by the general public. 

In the spirit of open source and collaboration, the authors encourage users to share reproducible insights to our twitter handle @HotHandNBA  The authors will be tweeting over the offseason so please request analyses and visualisations you are interested in. 

Dataframes:

Game - Row for each match, describing date, teams, scores and odds (RowID is the unique identifier for a match and follows a chronological order)
Team - Row for each team per match, containing traditional and advanced box score information 
Player - Row for each player per match, containing traditional and advanced box score information (NB: opposition stats and defensive stats such as OPP_PTS_OFF_TOV have not attributed to the player, rather these are total opposition stats for while that player was on the court) 

For help with understanding column definitions, refer to https://stats.nba.com/help/glossary/ or reach out to us on twitter.  All calculated metrics such as Net Rating, PIE, PACE have simply been copied from boxscores at stats.nba.com and are not derived independently by the authors. All stats relate to the full game including overtime.

Certain columns of the dataframes allow users to link to external references:

URL for match details: https://stats.nba.com/game/00[GAME_ID]/

URL for player profiles: https://stats.nba.com/player/[PLAYER_ID]/

URL for odds comparisons: https://www.sportsbookreview.com/betting-odds/?date=[YYYYMMDD]

Future updates and releases:

The most recent version of the package is v0.1.0 as at 30/06/2018.

The authors do not plan to update the datasets throughout the 2018-19 season as this project is a labour of love outside of their other full-time commitments. However, please feel free to contact us on twitter or email with requests for help or to engage us for analytical data work relating to NBA or sports betting. 

Disclaimers:

Every effort has been made to ensure the accuracy of data however these statistics are not official. 

Historical odds provided are intended to be indicative only. Odds are opening and closing from Pinnacle as collated by SportsBookReview.com website. The authors and maintainers of this package accept no responsibility for the accuracy of historical odds provided and will not be made liable for any betting activities of the user. 

The authors have no affiliation with any of sportsbookreview.com, Pinnacle Sportsbook or the National Basketball Association.


See also related sports data in R:

https://github.com/jimmyday12/fitzRoy/blob/master/README.md
@anoafl 

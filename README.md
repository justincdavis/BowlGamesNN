# BowlGames2021
This is an implementation of a feed forward neural network for use in predicting the bowl games for the 2021 college football season.
This uses the existing cfbd api (college football data api), for access to team and game statistics. 
The model predicts games during the regular season with 82% accuracy, however, the model knows the season statistics when predicting season games. 
This decision was made since the bowl game data pool is small and bowl games are always played at the end of the season. Thus, regular season games were used to train the neural network. 

This was originally designed to aid me (someone with very little football knowledge) beat my family in our annual game of confidence bowl game picks in the Capital One Bowl Mania. 
The ending performance of the neural network sat around a 75% accuracy. 

Future work will incorporate coaching data as well as combination and deletion of extranous feature data. 

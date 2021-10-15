Abstract:

The goal of this project is to advocate for an increase in the use of data to aid in the decision making of offensive play callers in the NFL. Currently, quantitative data is involved with risk assessment and pregame planning, but has a limited role in real-time use during games. Offensive play calling is one of the most complex tasks in professional sports, and many coaches are reluctant to validate their decisions using insights from play-by-play data and historical trends of their opponents. A simple exploratory data analysis of play-by-play data from the 2017-2018 season reveals many examples of inefficient decision making, a problem that can be remedied with a predictive play calling model. 

Design:

A predictive play calling model would pose some meaningful risks and includes many assumptions. The main assumption is that NFL offenses are concerned only with maximizing yards and points; however, teams will commonly make play calls with the sole objective of negatively influencing their opponents next possession. Another assumption is that the opponents defense will not have an equally sophisticated model, which would make this model less effective. 
Confirmation bias is a common phenomenon that may impact the adoption of this type of model; many coaches may be reluctant to consider this type of insight if it disagrees with their opinion of the optimal play in certain in-game situations. It is also quite possible that a model of this complexity may prove to be ineffective. 

Data:

Data for this project was obtained from Kaggle and produced by the Carnegie Mellon Sports Analytics Club. The dataset contains play-by-play data from 90,069 offensive plays during the 2017 and 2018 NFL regular season, and variables include the score differential, yards gained per play, time on the game clock, and play type among others.

Algorithms:

I performed an exploratory data analysis in Excel and Tableau, and displayed my findings in a Tableau dashboard. 

Feature engineering:
•	Red zone: created a feature to track whether the play was run from the red zone (final 20 yards of opponent’s half before the goal line). 
•	Pass and Run Direction: combined columns to create variables that detailed the play direction
•	Created variables to track the expected points added per play, the pass to run ratio, and the percentage of first and second downs where passing plays occurred for each game


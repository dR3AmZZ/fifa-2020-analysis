# fifa-2020-analysis
FIFA 20 is a football simulation video game published by Electronic Arts as part of the FIFA series. It is the 27th installment in the FIFA series, and was released on 27 September 2019 for Microsoft Windows. Throw this analysis we can understand how we select our FUT team for online play against rivals. For the project we are trying to provide a reference for player reference and salary evaluation. The results also can help the real word football club to decide like finding the best cost performance player.

From this project we will achieve three goals:1. How to improve value is a crucial question for both game players and real-life soccer players. What we do here is to figure out key factors to help players to increase the value most efficiently. 2. For the new players, in most cases they don’t know which is the best position for them. So, we are going to build the model to solve this question. 3. Sometimes players or managers want to pick the substitute for the team, but the question is there are thousands of players for them to pick. What we do here is to build a recommender system for helping them. 

To achieve those goals, we made three specific predictions. 1. We use some regression model to predict the value of a player including linear regression, random forest, Gradient Boosting Machine Regression. 2. We use classification models to predict the best fitting position of a player. 3. We use k-means clustering to create a recommender system for alternate players. 

For the inference, we use features like attacking_volleys’, skill_dribbling’, skill_move’, ‘international_reputation’ to predict value, position and alternative of a specific player
 
The model we build successfully defines the value of each player, can accurately find the position, and alternative of a specific player. 

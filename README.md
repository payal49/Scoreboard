# Scoreboard
Android App Scoreboard
Part 2: Android Development

The following task is to implement a small Android application (as specified). The requirements

A-E correspond to grades where A is best and E is worst.

Task

Implement a scoreboard (like

https://play.google.com/store/apps/details?id=com.chapas.cyclingsimulator&hl=en)

for sport matches.

Minimal requirement (E) is to support football matches and to provide the following functionality:

● Display the current score (e.g. 6 - 2)

● A button to reset the match score (e.g. set the score to 0-0)

● Two buttons to increase by 1 the score of one of each team.

Requirement for (D) is to support basketball matches, providing three buttons to increase the

score of the first team (+1, +2, +3) and three buttons for the second team.

Requirement for (C) is to support both basketball and football, allowing the user to select the

sport and to update the interface accordingly.

Requirement for (B) is to support basketball, football and tennis. For tennis, you should provide

one button for each player. Player score for a tennis match is a triple (points, games, sets).

Initially the score is (0,0,0)

1. If a player scores and its points are 0, then his points become 15

2. If a player scores and its points are 15, then his points become 30

3. If a player scores and its points are 30, then his points become 40

4. If a player scores and its points are 40, then he wins the game. His games are increased

by one and points of both players are reset to 0

5. If a player wins 6 games, then he wins the set. His sets are increased by one and points

and games of both players are reset to 0

6. If a player wins 3 sets, then we wins the match

# LoL_match_predictions_RF
Small project to predict the outcome of a LoL match

League of Legends (abbreviated LoL) is a multiplayer online battle arena video game developed and published by Riot Games for Microsoft Windows and macOS.
In League of Legends, players assume the role of an unseen "summoner" that controls a "champion" with unique abilities and battle against a team of other players or computer-controlled champions. 
The goal is usually to destroy the opposing team's "nexus", a structure that lies at the heart of a base protected by defensive structures, although other distinct game modes exist as well.
Each League of Legends match is discrete, with all champions starting off fairly weak but increasing in strength by accumulating items and experience over the course of the game.

League of Legends ranked matches were analyzed and a random forest classification algorithm was developed to predict match scores. 

Features:

* Winner (1 = team1, 2 = team2).

* First Baron, dragon, tower, blood, inhibitor and Rift Herald (1 = team1, 2 = team2, 0 = none).

* The number of tower, inhibitor, Baron and dragon kills each team has.

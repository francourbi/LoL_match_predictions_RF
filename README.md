# LoL_match_predictions_RF
Small project to predict the outcome of a LoL match

League of Legends (abbreviated LoL) is a multiplayer online battle arena video game developed and published by Riot Games for Microsoft Windows and macOS.
In League of Legends, players assume the role of an unseen "summoner" that controls a "champion" with unique abilities and battle against a team of other players or computer-controlled champions. 
The goal is usually to destroy the opposing team's "nexus", a structure that lies at the heart of a base protected by defensive structures, although other distinct game modes exist as well.
Each League of Legends match is discrete, with all champions starting off fairly weak but increasing in strength by accumulating items and experience over the course of the game.

League of Legends ranked matches were analyzed and a random forest classification algorithm was developed to predict match scores. 

## THE GAME

Summoner's Rift is the most popular map in League of Legends.

On this map type, two teams of five players compete to destroy an enemy building called a Nexus, which is guarded by the enemy team and a number of defensive structures called turrets, or towers.

One nexus is located in each enemy base on opposite sides of the map, in the lower-left and upper-right hand corners.

These structures continually create weak non-player characters known as minions, which advance toward the enemy base along three paths: top, middle, and bottom lanes.

Players compete to advance these waves of minions into the enemy base, which allows them to destroy enemy structures and ultimately win the match.

Between lanes are neutral areas of the map known as the 'jungle', arrayed in four quadrants. A shallow river divides the map between the teams, but doesn't actually impede movement; all champions can wade through it no differently than dry land.

Each team wishes to defend their own structures and destroy the other team's structures. These include:

Towers – Each lane is guarded by powerful defensive structures called turrets or towers. Every team has 11 towers in total.

Inhibitor – Each lane contains one Inhibitor. A lane's Inhibitor can be attacked after a team has destroyed the three turrets guarding its lane.

Elemental Drakes/Elder Dragon – Elemental drakes are powerful monsters located in the bottom half of the river. All members of the team that kills the drake are provided with buffs that last the entire game and accrue cumulatively. The drakes are flavored after the Four Elements, with each drake granting a thematically appropriate buff. A random elemental drake will respawn six minutes after the previous one is killed. The Elder Dragon spawns instead after 35 minutes have passed in-game. When killed, it provides a stronger buff than an individual elemental drake, but is temporary, unlike the earlier drake rewards.

Rift Herald – The Rift Herald is a powerful enemy located in the upper side of the River. Killing the Rift Herald allows it to be summoned again as a battering ram to attack enemy towers.

Baron Nashor – Baron Nashor is the most powerful neutral enemy, located in the upper side of the River. It will spawn after twenty minutes, replacing the Rift Herald.

Nexus – Each team has a Nexus that can only be damaged once all the turrets in a lane, that lane's inhibitor and the Nexus turrets are destroyed. Destruction of the enemy team's Nexus ends the game.

Features used:

* Winner (1 = team1, 2 = team2).

* First Baron, dragon, tower, blood, inhibitor and Rift Herald (1 = team1, 2 = team2, 0 = none).

* The number of tower, inhibitor, Baron and dragon kills each team has.

Locations
=========
WorldSpawn/Dev:	0 64 0
Map Lobby:		0 64 500

SpeedCraft		
----------
Lobby: 0 150 1008

**Track 1**
Start: 2000 66 2000 North Facing
Finish 2000 66 2015 North Facing

Global Variables scoreboard (vars)
==================================
Uses fake players to hold values

**MapState**
0 = NotLoaded
1 = Loaded

Game Rules
==========
commandBlockOutput false
doDaylightCycle false
logAdminCommands false
doMobSpawning false
mobGriefing false

Lobby Status scoreboard (lobbyStatus)
=====================================
Used to specify lobby position (or trigger movements) of each player
0 = Move to main lobby
1 = In main lobby
2 = Move to SpeedCraft
3 = in SpeedCraft

Global Variables scoreboard (vars)
==================================
**SpeedCraft_GameState**
0 = NotLoaded
1 = Loaded
2 = Tutorial
3 = SingleRace
4 = Championship

**FUTURE: SpeedCraft_CurrentTrack**
1 = Jungle (running)
2 = Beach (running)
3 = Ice Plains (boats)
4 = Moutains/Caves (elytra)
5 = ???

**SpeedCraft_RaceState**
1 = Stopped
2 = Starting
3 = Started
FUTURE: 4 = FirstPlayerFinished
FUTURE: 5 = SecondPlayerFinished
FUTURE: 6 = ThirdPlayerFinished
FUTURE: 7 = AllPlayersFinished

Current Race scoreboard (current)
=================================
Used to specify the finishing position for each player

0 = Not completed race / No position
1 = First position
2 = Second position
3 = Third position

Other scoreboards
=================
**Checkpoints Reached (checkpoints):** 
Used to display which checkpoints have been reached by each player. 
Gives other players an idea of how far ahead/behind they are.

**Races Won (races):**
Used to display how many races a player has won in the current championship.
This will be reset whenever a new 'championship' is started.



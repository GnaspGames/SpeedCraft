Global Variables scoreboard (vars)
==================================
Uses fake players to hold values

**MapState**
0 = NotLoaded
1 = Loaded

**SpeedCraft_GameState**
0 = NotLoaded
1 = Loaded
2 = Tutorial
3 = SingleRace
4 = Championship

**FUTURE: SpeedCraft_CurrentTrack**
1 = Jungle
2 = Beach
3 = ?
4 = ?
5 = ?

**SpeedCraft_RaceState**
1 = Stopped
2 = Starting
3 = Started
4 = FirstPlayerFinished
5 = SecondPlayerFinished
6 = ThirdPlayerFinished
7 = AllPlayersFinished

Game Rules
==========
commandBlockOutput false
doDaylightCycle false
logAdminCommands false
doMobSpawning false
mobGriefing false

FUTURE: Lobby Status scoreboard (lobbyStatus)
=====================================
Used to specify lobby position (or trigger movements) of each player
0 = Move to main lobby
1 = In main lobby
FUTURE: 2 = Move to SpeedCraft
FUTURE: 3 = in SpeedCraft


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



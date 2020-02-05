Memo Game Readme
================

Simple game field

Initials:
Size = N x N. The start is from 4x4. The end might be 20x20. 
Amount of gaming cells must be even. 
If is not even then the central one is out of game (black color or has face and marked as unavailable).
Initially all cells are face upped. 

Game flow:
If player click on cell then the cell turns/opens. 
If it is opened/turned two cells then needto wait for a while (T sec). If cells have the same value then they disapear/clear/make unavailable and player gets winner point.
If the cells is not mach then they turn back to face and player gets steps point.

Game end:
Game ends when there are no available cells. If game ends then show winner banner with time or steps point or winner points and propose to continue or end the game.

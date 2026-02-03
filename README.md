# Guardia e Ladro 1

The goal is to develop an application simulating a game called Guard and Thief.
A user (player) is identified by their first and last name.
The game takes place in a room with a tiled floor (squares), with external and internal walls. In the room, there is a guard and a thief. The player’s goal is to allow the thief to escape from the room.

Both the thief and the guard move one square at a time among the eight adjacent squares. Multiple scenarios must be supported. For each scenario, the guard’s movement strategies are as follows (K is the probability):

* In K% of cases, the guard moves randomly to one of the eight possible adjacent squares (if not blocked by a wall);
* In (100 − K)% of cases, the guard’s direction is calculated using the ant colony optimization algorithm.

## Additionally, in the room there are objects of different colors available for the thief:

<div style="text-align:left">
    <p>Green – the guard moves in the opposite direction of the thief for 10 seconds.</p>
    <img src="https://github.com/Atymia/Programmazione_3/assets/92294051/70722189-76d6-416d-b6f7-8dc91b10ebf6" alt="verde">
</div>

<div style="text-align:left">
    <p>Yellow – the guard moves in a random direction for 10 seconds.</p>
    <img src="https://github.com/Atymia/Programmazione_3/assets/92294051/f0f66375-7dd0-4ed3-a5fa-0df3a08c93c9" alt="giallo">
</div>

<div style="text-align:left">
    <p>ed – the guard moves toward the exit (ant colony optimization).</p>
    <img src="https://github.com/Atymia/Programmazione_3/assets/92294051/078b2dbc-48d6-4803-adf7-d40b15ff479e" alt="rosso">
</div>

Write a program to manage the game that displays, at the beginning and end of each match, the leaderboard of best results achieved by all players in all matches (i.e., the lowest number of steps needed to reach the exit).


## Authors

- [@atymia](https://github.com/Atymia)
- [@ssdj3nt](https://github.com/Ssdj3nt)

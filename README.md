# AB_Testing_Cookie_Cats

---

## About The Dataset:

### Context

This dataset includes A/B test results of Cookie Cats to examine what happens when the first gate in the game was moved from level 30 to level 40. When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.

### Content

The data we have is from 90,189 players that installed the game while the AB-test was running. The variables are:

<b>userid:</b> A unique number that identifies each player.

<b>version:</b> Whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).

<b>sum_gamerounds:</b> the number of game rounds played by the player during the first 14 days after install.

<b>retention_1:</b> Did the player come back and play 1 day after installing?

<b>retention_7:</b> Did the player come back and play 7 days after installing?

When a player installed the game, he or she was randomly assigned to either.

## Outcome and Analysis

Number of Unique Players: 90189

The number of players in each version is very balanced the data is not very skewed.(gate_30->49.56% and gate_40->50.44%)

The percentage of Players installing the game and never playing it is 4.43%

There is no statistically significant difference between 'gate30' and 'gate40' with 95% confidence

A little less than half of the players (44.52%) come back one day after installing the game. 18.61% of the players come back 7 day after installing the game.

There was a slight decrease in 1-day retention when the gate was moved to level 40 (44.2%) compared to the control group when it was at level 30 (44.8%).

A decrease in 7-day retention when the gate was moved to level 40 (18.2%) compared to the control group when it was at level 30 (19.8%).

Percentage of returning players of control group after 7 day is 19.0%, whereas Percentage of returning players of experimental group is 18.2%

Movement of gate to the 40th level affects negatively on numbers of returning players after 7 days

The bootstrap result tells us that there is strong evidence 99.8% probability that 7-day retention is higher when the gate is at level 30 than when it is at level 40.

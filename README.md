# LCR-odds

Goal of program:
- Get better at using Python (2.7.6)
- Determine the probability of winning a round of "LCR" ((based on seating position, number of players, and initial chip count)
- Allow for analysis of various LCR setup scenarios to better understand where an optimal player should sit

What is LCR (per wikipedia):
- LCR, or Left Center Right, is a dice game for three or more players, published by George & Company LLC in 1992.
- The game comes with three dice and numerous chips.
- It is entirely a game of chance. The players make no decisions of any kind, even as to wagering.

Setup and play (per wikipedia):
- Each player receives at least 3 chips. 
- Players take it in turn to roll three six-sided dice, each of which is marked with "L", "C", "R" on one side, and a single dot on the three remaining sides. For each "L" or "R" thrown, the player must pass one chip to the player to their left or right, respectively. A "C" indicates a chip to the center (pot). A dot has no effect.
- If a player has fewer than three chips left, they are still in the game but their number of chips is the number of dice they roll on their turn, rather than rolling all three. When a player has zero chips, they pass the dice on their turn, but may receive chips from others and take their next turn accordingly. The player who does not receive chips after two passes is out of the game. The winner is the last player with chips left.[1][2]

Deviations from Wikipedia's rules used for this analysis:
- My family does not use the rule that a player who does not receive chips after two passes is out of the game, so I have not included it in my analysis.

# Connect_4_using_RL

Minimax is a decision-making algorithm, typically used in a turn-based, two player games. The goal of the algorithm is to find the optimal next move.
In the algorithm, one player is called the maximizer, and the other player is a minimizer. If we assign an evaluation score to the game board, one player tries to choose a game state with the maximum score, while the other chooses a state with the minimum score.
In other words, the maximizer works to get the highest score, while the minimizer tries get the lowest score by trying to counter moves.
It is based on the zero-sum game concept. In a zero-sum game, the total utility score is divided among the players. An increase in one player's score results into the decrease in another player's score. So, the total score is always zero. For one player to win, the other one must lose.

## Pygame Installation 
Pygame requires Python; if you don't already have it, you can download it from python.org. Use python 3.7.7 or greater, because it is much friendlier to newbies, and additionally runs faster.

The best way to install pygame is with the pip tool (which is what python uses to install packages). Note, this comes with python in recent versions. We use the --user flag to tell it to install into the home directory, rather than globally.
```
python3 -m pip install -U pygame --user
```
To see if it works, run one of the included examples:

```
python3 -m pygame.examples.aliens
```
### Run the code

Enter the following to run the code.

```
cd code
python3 connect_4_using_RL.py
```

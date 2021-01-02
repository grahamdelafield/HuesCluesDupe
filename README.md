# HuesCluesDupe

<img src="https://github.com/grahamdelafield/HuesCluesDupe/blob/master/colorwheel.png" align="right"
     alt="Colorwheel" width="120" height="178">

This code emulates a simple version of the board game Hues and Cues (https://boardgamegeek.com/boardgame/302520/hues-and-cues). This is done purely for exercise; I own no intellectual property or rights to the board game.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This desktop game was built using Python v3.8.2 and various packages that can be installed with pip or equivalent package manager.

To get started with Python: https://www.python.org/downloads/
To read more on Pip: https://packaging.python.org/tutorials/installing-packages/

### Installing

Get the sourcode
```
# clone directory
git clone https://github.com/grahamdelafield/HuesCluesDupe
```

Navigate to directory and instal packages
```
# navigate to /users/some_path/HuesCluesDupe
pip install -r requirements.txt
```

Run with Python
```
python '.\HuesCues.py'
```

## How to play

1. Enter a name for each player in the field below 'Player x' (If two players have the same name, make sure they are distinguished in some way. Otherwise they will share a score for every round)
2. At the bottom of the screen is your clue. It is your job to place a marker on the colorwheel as close to the true location of the clue color as possible.
3. When ready to take a turn, select the 'Player x' button above your name and click on the colorwheel to place your guess. You only guess once in this game, so choose wisely!
4. Select the next player button and repeat until all players have gone.
5. When all players have submitted guesses, press the 'Show Answer' button at the bottom.
6. The answer coordinates will appear as a large black circle. The player whose guess is closest to the answer coordinates will earn a point, which will be reflected in the plot to the right.
7. The game is coded to play to 10 points, but you can decide amongst yourselves how much or how little you wish to play!
8. If you wish to restart the game, press the 'Play Again' button and all components will reset. (Notice: the names do not change after pressing 'play again', so make sure you change them when players enter/exit.)


## Authors

* **Graham Delafield** - [See my resume](https://www.grahamdelafield.com)

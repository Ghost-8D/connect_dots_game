# connect_dots_game
This is a small game implemented in java, where two players can play the connect the dots game. There is no AI behind this game so two players are required to play this game.

### Requirements
- javac >= 11.0.2

### Usage
To compile the java file use:
```bash
cd connect_dots_game
javac Dots.java
```

To run the program use:
```bash
java Dots
```

### How to play
The game is very simple:
- The player clicks between two dots to draw a line.
- When the player hovers over a valid move a line is displayed with the current player's color.
- When a player completes a square box (places the last line to form the box) the box will be colored with the player's color (green or red) and the player receives one point. In addition, the player who scores a point gets an extra move and can chain multiple moves as long as he/she keeps completing boxes. 
- The game finishes when there are no more lines to draw and the player with the most points is the winner.

This is an overveiw of the game's User Interface (UI):
![]()

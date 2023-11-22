**On-Fairy-Line**

This project is based on the board game Fairy Tile, a simplified model of the game implemented in an online space. In this React-based board game implementation, I plan to use the following technologies:
- MySQL database
- React-based frontend
- Java (Springboot) back-end
- 3D technology, AI (?)

**I plan to implement the following functionalities in addition to the board game logic:**

- Admin interface: manage players, create new game elements (map elements, maps, etc.)
- Saving the game in a relational database linked to the game
- Implementation of communication between players (chat window implementation)
- Implementation of in-game music
- In the game, both the pieces and the track elements are displayed in 3D view on the screen.

**Short Description of the game:**

The game is a turn-based, mouse-controlled, simple logic-based co-op, takes about 1 hour to play. The game is played by only 2 players in version 1.0, but can be expanded to 3 or 4 players in the future (more players are not allowed due to the number of cards). Everyone will be dealt a number of cards at the start of the game, and then the board game board will appear on the screen with the characters. The characters have a fixed place on the board.

**Players' circles**

In a round, players can perform the following actions:
 - Move with any of the pieces
 - They can move with any piece of the board.
 - Add a new space to the playing field (version 2.0)
 - Use fairy dust (version 2.0) 

Players place an instruction on the card instructing them how each character should be positioned relative to the other. If this is met, they can keep the card and draw a new one. If not, they can decide whether to put the card back in the draw deck and draw a new one, or move one of the pieces.

**Winner**

The game ends when one of the players runs out of drawing cards. In this case, that player immediately wins.

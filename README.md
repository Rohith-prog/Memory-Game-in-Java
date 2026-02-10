# Memory-Game-in-Java
The Memory Game is a fun and simple two-player game that tests your memory. In this game, a set of cards is laid face down. Players take turns flipping two cards to find matching pairs. If the two cards match, they remain face up. If not, they are flipped back down. The game continues until all pairs are found.
In this article, we will build a Memory Game in Java that runs in the console. Players will select card positions using numbers, and the board will update after every move.

**Game Board Layout**
The game has 8 cards in total, which is made up of 4 matching pairs. Each card is numbered from 0 to 7. When a player flips over two cards, their values are shown. If the cards match, then they stay face up. If not, then they’re turned back down again.

**How to Play the Game**
The steps to play the game are listed below:

The game board has 4 pairs of cards (8 total), which are randomly shuffled.
The board is shown as a row of numbered slots from 0 to 7.
On each turn:
A player selects two different indices to flip.
If the values match, the pair remains visible.
If the value does not match, then they are hidden again.
The game will end when all the pairs are found.
**Key Concepts Used**
We are using an array to manage the game state:
Cards: We are using an ArrayList<String> to store and shuffle the card values.
Board: We are using a String[] array to show the current state.
Flipped: We are using a boolean[] array to track which cards have been flipped.

# Text101-Game

*This is my first Unity 2d game.*

This game is a very simple text adventure. The user will read the story and press a single key from a list of one or more. 
The computer then will display a new screen of text in response to this input. Early examples of such games include 
Zork and Colossal Cave Adventure.  The story doesn’t matter in a way. We will be using the example of a very simple prison escape scene. The important thing is that the user knows at every stage what keys they can press, and that the computer responds appropriately to those key presses until the game is over. At the end of the game the text will simply state this, and invite the player to play again.  This simple game will be implemented as a “finite state machine”. This implementation is complete, and fine for a simple game. It has the advantage of making sure you are explicit about all the possible pickles the player can get into, leading to a rich set of interactions. The disadvantage of this approach is that it quickly becomes impossible to keep track.


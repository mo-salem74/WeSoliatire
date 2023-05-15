# WeSoliatire
Klondike card game made in C++, with the SFML graphics library, featuring drag-and-drop functionality.

-How to open the program:
1) Extract the compressed file. 
2) open the SRC directory.
3) open the cpp file.

-How to use the program:
1) Launch the cpp file.
2) Wait for the window to load and open.
3) Have Fun Playing.

Klondike Rules:

1) The player can move around the cards by clicking on them while holding and dragging them around.

2) To place cards above each other 2 things you need to keep in mind, 1. colors need to be different, and 2. cards getting placed need to be 1 number lower than the card already in place where K = 13, Q = 12, J = 11.

3) To Place cards in the foundation piles you need to place them in order starting from the Ace and then moving up to the K and you need to make sure the suit of the card matches the suit of the Foundation pile.

4) If a column is empty you can only place the K in the column.

5) If the player is stuck he can press the deck to get a card face-up and place it in the draws. There are 24 cards in the deck and you can only access the top card in the draws.

6) The player gains +5 score for placing the card in the column and a +10 score for placing a card in the foundation pile adding to +15 for each card if both targets are met.

7) The player needs to place all cards in the Foundation piles to win.


Note: This was built on a C++ programing language. On Clion IDE. Using SFML GUI.

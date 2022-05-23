# NetGame
 Net based game

Instructions:

Using Visual Studios(Choose Windows Form App .net framework)

A deck of playing cards has 52 cards: A, 2, 3, 4, 5, 6, 7, 8. 9,10, J, Q, K in each suit of clubs, spades, diamonds, and hearts. In the game of 21, the player closest to 21 points without exceeding 21 wins. Cards 2-10 have their face (pip) value. J, Q, and K each count as 10 points. The A can be 1 or 11 points as the player chooses. Each player is dealt two cards face up. Then as many more as desired, one player at a time, starting at the dealer’s left.
You will play the game against the House plus four other players. Label the six players as House, Playerl, Player2, Player3, Player4, Me. Create a graphic for each card dealt, such as a rectangle of the proper color (clubs, spades = black; diamonds, hearts = red) with the suit and value number/letter in the rectangle, or you may prefer to get card images from the Internet.

Each player should have the capacity for six cards dealt. Use a random number generator to determine each card dealt to a player. Note that the same card cannot be dealt twice. Below each player’s cards include two radio buttons labeled “Hit” and “Stand”. The House docs not have the radio buttons but instead will stand if dealt “Blackjack” (Ace plus 10-count card) in the first two cards, or when the House’s point total is a “hard” 17 (Ace counted as 11 unless it puts the house over 21), or above. If the House point total is 16 or less, the House must take another card.

Once a player Stands, your program moves to the next player to the left. If any player’s total exceeds 21, your program indicates that player is “busted” and the player receives no more cards that hand. When all players are done, your program determines and announces the winner, or a tie if one exists, plus the score of the winning total for that hand. Grading for Problem #1
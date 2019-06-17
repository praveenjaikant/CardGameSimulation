# CardGameSimulation

## Simulating a card game:
In the classic card game War, a standard deck of (52) playing cards is shuffled and distributed evenly among two players (26 cards each). For each round of game play, the players lay out one card at a time (for our purposes, in order of how they have been dealt) and the player with the higher card wins the round (where Ace = 1, 2-10 equal their face value, and Jack, Queen, and King = 11, 12, 13, respectively, across each of the four suits: diamonds, hearts, clubs, spades). Ties are broken with additional plays until one player wins the full round (i.e., all of the cards played during the round, including those that were tied). Although variations of the game can continue until one player wins all of the cards, let's consider the simple case in which cards won during a previous round cannot be replayed.

A variant of War, called Addition War, consists of two cards being played by each player at a time, where the player with the higher sum of two card values wins the round. Similar to the original game, ties are broken with additional plays of two cards each until one player wins all of the cards in the round. Once all cards have been played (once), the player with the higher score (sum of collected card values) wins the game. If the players run out of cards in the middle of a tiebreaker, assume that each player's respective cards (for that round) are returned to them for the final score.

### Packages used: NumPy and Pandas

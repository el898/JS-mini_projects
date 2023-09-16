
### Project One: Counting Cards

#### Description

In the casino game Blackjack, players can gain an advantage over the house by employing a strategy called **Card Counting**. The idea behind card counting is to keep track of the relative number of high and low cards remaining in the deck.

Here's how the card values are assigned:

 **High Cards (Count as +1):** 2, 3, 4, 5, 6
 **Neutral Cards (Count as 0):** 7, 8, 9
 **Low Cards (Count as -1):** 10, 'J', 'Q', 'K', 'A'

For this project, you will create a JavaScript function that simulates card counting. The function will take a card parameter (which can be a number or a string) and adjust a global count variable based on the card's value as per the table above. It will then return a string with the current count and a decision for the player:

 **If the count is positive**, the player should "Bet."
 **If the count is zero or negative**, the player should "Hold."

#### Example

 If the function receives a sequence of cards that result in a count of -3, it should return: `-3 Hold`.
 If the function receives cards that lead to a count of 5, it should return: `5 Bet`.

#### Tips

  Do NOT reset the count to 0 when the card value is 7, 8, or 9.
  Do NOT return an array.
  Do NOT include quotes (single or double) in the output.

This project is a great exercise to practice JavaScript logic and decision-making based on specific criteria.


# CASINO GAME

This program simulates a virtual baccarat table where players can place bets on either the Banker or the Player. The game is played with randomly generated cards, and the winner is determined based on the total value of the cards.

## How to Play

1. **Starting the Game**
   - Run the program and enter your name when prompted.
   - You will start with a balance of Rs. 10,000.

2. **Placing Bets**
   - Choose whether to bet on the Banker or the Player.
   - Enter the amount you want to bet. Your bet cannot exceed your current balance.

3. **Dealing Cards**
   - Random cards are generated for both the Banker and the Player.
   - If either the Banker or the Player gets a natural win (8 or 9), the game ends.

4. **Determining the Winner**
   - If neither the Banker nor the Player gets a natural win, additional cards may be drawn.
   - The winner is determined based on the total value of the cards.

5. **Winning and Losing**
   - If you bet on the winning hand, you win an amount equal to your bet.
   - If it's a tie, your bet amount is returned.
   - If you lose, your bet amount is subtracted from your balance.

6. **Playing Again**
   - After each round, you can choose to play again or exit the game.
   - If your balance reaches zero, you cannot play again.

## How to Run

Compile and run the code using a C++ compiler. Make sure to have the necessary libraries included (`iostream`, `ctime`, `string`).

## Game Logic

- The game uses random number generation for card values.
- It checks for natural wins (8 or 9) at the start of each round.
- The winner is determined based on the total card values, with rules similar to traditional baccarat.

## Developer

This program was developed by Paras Tyagi.
Email: parastyagi1105@gmail.com

---------------------------------------------------------------------------------------------------------------------------------------------------


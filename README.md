# 🎰 Console Casino Game in C

A fun, interactive console-based Casino game built in the C programming language. This project includes four classic games: **Roulette**, **Blackjack**, **Slots**, and **Coin Flip**, where players can place bets, win (or lose) virtual money, and test their luck!

---

## 🛠 Features

- 💵 Start with your own custom balance
- 🎲 Choose from 4 exciting games:
  - **Roulette**
  - **Blackjack**
  - **Slots**
  - **Coin Flip**
- 📈 Balance updates automatically based on wins/losses
- 🔁 Unlimited play until you choose to exit
- 🎮 Simple text-based interface for ease of use

---

## 🎮 Games & Rules

### 1. Roulette
- Choose a number between 0 and 18.
- If your number matches the winning number, you win **18x** your bet.
- If not, you lose your bet.

### 2. Blackjack
- You and the dealer get a card (1–21).
- Higher card wins the bet.
- Equal cards = draw (no loss/gain).

### 3. Slots
- Spin 3 slots (each from 0–10).
- All 3 match → Jackpot! Win **10x** bet.
- 2 match → Win **0.5x** bet.
- No match → Lose the bet.

### 4. Coin Flip
- Pick Heads or Tails.
- If you guess right → Win **1x** bet.
- If wrong → Lose your bet.

---
##⚡What I Learned

Working on the Console Casino project in C allowed me to deepen my understanding of:

- **Modular Code Structure:** Organized the program into multiple functions, each handling a specific casino game and balance management, improving code clarity and maintainability.
- **Random Number Generation:** Used `rand()` and `srand(time(NULL))` to simulate randomness in games like Roulette, Slots, Blackjack, and Coin Flip.
- **Pointers:** Managed the player’s balance via pointer passing to update the balance across multiple functions.
- **Game Logic Implementation:** Translated casino game rules into functioning C code with appropriate win/lose conditions.
- **User Input Validation:** Implemented checks to handle invalid bets, choices, and inputs gracefully.
- **Console Interaction:** Created an interactive text-based menu-driven interface with clear prompts and game rules.
- **Debugging & Testing:** Refined logic through iterative debugging and testing to ensure fair gameplay and balance accuracy.

This project strengthened my core C programming skills and gave me practical experience creating interactive console applications with multiple game modules.

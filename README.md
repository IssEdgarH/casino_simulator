# Casino Simulator

**Authors**: Carlos, Fernando, Edgar, Oswaldo  
**Status**: Functional  
**Bugs**: None known  

## Description
The Casino Simulator is a C++ application where players can simulate various casino games, such as:
- Roulette
- Blackjack
- Number Guessing

Players can manage their chips at the cashier, enjoy a vending machine with snacks, and even visit a restaurant in the simulator. 

## Features
- **Player Account Management**: Players can sign up, earn chips, and check their balance.
- **Casino Games**: Enjoy classic games like Blackjack and Roulette.
- **Food Options**: Visit a vending machine or a restaurant with a menu.
- **Cashier System**: Deposit or withdraw chips as needed.

## Setup Instructions
1. Clone the repository: `git clone https://github.com/your-username/casino_simulator.git`
2. Compile the code:  
   ```bash
   g++ -std=c++11 -o casino_simulator main.cpp Cashier.cpp Item.cpp Player.cpp Roulette.cpp Vending.cpp NumberGuess.cpp BlackJack.cpp Slot.cpp
Run the executable: ./casino_simulator
Usage

Upon starting the simulator, you’ll see a menu with options to visit the cashier, play games, or buy food. Navigate through the options using the provided menu prompts.

## Requirements

Compiler: A C++ compiler that supports C++11 (like g++).
OS: macOS, Linux, or Windows.

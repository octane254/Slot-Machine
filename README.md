### 🎰 Slot Machine Game

A fun, interactive command-line slot machine game built with Node.js. Test your luck and try to win big!

## Features

- 💰 **Deposit System**: Start with your initial balance
- 🎯 **Flexible Betting**: Choose how many lines to bet on (1-3) and set your bet amount
- 🎪 **Realistic Spins**: Watch as the reels spin with random symbol combinations
- 🏆 **Winning Combinations**: Match symbols across your chosen lines to win
- 🔄 **Play Again**: Keep playing as long as you have money in your balance

## How to Play

1. **Deposit Money**: Enter your initial deposit amount to start
2. **Choose Lines**: Select how many lines you want to bet on (1, 2, or 3)
3. **Place Your Bet**: Enter your bet amount per line
4. **Spin**: The reels spin automatically with random symbols
5. **Check Results**: See if you've won with matching symbols!
6. **Play Again**: Continue playing or cash out

## Game Rules

- Each reel displays 3 symbols
- Symbols available: **A** (rare, 5x payout), **B** (4x payout), **C** (3x payout), **D** (2x payout)
- **Win Condition**: Match the same symbol across all columns on any of your bet lines
- Your balance updates after each spin
- Game ends when you run out of money

## Installation

### Prerequisites
- Node.js (v14 or higher)

### Setup

```bash
# Clone the repository
git clone https://github.com/octane254/Slot-Machine.git
cd Slot-Machine

# Install dependencies
npm install
```

## Usage

Run the game with:

```bash
node project.js
```

Follow the on-screen prompts to deposit, bet, and spin!

## Example Gameplay

```
You have a balance of $100
Enter the number of lines to bet on (1-3): 2
Enter your bet per line: $10

A | B | C
D | D | D
B | A | B

You won $20
```

## Symbol Payouts

| Symbol | Multiplier | Rarity |
|--------|-----------|--------|
| A      | 5x        | ⭐     |
| B      | 4x        | ⭐⭐   |
| C      | 3x        | ⭐⭐⭐ |
| D      | 2x        | ⭐⭐⭐⭐ |

## Technologies Used

- **Node.js**: Runtime environment
- **prompt-sync**: Synchronous user input handling

## Project Structure

```
Slot-Machine/
├── project.js          # Main game file
├── package.json        # Project metadata and dependencies
├── package-lock.json   # Dependency lock file
└── README.md          # This file
```

## Future Enhancements

- Add sound effects and animations
- Implement difficulty levels
- Create a leaderboard system
- Add bonus rounds and special features
- Multi-player support

## License

ISC

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## Author

Created by [octane254](https://github.com/octane254)

---

**Good Luck and Have Fun! 🍀**

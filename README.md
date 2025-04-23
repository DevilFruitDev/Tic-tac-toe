# JavaScript Games Collection

A collection of interactive browser games built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies - just pure web fundamentals.

## 🎮 Games Included

### 1. Dice Game
A simple dice rolling game where you compete against an opponent to get the higher roll.

**Features:**
- Random dice rolling with visual dice faces
- Win/loss/tie tracking
- Game statistics and win rate calculation
- Responsive design

![Dice Game Screenshot](screenshots/dice-game.png)

### 2. Limited Marks Tic Tac Toe
A strategic twist on the classic Tic Tac Toe game where each player can only have 3 marks on the board at a time.

**Features:**
- Limited to 3 marks per player - when you place a 4th mark, your oldest mark disappears
- Visual indicator showing which mark will disappear next
- Smooth animations for disappearing marks
- Winning line animation
- Detailed game statistics panel with:
  - Win rate tracking with visual progress bars
  - Game history with timestamps
  - Stats that persist during your session
- Responsive design for all devices

![Tic Tac Toe Screenshot](screenshots/tic-tac-toe.png)

## 🚀 Getting Started

### Play Online
You can play the games directly on GitHub Pages: [Play Games](https://yourusername.github.io/js-games/)

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/js-games.git
   ```

2. Open any of the HTML files in your browser:
   ```bash
   cd js-games
   # Open dice-game.html or limited-tic-tac-toe.html in your browser
   ```

## 💻 Implementation Details

These games are built with:
- **HTML5** - For structure and content
- **CSS3** - For styling and animations
- **JavaScript** - For game logic and interactivity

No external libraries or frameworks are used, making this project excellent for learning web development fundamentals.

### Key JavaScript Concepts Demonstrated
- DOM manipulation
- Event handling
- Game state management
- Animations and transitions
- Randomization
- Win condition checking
- Statistics tracking

## 🛠️ Development

### Project Structure
```
js-games/
├── dice-game.html           # Dice rolling game
├── limited-tic-tac-toe.html # Limited marks tic-tac-toe game
├── screenshots/             # Screenshots for documentation
│   ├── dice-game.png
│   └── tic-tac-toe.png
└── README.md                # This file
```

### Future Enhancements
- [ ] Add sound effects
- [ ] Implement local storage to persist game statistics between sessions
- [ ] Add AI opponents with adjustable difficulty
- [ ] Create mobile-optimized touch controls
- [ ] Add more games to the collection

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! If you'd like to add features, fix bugs, or improve the games:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📬 Contact

Your Name - [@yourusername](https://twitter.com/yourusername) - email@example.com

Project Link: [https://github.com/yourusername/js-games](https://github.com/yourusername/js-games)

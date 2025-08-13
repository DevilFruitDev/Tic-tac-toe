# 🎯 Limited Marks Tic Tac Toe

A strategic twist on classic Tic Tac Toe where players can only have 3 marks on the board at once. When placing a 4th mark, your oldest mark disappears - turning a solved game into an evolving puzzle.

[![Play Now](https://img.shields.io/badge/Play-Live_Demo-brightgreen)](https://yourusername.github.io/limited-tictactoe/)
![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-No_Dependencies-yellow)
![Size](https://img.shields.io/badge/Size-<20KB-green)
![License](https://img.shields.io/badge/License-MIT-blue)

## The Twist 🔄

Traditional Tic Tac Toe is a solved game - perfect play always leads to a draw. **This version breaks that.**

- **3 Mark Limit** - Each player can only have 3 marks on the board
- **Auto-Removal** - Your 4th move removes your oldest mark
- **Visual Indicators** - Orange dots show which marks will disappear next
- **Dynamic Strategy** - Winning positions can suddenly become vulnerable

## Features ✨

### Gameplay
- **Limited Marks System** - Core mechanic that changes everything
- **Smooth Animations** - Fade effects when marks disappear
- **Win Detection** - Instant highlighting of winning combinations
- **Visual Feedback** - Clear indicators for current player and oldest marks

### Statistics Tracking
- **Win Rates** - Live progress bars for each player
- **Game History** - Last 10 games with timestamps
- **Session Stats** - Total games, wins, draws
- **Clear Function** - Reset stats without losing current game

### UI/UX
- **Clean Design** - Minimalist interface that stays out of the way
- **Responsive Layout** - Works on all screen sizes
- **Collapsible Stats** - Click to show/hide statistics panel
- **Color Coding** - Pink for X, Blue for O, Orange for warnings

## Quick Start 🚀

### Play Online
Simply open `index.html` in any modern browser. No installation, no dependencies.

### Deploy Your Own
```bash
# Clone the repo
git clone https://github.com/yourusername/limited-tictactoe.git

# Open in browser
open index.html

# Or serve locally
python3 -m http.server 8000
```

### GitHub Pages
1. Push to GitHub
2. Settings → Pages → Deploy from main
3. Share your game link!

## How It Works 🧠

### Core Algorithm
```javascript
// Track each player's moves in order
let xMoves = []; // [oldest, ..., newest]
let oMoves = [];

// When a player makes their 4th move
if (xMoves.length > 3) {
    const oldestMove = xMoves.shift(); // Remove oldest
    clearCell(oldestMove);             // Clear from board
}
```

### The Strategy Layer
Unlike classic Tic Tac Toe, this version requires:
- **Defensive Planning** - Your winning move might disappear
- **Offensive Timing** - Strike when opponent's key piece is about to vanish
- **Board Reading** - Track both current positions AND move order
- **Adaptation** - Strategies must evolve as marks cycle

## Technical Details 📊

### Architecture
- **Single File** - Everything in one HTML file
- **Pure CSS Animations** - No animation libraries
- **Vanilla JavaScript** - No frameworks needed
- **Local State** - No backend required

### Performance
- **Size**: < 20KB total
- **Load Time**: Instant
- **Dependencies**: Zero
- **Browser Support**: All modern browsers

### Code Structure
```
index.html
├── Styles (Internal CSS)
│   ├── Layout & Typography
│   ├── Game Board Styling
│   ├── Animation Keyframes
│   └── Statistics Panel
└── Script (Vanilla JS)
    ├── Game State Management
    ├── Move Validation
    ├── Win Detection
    ├── Statistics Tracking
    └── UI Updates
```

## Why This Exists 🤔

Classic Tic Tac Toe has a fundamental flaw: it's solved. Perfect play always results in a draw. This variant introduces **managed chaos** - your perfect strategy can crumble when that crucial center square you placed three moves ago suddenly vanishes.

The result? A game that's:
- **Always Winnable** - No guaranteed draws
- **Never Repetitive** - Board states constantly evolve
- **Strategically Deep** - Multiple layers of planning required
- **Actually Fun** - Even for adults who've outgrown classic version

## Contributing 🤝

This is a complete game, but improvements are welcome:

### Potential Enhancements
- [ ] AI opponent with difficulty levels
- [ ] Online multiplayer
- [ ] Tournament mode
- [ ] Custom board sizes (4x4, 5x5)
- [ ] Time limits per move
- [ ] Sound effects
- [ ] Dark mode

### Code Style
- Keep it vanilla (no frameworks)
- Maintain single-file simplicity
- Comment complex logic
- Test on mobile devices

## Credits & License

Built with vanilla JS to prove simple games don't need complex tools.

MIT © [Your Name]

---

<p align="center">
  <strong>When three marks aren't enough, but four is too many</strong>
  <br>
  <em>Sometimes the best games come from simple rule changes</em>
</p>

<div align="center">

# Pro Chess ♟️

</div>

A modern, feature-rich chess application with AI opponent, local multiplayer, and competitive leaderboard system.

## 🎮 Features

- **Play vs AI** - Challenge an intelligent AI opponent with adjustable difficulty levels
- **Local Multiplayer** - Play 1v1 against friends on the same device
- **Leaderboard System** - Track wins, losses, draws, and win rates
- **Time Controls** - Multiple time formats including Fischer +2s increment
- **Move History** - Review all moves with previous/next navigation
- **PGN Export** - Export games in standard PGN (Portable Game Notation) format
- **Difficulty Levels** - Adjustable AI difficulty (Easy, Medium, Hard)
- **Real-time Timers** - Visual countdown timers for both players
- **Move Validation** - Automatic detection of captured pieces and game state

## 🚀 Getting Started

### Prerequisites
- Web browser with JavaScript enabled
- Modern browser (Chrome, Safari, Firefox, Edge)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kschouhanpali-coder/pro-chess.git
cd pro-chess
```

2. Open the project in your local environment:
```bash
# Using Python 3
python -m http.server 8000

# Or using Node.js
npx http-server
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## 📖 How to Play

### Main Menu
- **Play vs AI** - Start a game against the computer
- **1 vs 1 Local** - Play against another player on the same device
- **Leaderboard** - View player statistics and rankings

### Game Screen
1. **Choose Your Side** - Select to play as White (first move) or Black
2. **Make Moves** - Click and drag pieces to move them
3. **Time Management** - Monitor your timer (default: 5 minutes with Fischer +2s)
4. **View History** - Use Previous/Next buttons to review moves
5. **End Game** - Resign, draw offer, or checkmate

### Game Controls
- **Resign** - Concede the game
- **Draw Offer** - Propose a draw to your opponent
- **Undo Last Move** - Return to previous board state
- **Export PGN** - Save your game in standard notation
- **Back to Menu** - Return to main menu

## 🎯 Game Modes

### Play vs AI
Challenge the computer at your preferred difficulty level:
- **Easy** - Basic strategy, limited lookahead
- **Medium** - Balanced play, tactical awareness
- **Hard** - Advanced tactics, positional mastery

### 1 vs 1 Local
Perfect for learning or casual play with friends. Both players use the same device with turn-based play.

### Leaderboard
Track your performance across all game modes:
- **Rank** - Your position in the standings
- **Wins** - Total victories
- **Losses** - Total defeats
- **Draws** - Stalemates and agreed draws
- **Win Rate** - Percentage of games won

## ⚙️ Time Controls

Default configuration:
- **Base Time**: 5 minutes per player
- **Increment**: Fischer +2 seconds (2 seconds added per move)

## 🛠️ Technologies

- **Frontend**: HTML5, CSS3, JavaScript
- **Board Rendering**: Canvas/SVG
- **AI Engine**: Chess algorithm with move validation
- **Storage**: Browser LocalStorage for leaderboard persistence
- **Hosting**: GitHub Pages

## 📋 Project Structure

```
pro-chess/
├── index.html              # Main entry point
├── css/
│   └── styles.css         # Application styling
├── js/
│   ├── chess.js           # Core chess engine
│   ├── ai.js              # AI opponent logic
│   ├── ui.js              # User interface management
│   └── leaderboard.js     # Leaderboard functionality
└── assets/
    └── pieces/            # Chess piece graphics
```

## 🎮 Keyboard Shortcuts

- `Esc` - Return to main menu
- `Z` - Undo last move (local games only)
- `E` - Export game as PGN

## 💾 Data Storage

Player statistics and leaderboard data are stored locally using:
- **Browser LocalStorage** - Persists data across sessions
- **PGN Format** - Standard chess notation for game export

Clear your browser cache to reset the leaderboard.

## 🐛 Known Issues & Limitations

- Three-fold repetition draw not automatically detected
- Fifty-move rule requires manual draw claim
- Offline play only (no online multiplayer)

## 📝 License

This project is licensed under the MIT License - see LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Areas for Contribution:
- Enhanced AI algorithm improvements
- Additional time control formats
- Online multiplayer integration
- Mobile app development
- UI/UX enhancements
- Bug fixes and optimizations

## 📧 Support

For bug reports or feature requests, please create an issue on GitHub.

## 🏆 Roadmap

- [ ] Online multiplayer support
- [ ] Tournament mode
- [ ] Advanced AI with opening book
- [ ] Puzzle mode
- [ ] Game analysis and evaluation
- [ ] Mobile app (iOS/Android)
- [ ] Multiplayer friends list
- [ ] Rated games and rating system

## 🙏 Acknowledgments

- Chess piece graphics and design inspiration
- Open-source chess engine libraries
- Community feedback and contributions

---

**Play, Learn, and Master Chess with Pro Chess!** ♟️

[Play Online](https://kschouhanpali-coder.github.io/pro-chess) | [GitHub Repository](https://github.com/kschouhanpali-coder/pro-chess)

*Last Updated: September 2026*

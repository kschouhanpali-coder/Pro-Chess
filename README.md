<div align="center">

# 📋 Pro Chess — Project Documentation

### Full technical & project reference for the Pro Chess web app

<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-c9a44c?style=flat-square)

[![Live Demo](https://img.shields.io/badge/▶_LIVE_DEMO-Play_Now-c9a44c?style=for-the-badge)](https://kschouhanpali-coder.github.io/Pro-Chess/chess.html)

</div>

<br/>

---

## 📖 Table of Contents

- [Project Summary](#-project-summary)
- [Objectives](#-objectives)
- [Core Features](#-core-features)
- [Technology Stack](#️-technology-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Usage Guide](#-usage-guide)
- [Roadmap](#️-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Credits & Contact](#-credits--contact)

<br/>

## 🎯 Project Summary

**Pro Chess** is a browser-based chess game built with HTML5, CSS3, and JavaScript. It delivers a premium dark-gold visual theme, full chess rule enforcement, an AI opponent, local two-player mode, and supporting features like move history, timers, and PGN export — all in a lightweight, dependency-light web app that runs instantly with no installation.

<br/>

## 🧭 Objectives

<div align="center">

| 🎮 No Backend Needed | 🤝 Two Ways to Play | 🎨 Distinct Visual Identity | 🧩 Simple Codebase |
|:---:|:---:|:---:|:---:|
| Runs fully client-side | AI or local 1v1 | Premium dark-gold theme | 3 core files, easy to extend |

</div>

<br/>

---

## ✨ Core Features

<table>
<tr>
<td valign="top" width="50%">

### 🎮 Game Modes
- Play against AI
- Local multiplayer (1 vs 1)

### ♟️ Chess Mechanics
- Interactive chessboard
- Legal move validation
- Turn-based gameplay
- Captured pieces tracking
- Resign and draw options

### ⏱️ Timer System
- Multiple time controls
- Fischer increment support
- Live countdown timers

</td>
<td valign="top" width="50%">

### 📜 Move Management
- Move history panel (prev/next)
- Resume latest position
- Undo last move
- PGN export support

### 🏆 Extras
- Leaderboard system
- Smooth, immersive interface

### 🎨 UI / UX
- Premium dark-gold theme
- Fully responsive layout
- Smooth animations & hover effects
- Elegant gold typography and accents

</td>
</tr>
</table>

<br/>

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Structure & layout |
| **CSS3** | Styling, theming, and animations |
| **JavaScript** | Game logic & interactivity |
| **[Chess.js](https://github.com/jhlywa/chess.js)** | Move validation & game rules *(if used)* |

No build tools, frameworks, or backend services are required — Pro Chess runs entirely client-side.

<br/>

---

## 📂 Project Structure

```bash
Pro-Chess/
│
├── chess.html      # Main game page (entry point)
├── style.css       # Styling and dark-gold theme
├── script.js       # Game logic, AI, and interactivity
└── README.md       # Project overview
```

| File | Responsibility |
|---|---|
| `chess.html` | DOM structure: board, panels, controls, timers |
| `style.css` | Visual presentation and responsiveness |
| `script.js` | Game logic, move validation hooks, AI, timers, history, PGN export |

<br/>

---

## 🧑‍💻 Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/kschouhanpali-coder/Pro-Chess.git
```

**2. Navigate into the project folder**
```bash
cd Pro-Chess
```

**3. Open `chess.html`** in your browser

**4. (Optional) Run a local server** — avoids browser restrictions on `file://` assets
```bash
python -m http.server 8000
# then visit http://localhost:8000/chess.html
```

**5. Start playing** ♟️

<br/>

---

## 🎮 Usage Guide

1. Open the game (locally or via the [live demo](https://kschouhanpali-coder.github.io/Pro-Chess/chess.html)).
2. Choose a mode: **vs AI** or **local 1v1**.
3. Select a time control, if desired.
4. Move pieces by clicking/dragging to legal squares.
5. Review past moves in the move history panel.
6. Resign or offer/accept a draw anytime.
7. Export the finished game as PGN to save or share.

<br/>

---

## 🗺️ Roadmap

- [ ] Online multiplayer support
- [ ] Adjustable AI difficulty levels
- [ ] Sound effects for moves and captures
- [ ] Match history / saved games
- [ ] Mobile app version

<br/>

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Check the [issues page](https://github.com/kschouhanpali-coder/Pro-Chess/issues) or submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a pull request

<br/>

---

## 📄 License

This project is open source under the **MIT License**. Feel free to use, modify, and share it with proper attribution.

<br/>

---

## 👤 Credits & Contact

<div align="center">

### ♟️ Made with precision — Pro Chess

For bugs, feature requests, or questions, open an issue on the [GitHub repository](https://github.com/kschouhanpali-coder/Pro-Chess/issues).

If you find this useful, consider giving it a ⭐ on GitHub!

[⬆ Back to top](#-pro-chess--project-documentation)

</div>

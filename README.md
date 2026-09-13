<div align="center" id="top">

# ♟️ PRO CHESS

<img src="https://img.shields.io/badge/-%E2%99%9F%20PREMIUM%20CHESS%20EXPERIENCE%20%E2%99%9F-0d0d0d?style=flat-square&labelColor=0d0d0d&color=c9a44c" alt="Premium Chess Experience"/>

### A premium, browser-based chess experience — dark-gold interface, zero installation

**📋 Project Documentation**

<br/>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

<p>
  <img src="https://img.shields.io/badge/status-active-2ea44f?style=flat-square" alt="status"/>
  <img src="https://img.shields.io/badge/license-MIT-c9a44c?style=flat-square" alt="license"/>
  <img src="https://img.shields.io/badge/build-passing-2ea44f?style=flat-square" alt="build"/>
  <img src="https://img.shields.io/badge/dependencies-minimal-c9a44c?style=flat-square" alt="dependencies"/>
  <img src="https://img.shields.io/badge/PRs-welcome-c9a44c?style=flat-square" alt="PRs welcome"/>
</p>

</div>

<br/>

## 📖 Table of Contents

| | | |
|---|---|---|
| [🎯 Overview](#-overview) | [🧭 Objectives](#-objectives) | [✨ Features](#-features) |
| [🛠️ Tech Stack](#️-tech-stack) | [📂 Project Structure](#-project-structure) | [🧑‍💻 Getting Started](#-getting-started) |
| [🎮 Usage Guide](#-usage-guide) | [🗺️ Roadmap](#️-roadmap) | [🤝 Contributing](#-contributing) |
| [❓ FAQ](#-faq) | [📄 License](#-license) | [👤 Credits & Contact](#-credits--contact) |

### 🔗 [Live Demo](https://kschouhanpali-coder.github.io/Pro-Chess/chess.html)

<br/>

---

## 🎯 Overview

**Pro Chess** is a full-featured chess game built entirely with **HTML5, CSS3, and JavaScript** — no frameworks, no backend, no build step. It pairs clean, rules-accurate gameplay with a refined **dark-gold interface** inspired by premium strategy games, making it as pleasant to look at as it is to play.

Whether you're sharpening your skills against the built-in AI or facing a friend across the same screen, Pro Chess is designed to feel fast, responsive, and polished from the first move.

<div align="center">

| ⚡ | 🧠 | 👥 | 🎨 |
|:---:|:---:|:---:|:---:|
| **Fast & Lightweight**<br/>No installs, runs instantly | **AI Opponent**<br/>Play solo, anytime | **Local 1v1**<br/>Challenge a friend | **Dark-Gold Theme**<br/>Premium, polished look |

</div>

<br/>

---

## 🧭 Objectives

- 🌐 Deliver a complete chess experience that runs **entirely client-side** — no accounts, downloads, or servers.
- 🤖 Support both **solo play** (vs AI) and **local multiplayer** (1v1 on one device).
- 🎨 Stand apart visually with a **refined, premium aesthetic** rather than a generic board UI.
- 🧩 Keep the codebase **lean and approachable** — three core files, easy to read and extend.

<br/>

---

## ✨ Features

<table width="100%">
<tr>
<th align="left" width="50%">♟️ Gameplay</th>
<th align="left" width="50%">🎨 Experience</th>
</tr>
<tr>
<td valign="top">

**Game Modes**
- Play against AI
- Local multiplayer (1 vs 1)

**Chess Mechanics**
- Interactive chessboard
- Legal move validation
- Turn-based gameplay
- Captured pieces tracking
- Resign & draw options

**Timers**
- Multiple time controls
- Fischer increment support
- Live countdown display

</td>
<td valign="top">

**Move Management**
- Move history with prev / next navigation
- Resume latest position
- Undo last move
- PGN export

**Extras**
- Leaderboard system
- Smooth, immersive interface

**Visual Design**
- Premium dark-gold theme
- Fully responsive layout
- Smooth animations & hover effects
- Elegant gold typography and accents

</td>
</tr>
</table>

<br/>

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Role |
|:---:|:---:|---|
| 🧱 Structure | **HTML5** | Semantic layout for board, panels, and controls |
| 🎨 Styling | **CSS3** | Theming, responsiveness, animation |
| ⚙️ Logic | **JavaScript** | Game state, interactivity, AI behavior |
| ♟️ Rules Engine | **[Chess.js](https://github.com/jhlywa/chess.js)** *(if used)* | Move validation & rule enforcement |

</div>

> No build tools, package managers, or backend services required — Pro Chess is a fully static, client-side app.

<br/>

---

## 📂 Project Structure

```bash
Pro-Chess/
│
├── chess.html      # 🎯 Main game page — entry point
├── style.css       # 🎨 Styling & dark-gold theme
├── script.js       # ⚙️ Game logic, AI, and interactivity
└── README.md       # 📖 Project overview
```

<div align="center">

| File | Responsibility |
|---|---|
| `chess.html` | DOM structure — board, panels, controls, timers |
| `style.css` | Visual presentation and responsive design |
| `script.js` | Game logic, move validation hooks, AI, timers, history, PGN export |

</div>

<br/>

---

## 🧑‍💻 Getting Started

<table>
<tr><td>

**1️⃣ Clone the repository**
```bash
git clone https://github.com/kschouhanpali-coder/Pro-Chess.git
```

**2️⃣ Navigate into the project**
```bash
cd Pro-Chess
```

**3️⃣ Open `chess.html`** in your browser

**4️⃣ (Optional) Serve locally** — avoids `file://` asset restrictions
```bash
python -m http.server 8000
# → visit http://localhost:8000/chess.html
```

**5️⃣ Start playing** ♟️

</td></tr>
</table>

<br/>

---

## 🎮 Usage Guide

1. **Launch** the game locally or via the [live demo](https://kschouhanpali-coder.github.io/Pro-Chess/chess.html).
2. **Choose a mode** — vs AI or local 1v1.
3. **Set a time control**, if desired.
4. **Move pieces** by clicking or dragging to legal squares.
5. **Track progress** in the move history panel — step back and forward freely.
6. **Resign or draw** at any point.
7. **Export** the finished game as PGN to save or share.

<br/>

---

## 🗺️ Roadmap

| Status | Feature |
|:---:|---|
| ⏳ | Online multiplayer support |
| ⏳ | Adjustable AI difficulty levels |
| ⏳ | Sound effects for moves and captures |
| ⏳ | Match history / saved games |
| ⏳ | Mobile app version |

<br/>

---

## 🤝 Contributing

Contributions, issues, and feature requests are genuinely welcome — this project grows with community input.

<table>
<tr><td>

1. 🍴 Fork the project
2. 🌱 Create your feature branch — `git checkout -b feature/amazing-feature`
3. 💾 Commit your changes — `git commit -m 'Add some amazing feature'`
4. 🚀 Push to the branch — `git push origin feature/amazing-feature`
5. 🔁 Open a pull request

</td></tr>
</table>

Check the [issues page](https://github.com/kschouhanpali-coder/Pro-Chess/issues) first to avoid duplicate work.

<br/>

---

## ❓ FAQ

**Do I need to install anything to play?**
No — just open `chess.html` in a browser, or use the [live demo](https://kschouhanpali-coder.github.io/Pro-Chess/chess.html).

**Does it work on mobile?**
Yes — the layout is fully responsive.

**Can I play online with a friend on different devices?**
Not yet — online multiplayer is on the [roadmap](#️-roadmap). Currently, local 1v1 requires sharing one device.

**Can I save or share a finished game?**
Yes — use the PGN export feature from the move history panel.

<br/>

---

## 📄 License

Released under the **MIT License** — free to use, modify, and share with proper attribution.

<br/>

---

## 👤 Credits & Contact

<div align="center">

### ♟️ Made with precision — Pro Chess

Built with HTML5, CSS3, and JavaScript · Move validation via Chess.js *(if used)*

For bugs, feature requests, or questions, open an issue on the
**[GitHub repository](https://github.com/kschouhanpali-coder/Pro-Chess/issues)**.

<br/>

**If you enjoyed this project, consider giving it a ⭐ on GitHub!**

[![GitHub stars](https://img.shields.io/github/stars/kschouhanpali-coder/Pro-Chess?style=social)](https://github.com/kschouhanpali-coder/Pro-Chess)

<br/>

**🔗 [Live Demo](https://kschouhanpali-coder.github.io/Pro-Chess/chess.html)** · **[⬆ Back to top](#top)**

</div>

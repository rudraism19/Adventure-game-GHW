# Mona and the Mossy Isles 🌿

<p align="center">
  <a href="index.html">
    <img alt="Play the game" src="https://img.shields.io/badge/PLAY%20THE%20GAME-%E2%96%B6-367758?style=for-the-badge" />
  </a>
  <img alt="Built with HTML, CSS and JavaScript" src="https://img.shields.io/badge/Built%20with-HTML%20%7C%20CSS%20%7C%20JavaScript-ea8a53?style=for-the-badge" />
  <img alt="No build step" src="https://img.shields.io/badge/Setup-No%20build%20step-4b9668?style=for-the-badge" />
</p>

**Mona and the Mossy Isles** is a small, self-contained pixel-art platform adventure. Guide Mona across a colorful island chain, collect five fish, avoid roaming crabs, and reach the gate before losing all three lives.

> No installation, package manager, or build process is needed. The game is implemented in a single `index.html` file.

## 🎮 Play

**[Open the game](index.html)** from the repository, or clone/download the repo and open `index.html` in a modern browser.

```bash
git clone https://github.com/rudraism19/Adventure-game-GHW.git
cd Adventure-game-GHW
```

Then open `index.html` in your browser. For local development, you can also start a simple static server from this directory:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000`.

## 🐾 How to play

1. Select **Set out** on the title screen.
2. Move and jump across platforms to find all **5 fish**.
3. Avoid crabs and gaps in the islands. Collisions and falls cost a life.
4. Reach the island gate at the far right after collecting every fish.

You begin with **3 lives**. Use the pause and restart controls whenever needed.

## 🕹️ Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move left | `←` or `A` | Left button |
| Move right | `→` or `D` | Right button |
| Jump | `Space`, `↑`, or `W` | Jump button |
| Pause / resume | `Esc` or pause button | Pause button |
| Restart | Restart button | Restart button |

## ✨ Features

- Pixel-art scenery rendered on an HTML canvas
- Side-scrolling island world with platforms and gaps
- Five collectibles, roaming crab enemies, and a three-life challenge
- Start, pause, restart, win, and game-over states
- HUD for fish collected and lives remaining
- Keyboard and mobile touch controls
- Responsive layout and reduced-motion preference support
- No external game engine or build tooling

## 🧰 Tech stack

- **HTML5** — page structure and canvas
- **CSS** — responsive interface, overlays, and styling
- **Vanilla JavaScript** — movement, physics, collisions, enemies, collectibles, and game states
- **Canvas 2D API** — pixel-style rendering

The Google Fonts import is used for typography; gameplay and rendering logic live in the page itself.

## 📁 Project structure

```text
Adventure-game-GHW/
├── index.html   # Game UI, styles, canvas rendering, and gameplay logic
└── README.md    # Project guide
```

## 🛠️ Development

Because everything is contained in `index.html`, you can edit the markup, styles, and JavaScript directly. Reload the browser to test your changes. No compilation or dependency installation is required.

## 🤝 Contributing

Contributions and ideas are welcome:

1. Fork the repository.
2. Create a feature branch.
3. Make and test your changes in a browser.
4. Open a pull request with a clear summary of the improvement.

## 📄 License

No license file is currently included in this repository. Contact the repository owner before redistributing or reusing the project beyond what GitHub's default terms permit.

---

<p align="center">Made for little adventures 🌱</p>

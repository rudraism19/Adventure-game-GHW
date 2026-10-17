# Mona and the Mossy Isles 🌿

<p align="center">
  <a href="index.html">
    <img alt="Play the game" src="https://img.shields.io/badge/PLAY%20THE%20GAME-%E2%96%B6-367758?style=for-the-badge" />
  </a>
  <img alt="Built with HTML, CSS and JavaScript" src="https://img.shields.io/badge/Built%20with-HTML%20%7C%20CSS%20%7C%20JavaScript-ea8a53?style=for-the-badge" />
  <img alt="No build step" src="https://img.shields.io/badge/Setup-No%20build%20step-4b9668?style=for-the-badge" />
</p>

**Mona and the Mossy Isles** is a lightweight, pixel-art platform adventure that runs directly in your browser. Guide Mona across a chain of colorful islands, collect all five fish, avoid roaming crabs, and reach the gate while keeping at least one of your three lives.

No installation or build tools required—the game is contained in a single `index.html` file.

## 🎮 Play the game

**[Launch Mona and the Mossy Isles](index.html)**

To run it locally, clone the repository:

```bash
git clone https://github.com/rudraism19/Adventure-game-GHW.git
cd Adventure-game-GHW
```

Open `index.html` in a modern browser. Alternatively, start a local static server:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## 🧭 Your mission

1. Choose **Set out** on the title screen.
2. Explore the islands and collect all **5 fish**.
3. Avoid crabs and watch your footing around gaps—collisions and falls cost a life.
4. Once every fish is collected, reach the gate at the far right to win.

You start with **3 lives**. Pause, resume, or restart the adventure whenever needed.

## 🕹️ Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move left | `←` or `A` | Left button |
| Move right | `→` or `D` | Right button |
| Jump | `Space`, `↑`, or `W` | Jump button |
| Pause / resume | `Esc` or pause button | Pause button |
| Restart | Restart button | Restart button |

## ✨ Features

- 🎨 Pixel-art island scenery rendered on an HTML canvas
- 🌊 Side-scrolling platform gameplay with gaps and jumps
- 🐟 Five collectibles to find before finishing the level
- 🦀 Roaming crab enemies and a three-life challenge
- 🏁 Start, pause, restart, victory, and game-over states
- 📊 HUD displaying collected fish and remaining lives
- 📱 Keyboard and mobile touch controls
- ♿ Responsive layout and reduced-motion preference support
- ⚡ No external game engine, dependency installation, or compilation step

## 🧰 Built with

| Technology | Purpose |
| --- | --- |
| **HTML5** | Page structure and canvas element |
| **CSS** | Responsive layout, interface, and overlays |
| **Vanilla JavaScript** | Player movement, physics, collisions, enemies, collectibles, and game states |
| **Canvas 2D API** | Pixel-style game rendering |

The project imports Google Fonts for typography; the gameplay and rendering logic live in the page itself.

## 📁 Project structure

```text
Adventure-game-GHW/
├── index.html   # Game UI, styles, canvas, and gameplay logic
└── README.md    # Project documentation
```

## 🛠️ Development

All game code is in `index.html`. Edit the file, save your changes, and refresh the browser to test them. No package manager or build process is needed.

## 🤝 Contributing

Ideas, fixes, and improvements are welcome:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes and test them in a browser.
4. Open a pull request describing what changed.

## 📄 License

A license file is not currently included. Before redistributing or reusing the project, check with the repository owner and consider adding an explicit open-source license.

---

<p align="center">Made for little adventures 🌱</p>

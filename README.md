# 🎯 Guess The Number Game

<div align="center">

![Game Banner](https://img.shields.io/badge/🎮_Guess_The_Number-Game-blueviolet?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A fun and interactive number guessing game built with vanilla HTML, CSS & JavaScript.**

[🕹️ Play Now](#-getting-started) · [📖 How to Play](#-how-to-play) · [✨ Features](#-features) · [🐛 Report Bug](https://github.com/Neemayg/Guess_The_Number_Game/issues)

</div>

---

## 📸 Preview

> A sleek retro-styled game where you pit your intuition against a randomly generated number. Can you crack the code before your score hits zero?

---

## ✨ Features

- 🎲 **Random Number Generation** — A secret number between 1 and 20 is generated each round
- 📊 **Score Tracking** — Start with 20 points; every wrong guess costs you one
- 🏆 **Highscore System** — Your best score is preserved across rounds
- 🔁 **Instant Replay** — Reset the game anytime with the **Again!** button
- 🎨 **Visual Feedback** — Background turns green on a correct guess with a satisfying animation
- 🕹️ **Retro Aesthetic** — Styled with the iconic *Press Start 2P* pixel font

---

## 🗂️ Project Structure

```
Guess_The_Number_Game/
│
├── index.html       # Game layout & structure
├── style.css        # Retro dark-themed styling
├── script.js        # Core game logic
└── README.md        # Project documentation
```

---

## 🚀 Getting Started

No installations or dependencies needed — it runs entirely in the browser!

### Option 1: Open Locally

```bash
# Clone the repository
git clone https://github.com/Neemayg/Guess_The_Number_Game.git

# Navigate into the project folder
cd Guess_The_Number_Game

# Open in your browser
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

### Option 2: Live Demo

> Simply download or clone the repo and open `index.html` in any modern browser. No server required!

---

## 📖 How to Play

1. 🔢 **Enter a number** between 1 and 20 in the input box
2. 🖱️ **Click "Check!"** to submit your guess
3. 📢 Read the feedback message:
   - `🔼 Too high!` — Your guess is above the secret number
   - `🔽 Too low!` — Your guess is below the secret number
   - `✅ Correct Number!` — You guessed it! Background turns green 🎉
   - `💀 You lost!` — Score reached zero, game over
4. 🏅 Your **highscore** is saved as long as the page stays open
5. 🔁 Click **"Again!"** to start a fresh round

---

## 🎮 Game Rules

| Condition | Result |
|---|---|
| Correct guess | Win! Score preserved, highscore updated |
| Wrong guess | Score decreases by 1 |
| Score reaches 0 | Game over — you lost! |
| Click "Again!" | New round, score resets, highscore stays |

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| **HTML5** | Game structure & layout |
| **CSS3** | Retro styling, animations, responsive layout |
| **Vanilla JavaScript** | Game logic, DOM manipulation, event handling |
| **Google Fonts** | *Press Start 2P* pixel font for retro aesthetics |

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/awesome-feature`)
3. **Commit** your changes (`git commit -m 'Add awesome feature'`)
4. **Push** to the branch (`git push origin feature/awesome-feature`)
5. **Open** a Pull Request

---

## 💡 Ideas for Improvement

- [ ] Add difficulty levels (Easy: 1–10, Medium: 1–50, Hard: 1–100)
- [ ] Add a countdown timer ⏱️
- [ ] Add sound effects for win/lose
- [ ] Add animations on wrong guesses
- [ ] Mobile responsive design
- [ ] Persistent highscore using `localStorage`

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Neemayg**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Neemayg)

---

<div align="center">

⭐ **If you liked this project, give it a star!** ⭐

Made with ❤️ and JavaScript

</div>

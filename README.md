# 🫧 Bubble Math Game - Cognitive Assessment

A web-based Bubble Math Game that replicates the **Accenture Cognitive Assessment – Bubble Math Game (2026 pattern)**.

![Bubble Math Game](https://img.shields.io/badge/Game-Bubble%20Math-00d4ff)
![Version](https://img.shields.io/badge/Version-1.0-green)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🎯 Overview

Users must mentally solve arithmetic expressions displayed inside floating bubbles and select them in the correct numerical order (lowest to highest) within a strict 15-second time limit per question.

## ✨ Features

### Core Gameplay
- **25 Questions** - Complete all rounds for a full assessment
- **15-Second Timer** - Strict time limit per question with visual countdown
- **Mental Math** - Calculate expressions involving +, −, ×, ÷
- **Order Selection** - Click bubbles from lowest to highest value

### Expression Types
- ✅ Integers (e.g., `12 + 8`)
- ✅ Decimals (e.g., `3.5 × 2`)
- ✅ Fractions (e.g., `3/4 + 1/2`)
- ✅ Mixed operations

### Adaptive Difficulty
The game silently adapts to your performance:
- **Bubble Count**: 3 → 6 bubbles
- **Number Ranges**: Increases with skill
- **Decimal Precision**: 0 → 2 decimal places
- **Fraction Complexity**: Simple → Mixed fractions
- **Operator Mixing**: Combined operations

### Visual Feedback
- 🟢 **Green** - Correct selection
- 🔴 **Red** - Incorrect selection
- Smooth floating bubble animations
- Professional assessment-style UI

### Performance Tracking
- Question progress (1-25)
- Correct/incorrect selections
- Accuracy percentage
- Average response time
- Final score summary

## 🚀 How to Play

1. **Open** `index.html` in any modern web browser
2. **Click** "Start Game" to begin
3. **Calculate** each expression mentally
4. **Click** bubbles in order from **lowest to highest** value
5. **Complete** all 25 questions before time runs out

## 🛠️ Technical Details

- **Pure Vanilla JavaScript** - No external libraries
- **Single HTML File** - Easy to deploy
- **Responsive Design** - Desktop-first with mobile support
- **No Repeating Expressions** - Unique questions throughout

## 📁 File Structure

```
Balloon-game-/
├── index.html      # Complete game (HTML + CSS + JS)
├── README.md       # Documentation
└── LICENSE         # MIT License
```

## 🎮 Quick Start

```bash
# Clone the repository
git clone https://github.com/PranjalTripatHI07/Balloon-game-.git

# Open in browser
open index.html
# or
xdg-open index.html  # Linux
start index.html     # Windows
```

## 📊 Scoring System

| Component | Points |
|-----------|--------|
| Correct Selection | 10 pts each |
| Speed Bonus | Up to 30 pts |
| Accuracy Bonus | Up to 50 pts |

## 🧠 Game Rules

1. Each question displays 3-6 floating bubbles
2. Each bubble contains an arithmetic expression
3. Mentally calculate each expression's value
4. Click bubbles in order from **lowest to highest**
5. Green = correct, Red = incorrect
6. Complete before the 15-second timer expires

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built for cognitive assessment practice** 🧠

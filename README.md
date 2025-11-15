# 🎮 Math Quest Adventure

An interactive, educational math game built with vanilla HTML, CSS, and JavaScript. Embark on an epic mathematical journey where you solve arithmetic problems, level up, and challenge yourself across multiple difficulty levels!

![Math Quest Adventure](https://img.shields.io/badge/Game-Math%20Quest%20Adventure-purple?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Table of Contents

- [Features](#-features)
- [Gameplay](#-gameplay)
- [Getting Started](#-getting-started)
- [How to Play](#-how-to-play)
- [Game Mechanics](#-game-mechanics)
- [Difficulty Levels](#-difficulty-levels)
- [Scoring System](#-scoring-system)
- [Keyboard Controls](#-keyboard-controls)
- [Technical Details](#-technical-details)
- [Browser Compatibility](#-browser-compatibility)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

### Core Features
- 🎯 **Multiple Difficulty Levels**: Choose from Easy, Medium, or Hard difficulty
- 📈 **Progressive Difficulty**: Questions get harder as you level up
- ❤️ **Lives System**: Start with 3 lives - lose one for each incorrect answer
- 🏆 **Scoring System**: Earn points based on your level and performance
- 📊 **Progress Tracking**: Visual progress bar shows your advancement through each level
- 🎨 **Beautiful UI**: Modern gradient design with glassmorphism effects
- 📱 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- ⌨️ **Keyboard Support**: Use number keys 1-4 to select answers quickly
- 🎭 **Visual Feedback**: Animated responses for correct and incorrect answers
- 🔄 **Level Progression**: Advance to new levels every 5 questions

### Educational Features
- ➕ **Addition**: Practice basic addition skills
- ➖ **Subtraction**: Master subtraction problems
- ✖️ **Multiplication**: Challenge yourself with multiplication tables
- ➗ **Division**: Test your division abilities (Hard mode only)
- 🎓 **Adaptive Learning**: Difficulty scales with your progress

## 🎮 Gameplay

### Start Screen
- Select your preferred difficulty level (Easy, Medium, or Hard)
- Click "🚀 Begin Adventure" to start your quest

### Game Screen
- View your current level, score, and remaining lives
- Answer math questions by clicking on one of four answer options
- Watch the progress bar fill as you complete questions
- Receive instant feedback on your answers

### Game Over Screen
- See your final score and performance rating
- View statistics about your gameplay session
- Start a new adventure anytime

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required!

### Installation

1. **Clone the repository** (or download the files):
   ```bash
   git clone https://github.com/yourusername/math-quest-adventure-.git
   cd math-quest-adventure-
   ```

2. **Open the game**:
   - Simply open `index.html` in your web browser
   - Or use a local web server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```
   - Navigate to `http://localhost:8000` in your browser

3. **Start playing**:
   - No installation or setup required!
   - The game runs entirely in your browser

## 🎯 How to Play

1. **Choose Difficulty**: Select Easy, Medium, or Hard based on your skill level
2. **Start Game**: Click "Begin Adventure" to start
3. **Answer Questions**: 
   - Read the math problem carefully
   - Click on the correct answer from the four options
   - Or use keyboard keys 1-4 to select answers
4. **Progress**: 
   - Correct answers increase your score
   - Wrong answers cost you a life
   - Complete 5 questions to level up
5. **Survive**: Keep answering correctly to maintain your lives and reach higher levels!

## 🎲 Game Mechanics

### Question Generation
- Questions are randomly generated based on your selected difficulty
- Each question has 4 answer options, with only one correct answer
- Wrong answers are strategically placed to challenge your understanding

### Level System
- **Questions per Level**: 5 questions
- **Level Progression**: Automatically advance after completing 5 questions
- **Difficulty Scaling**: Numbers get larger as you progress through levels
- **Life Restoration**: Gain one life back every 3 levels (if you have less than 3)

### Lives System
- Start with **3 lives** (❤️❤️❤️)
- Lose **1 life** for each incorrect answer
- Game ends when you reach **0 lives**
- Lives are displayed as hearts (❤️ = active, 🖤 = lost)

## 📊 Difficulty Levels

### 🟢 Easy Mode
- **Number Range**: 1-10
- **Operations**: Addition (+), Subtraction (-)
- **Best For**: Beginners, young learners, quick practice
- **Example**: `7 + 3 = ?` or `9 - 4 = ?`

### 🟡 Medium Mode
- **Number Range**: 1-50
- **Operations**: Addition (+), Subtraction (-), Multiplication (×)
- **Best For**: Intermediate players, students learning multiplication
- **Example**: `23 + 15 = ?` or `6 × 7 = ?`

### 🔴 Hard Mode
- **Number Range**: 1-100
- **Operations**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Best For**: Advanced players, mental math practice
- **Example**: `67 + 23 = ?` or `84 ÷ 7 = ?`

## 🏆 Scoring System

### Base Scoring
- **Correct Answer**: `10 × current level` points
  - Level 1: 10 points per correct answer
  - Level 2: 20 points per correct answer
  - Level 3: 30 points per correct answer
  - And so on...

### Bonus Points
- **Perfect Health Bonus**: +5 points when you answer correctly with all 3 lives intact

### Performance Ratings
Based on your final score:
- **🏆 Mathematical Genius**: 500+ points
- **🥇 Math Champion**: 300-499 points
- **🥈 Great Job**: 200-299 points
- **🥉 Nice Work**: 100-199 points
- **💪 Good Effort**: Below 100 points

## ⌨️ Keyboard Controls

- **1, 2, 3, 4**: Select answer options (1 = first button, 2 = second button, etc.)
- Works only when the game screen is active and a question is displayed

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Structure and semantic markup
- **CSS3**: Styling with modern features:
  - CSS Grid and Flexbox for layout
  - CSS Animations and Transitions
  - Gradient backgrounds
  - Backdrop filters (glassmorphism)
  - Media queries for responsiveness
- **Vanilla JavaScript**: Game logic and interactivity
  - No external dependencies
  - ES6+ features
  - Event-driven architecture

### File Structure
```
math-quest-adventure-/
│
├── index.html          # Main game file (HTML, CSS, and JavaScript)
└── README.md           # This file
```

### Code Architecture
- **Single-file design**: All code in one HTML file for easy deployment
- **Modular functions**: Organized JavaScript functions for each game feature
- **Event-driven**: Uses DOM events for user interactions
- **State management**: Tracks game state with variables

### Performance
- Lightweight: No external libraries or frameworks
- Fast loading: Single HTML file
- Smooth animations: CSS-based animations for better performance
- Responsive: Works on all screen sizes

## 🌐 Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

**Note**: Some advanced CSS features (like `backdrop-filter`) may not work in older browsers, but the game will still function.

## 🚀 Future Enhancements

Potential features for future versions:
- [ ] Timer mode (answer questions within a time limit)
- [ ] Leaderboard system (local storage)
- [ ] Achievement badges
- [ ] Sound effects and background music
- [ ] More operation types (exponents, square roots)
- [ ] Custom difficulty settings
- [ ] Statistics tracking (accuracy rate, average time)
- [ ] Multiplayer mode
- [ ] Daily challenges
- [ ] Practice mode (unlimited lives)

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Report Bugs**: Found a bug? Open an issue describing the problem
2. **Suggest Features**: Have an idea? Share it in the issues section
3. **Submit Pull Requests**: 
   - Fork the repository
   - Create a feature branch
   - Make your changes
   - Submit a pull request

### Development Guidelines
- Follow existing code style
- Test on multiple browsers
- Ensure mobile responsiveness
- Keep the single-file structure (or document why you're changing it)

## 📝 License

This project is open source and available under the [MIT License](LICENSE) (or your preferred license).

## 🙏 Acknowledgments

- Inspired by educational games that make learning fun
- Built with modern web technologies
- Designed for accessibility and user experience

## 📧 Contact

Have questions or suggestions? Feel free to:
- Open an issue on GitHub
- Contact the maintainer

---

**Enjoy your mathematical adventure! 🎮✨**

*Happy calculating!*

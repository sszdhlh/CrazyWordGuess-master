# Crazy Word Guess

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android%20%7C%20Web-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A multi-player party game app built with React Native and Expo, supporting word guessing games with various themes and difficulty levels.

<p align="center">
  <img src="screenshots/welcome_screen.png" alt="Game Preview" width="300"/>
</p>

## 📖 Project Introduction

"Crazy Word Guess" is an interactive game ideal for team building and social gatherings. Players take turns being the guesser, while others describe the words on the screen using verbal or physical cues. The guesser needs to figure out the correct answer based on these hints. The game combines fun and challenge, providing an immersive multiplayer experience.

## ✨ Core Features

- **Rich Word Library** - 400+ carefully selected words covering 8 major thematic areas
- **Multiple Difficulty Levels** - Supports basic, advanced, and random difficulty selection
- **Customizable Duration** - Choose from 30/60/90 second game lengths
- **Game Controls** - Support for pause/resume, ability to end mid-game to view results
- **Score Statistics** - Detailed recording of correct/incorrect word lists
- **Ranking System** - Support for local and online leaderboards, recording personal best scores
- **Bilingual Support** - Toggle between Chinese and English interfaces

## 🛠️ Technical Architecture

- **Frontend Framework**: React Native
- **Development Tools**: Expo
- **Route Navigation**: React Navigation
- **Development Language**: TypeScript
- **State Management**: React Hooks
- **Data Storage**: Local Storage + Simulated Online API

## 📱 App Screenshots

Here are the main interface screenshots of the game:

<p align="center">
  <img src="screenshots/welcome_screen.png" alt="Welcome Screen" width="200"/>
  <img src="screenshots/settings_screen.png" alt="Settings Screen" width="200"/>
  <img src="screenshots/gameplay_screen.png" alt="Gameplay Screen" width="200"/>
</p>

<p align="center">
  <img src="screenshots/results_screen.png" alt="Results Screen" width="200"/>
  <img src="screenshots/rules_screen.png" alt="Rules Screen" width="200"/>
</p>

<p align="center">
  <img src="screenshots/leaderboard_local_screen.png" alt="Local Leaderboard" width="200"/>
  <img src="screenshots/leaderboard_global_screen.png" alt="Global Leaderboard" width="200"/>
</p>

### Main Game Interfaces

Brief introduction to each page:

- **Welcome Screen**: Displays the game title and provides buttons for "Start Game", "Game Rules", and "View Leaderboard"
- **Settings Screen**: Options for game duration (30/60/90 seconds), word library difficulty (random/basic/advanced) and word library theme
- **Gameplay Screen**: Displays the current word, timer, score, and "Correct" and "Skip" buttons
- **Results Screen**: Shows the final score, lists of correct/incorrect words, and option to save scores
- **Rules Screen**: Detailed explanation of game rules and gameplay
- **Leaderboard Screen**: View local and global high score rankings

## 🚀 Quick Start

### Prerequisites

- Node.js (v12.0+)
- npm or yarn
- Expo CLI

### Installation Steps

```bash
# Clone repository
git clone https://github.com/yourusername/CrazyWordGuess.git

# Enter project directory
cd CrazyWordGuess

# Install dependencies
npm install
# or
yarn install

# Start development server
npm start
# or
expo start
```

### Build and Deploy

```bash
# Web version build
npm run web-build

# iOS build
expo build:ios

# Android build
expo build:android
```

## 📋 Game Instructions

1. **Game Settings**:
   - Select game duration (30/60/90 seconds)
   - Select word library difficulty (random/basic/advanced)
   - Select word library theme (all/daily/technology/literature, etc.)

2. **Game Flow**:
   - One player acts as the guesser, holding the device but not looking at the screen
   - Other players see the word on the screen and help the guesser through description
   - Click "✓" for correct guesses, "✗" for incorrect
   - Game ends when time runs out or through the pause menu

3. **Result Record**:
   - View the score for the current game
   - Browse lists of correct and incorrect words
   - Enter a name to save your score to the leaderboard
   - View historical best scores and global rankings

## 🔄 Recent Updates

### v1.0.0 (2023-05-20)

- **Game Control Upgrade**:
  - Added game pause/resume function
  - Support for ending mid-game and saving scores
  - Optimized navigation stack, fixed return logic issues

- **Leaderboard System**:
  - Implemented player name registration and score saving
  - Added local/online leaderboard switching
  - Intelligent sorting and display by score

- **Content Expansion**:
  - Expanded word library to 400+
  - Added popular terms and internet meme library
  - Implemented theme-based word library filtering
  
- **Language Support**:
  - Added English language support
  - Language switching feature on the welcome screen
  - Saved language preference between sessions

## 🤝 Contribution

Welcome to participate in the development and improvement of this project!

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Create a Pull Request

## 📝 Development Plan

- [ ] Add multiplayer online battle function
- [ ] Implement custom word library creation and sharing
- [ ] Add sound effects and animations
- [ ] Support dark mode
- [ ] Add achievement system

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## 👥 Team Members

- **Developer** - [Yixin(Charles) Zhang](https://github.com/sszdhlh)
- **Designer** - Claude & Yixin(Charles) Zhang

## 🙏 Acknowledgements

- Thanks to all users who provided feedback and suggestions
- [React Native Community](https://reactnative.dev/)
- [Expo Team](https://expo.dev/)

---

<p align="center">
  Made with ❤️ for word game enthusiasts
</p>

# 🎨 Color Guesser Game

A fun and challenging web-based color guessing game inspired by GeoGuessr! Test your color perception skills by clicking on a color wheel to match target colors. Perfect for playing with friends and challenging your visual accuracy.

## 🎮 How to Play

1. **Look at the target color** displayed on the left
2. **Click on the color wheel** to pick the color you think matches
3. **Submit your guess** to see how accurate you are
4. **Get scored** based on how close your guess is (0-100% accuracy)
5. **Share your best score** and challenge friends!

## 🌟 Features

- **Interactive Color Wheel**: Click anywhere on the HSL color wheel to make your guess
- **Accuracy-Based Scoring**: Get percentage scores based on RGB color distance
- **Best Score Tracking**: Your highest accuracy is saved locally
- **Visual Feedback**: Animated accuracy circles with color-coded performance
- **Responsive Design**: Play on desktop, tablet, or mobile
- **Social Sharing**: Share your best accuracy score with friends
- **Keyboard Shortcuts**: 
  - Press `N` for new game
  - Press `S` to share score
  - Press `Enter` or `Space` to submit guess/next round

## 🏆 Scoring System

- **Accuracy Calculation**: Based on Euclidean distance in RGB color space
- **95%+ Accuracy**: Perfect! Amazing color perception 🎯
- **80-94% Accuracy**: Excellent guess! Very close 🎉
- **60-79% Accuracy**: Good job! Getting warmer 👍
- **Below 60%**: Keep practicing! 💪

## 🚀 Play Online

Visit the live game at: `https://yourusername.github.io/color-guesser/`

*(Replace `yourusername` with your actual GitHub username after deployment)*

## 🛠️ Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/color-guesser.git
   cd color-guesser
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## 📱 GitHub Pages Deployment

1. Push your code to a GitHub repository
2. Go to your repository settings
3. Scroll down to "Pages" section
4. Select "Deploy from a branch" 
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"
7. Your game will be available at `https://yourusername.github.io/repository-name/`

## 🎯 Game Rules

- **Target Color**: A random RGB color is generated each round
- **Color Wheel**: Click anywhere on the HSL color wheel to make your guess
- **Accuracy Scoring**: Your score is based on how close your RGB guess is to the target
- **Best Score**: Your highest accuracy percentage is saved and displayed
- **Unlimited Rounds**: Keep playing to improve your color perception skills
- **Challenge Friends**: Share your best accuracy score to see who has better color vision!

## 🎨 Technical Details

- **Built with**: HTML5 Canvas, CSS3, Vanilla JavaScript
- **Color Space**: HSL color wheel with RGB distance calculations
- **No dependencies**: Runs entirely in the browser
- **Mobile-friendly**: Touch-optimized responsive design
- **Modern browsers**: Supports ES6+ features and Canvas API

## 🤝 Contributing

Feel free to contribute to make the game even better! Some ideas:

- Add difficulty levels
- Implement high score leaderboard
- Add sound effects
- Create different game modes (HSL, HEX, etc.)
- Add animations and transitions

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Share & Enjoy

Have fun playing and don't forget to challenge your friends! Share your high scores and see who has the best color perception skills.

---

Made with ❤️ for color enthusiasts everywhere!

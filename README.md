# chesssss
# Chess Master - Online Chess Platform

<div align="center">

![Chess Master](https://img.shields.io/badge/Chess-Master-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

A modern, responsive online chess platform with AI and multiplayer capabilities.

[Features](#features) • [Installation](#installation) • [Usage](#usage) • [Game Modes](#game-modes) • [Screenshots](#screenshots)

</div>

## 🚀 Overview

Chess Master is a comprehensive web-based chess platform that offers both single-player against AI and real-time multiplayer gameplay. Built with modern web technologies, it provides an immersive chess experience with beautiful visuals and smooth gameplay.

## ✨ Features

### 🎮 Gameplay
- **🤖 AI Challenge Mode** - Play against intelligent computer opponent
- **👥 Multiplayer Mode** - Real-time chess with friends
- **♟️ Complete Chess Rules** - Full move validation and game logic
- **⏰ Game Timer** - Track game duration for both players
- **📊 Move History** - Complete record of all moves made

### 🎨 User Experience
- **📱 Responsive Design** - Works seamlessly on desktop and mobile
- **🎯 Interactive Board** - Visual move hints and piece selection
- **🌈 Modern UI** - Beautiful gradients and animations
- **🔊 Visual Feedback** - Hover effects and transition animations
- **🎪 Chess Notation** - Professional move recording

### 🛠️ Technical Features
- **Pure Client-Side** - No server requirements for basic gameplay
- **Cross-Browser** - Compatible with all modern browsers
- **Fast Loading** - Optimized assets and efficient code
- **Accessible** - Keyboard and touch-friendly interface

## 📦 Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic web server for local hosting (optional)

### Quick Start
1. **Clone or Download the Project**
   ```bash
   git clone <repository-url>
   ```
   Or download the ZIP file and extract it

2. **Project Structure**
   ```
   chess-master/
   ├── index.html          # Main homepage
   ├── AIchess.html        # Single player vs AI
   ├── Multiplayer.html    # Multiplayer game
   ├── style.css           # Main stylesheet
   ├── stylem.css          # Multiplayer styles
   ├── scriptm.js          # Multiplayer game logic
   ├── images/             # Assets folder
   │   ├── logo.png
   │   ├── cb.jpeg
   │   ├── multi.jpg
   │   ├── ai.jpg
   │   └── chess-bg.jpg
   ```

3. **Run the Application**
   - **Option 1**: Open `index.html` directly in your browser
   - **Option 2**: Serve using a local web server
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

4. **Access the Game**
   - Open your browser and navigate to:
     - Local: `http://localhost:8000`
     - Or directly open `index.html`

## 🎯 Usage

### Starting a Game
1. **Open the Application** - Launch `index.html` in your web browser
2. **Choose Game Mode**:
   - **Single Player**: Click "Single Player" card or "Play" button
   - **Multiplayer**: Click "Multiplayer" card

### Game Controls
- **Piece Selection**: Click on any of your pieces
- **Move Making**: Click on highlighted valid squares
- **Game Info**: View turn indicator and move history
- **Restart**: Refresh the page or use restart button

### AI Chess Features
- **Intelligent AI** - Adaptive difficulty based on your moves
- **Move Validation** - Prevents illegal moves
- **Check Detection** - Visual and textual check indicators
- **Game Analysis** - Move-by-move recording

## 🎮 Game Modes

### 🤖 Single Player vs AI
- Challenge computer-controlled opponent
- AI makes strategic moves in response to your gameplay
- Perfect for practice and skill development
- No internet required after loading

### 👥 Multiplayer
- Real-time two-player chess
- Turn-based gameplay with visual indicators
- Local multiplayer on the same device
- Complete move validation and game state management

## 🎨 Customization

### Changing Colors
Modify `style.css` to customize the appearance:

```css
:root {
  --primary-color: #ff6b6b;
  --secondary-color: #1a1a2e;
  --accent-color: #ee5a24;
  --board-light: #f0d9b5;
  --board-dark: #b58863;
}
```

### Adding Pieces
Replace piece images in `images/` folder:
- Use PNG format with transparent background
- Recommended size: 40x40 pixels
- Follow naming convention: `[color]_[piece].png`

## 📱 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 60+ | ✅ Full |
| Firefox | 55+ | ✅ Full |
| Safari | 12+ | ✅ Full |
| Edge | 79+ | ✅ Full |
| Mobile Browsers | Recent | ✅ Full |

## 🐛 Troubleshooting

### Common Issues

1. **Pieces Not Loading**
   - Check if images are in correct `images/` folder
   - Verify image file names match code references

2. **Moves Not Working**
   - Ensure JavaScript is enabled in browser
   - Check browser console for errors (F12)

3. **Layout Issues**
   - Clear browser cache (Ctrl+F5)
   - Check CSS file loading

4. **AI Not Making Moves**
   - Wait for AI processing (1-3 seconds)
   - Check if it's AI's turn

### Debug Mode
Open browser console (F12) to see:
- Game state changes
- Move validations
- AI decision process

## 🚀 Future Enhancements

- [ ] Online multiplayer with WebSockets
- [ ] User accounts and Elo rating system
- [ ] Game replay and analysis
- [ ] Chess puzzles and tutorials
- [ ] Tournament mode
- [ ] Mobile app version
- [ ] Voice commands
- [ ] Advanced AI difficulty levels

## 👥 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Setup
```bash
# Clone repository
git clone https://github.com/yourusername/chess-master.git

# Navigate to project
cd chess-master

# Start development server
python -m http.server 8000
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Chess piece designs and Unicode symbols
- Stockfish AI inspiration for move generation
- Chess.com for UI/UX inspiration
- Contributors and testers

## 📞 Support

If you encounter any issues or have questions:

1. **Check Documentation** - Review this README
2. **Browser Console** - Look for error messages (F12)
3. **GitHub Issues** - Report bugs and request features
4. **Email Support** - Contact development team

## 🏆 Credits

**Developed by:** Aswini Devi Medisetti  
**Design:** Modern Chess UI/UX  
**AI Logic:** Custom chess engine  
**Multiplayer:** Real-time game synchronization  

---

<div align="center">

**Enjoy playing chess! ♟️**

*"The chessboard is the world, the pieces are the phenomena of the universe."* - Thomas Huxley

[⬆ Back to Top](#chess-master---online-chess-platform)

</div>

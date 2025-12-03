# ⚡ Retro Blaster 90 ⚡

A nostalgic web-based space shooter game that brings back the glory days of 90s arcade gaming! Defend Earth from waves of pixelated alien invaders in this browser-based tribute to classic arcade shooters.

![Game Type](https://img.shields.io/badge/Type-Space%20Shooter-ff00ff)
![Platform](https://img.shields.io/badge/Platform-Web%20Browser-00ff41)
![Era](https://img.shields.io/badge/Era-90s%20Nostalgia-00ffff)

## 🎮 Game Features

- **Pure 90s Aesthetic**: Pixel art graphics, neon colors, and retro scanline effects
- **Classic Arcade Gameplay**: Space Invaders-inspired mechanics with modern polish
- **Progressive Difficulty**: Enemies get faster and more aggressive with each level
- **Score System**: Compete against yourself with persistent high score tracking
- **Sound Effects**: Authentic retro beeps and boops using Web Audio API
- **Responsive Design**: Plays on desktop, tablet, and mobile devices
- **No Installation Required**: Runs directly in any modern web browser
- **Keyboard Controls**: Classic arcade-style keyboard controls

## 🚀 How to Play

### Starting the Game
1. Open `index.html` in your web browser
2. Click the **"START GAME"** button
3. Get ready to blast some aliens!

### Controls
- **← → Arrow Keys**: Move your spaceship left and right
- **SPACE**: Fire your laser cannon
- **P**: Pause/Resume the game

### Gameplay
- Destroy all alien invaders before they reach your position
- Avoid enemy fire by moving left and right
- Each enemy destroyed adds to your score (higher rows = more points)
- Complete waves to advance to harder levels
- You have 3 lives - don't waste them!

### Scoring
- **Top Row Enemies** (Purple): 10 points each
- **Middle Row Enemies** (Pink): 20 points each
- **Bottom Row Enemies** (Orange): 30 points each

## 🖥️ How to Run Locally

### Option 1: Direct File Opening
1. Download or clone this repository
2. Navigate to the project folder
3. Double-click `index.html` to open in your default browser

### Option 2: Using Python's HTTP Server
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```
Then navigate to `http://localhost:8000` in your browser

### Option 3: Using Node.js HTTP Server
```bash
# Install http-server globally (one time)
npm install -g http-server

# Run server
http-server -p 8000
```
Then navigate to `http://localhost:8000` in your browser

### Option 4: Using VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🎨 90s Design Elements

This game captures the essence of 90s gaming through:

- **Pixel-Perfect Graphics**: Crisp, blocky sprites reminiscent of 8-bit and 16-bit era games
- **Neon Color Palette**: Bright cyan, magenta, and green colors on dark backgrounds
- **CRT Scanlines**: Subtle horizontal lines simulating old CRT monitor displays
- **Glowing Text Effects**: Neon glow effects on titles and UI elements
- **Chiptune-Style Audio**: Simple oscillator-based sound effects
- **Arcade Cabinet Aesthetic**: High score tracking and coin-op inspired UI
- **Retro Typography**: Monospace fonts that evoke terminal screens and early computer displays

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas**: For game rendering and graphics
- **Vanilla JavaScript**: Pure JS with no external dependencies
- **Web Audio API**: For generating retro sound effects
- **CSS3**: For styling and visual effects
- **LocalStorage API**: For persistent high score tracking

### Browser Compatibility
Works on all modern browsers that support:
- HTML5 Canvas
- Web Audio API
- ES6 JavaScript
- CSS3

Tested on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### File Structure
```
retro-game-test/
├── index.html          # Complete game (HTML, CSS, and JavaScript)
└── README.md           # This file
```

## 🎯 Game Mechanics

### Player
- Moves horizontally along the bottom of the screen
- Fires lasers upward
- Has 3 lives (indicated by hearts in the UI)

### Enemies
- Move in formation across the screen
- Drop down when reaching screen edges
- Randomly fire bullets at the player
- Come in 3 types with different point values

### Difficulty Progression
- **Level 1**: Slow-moving enemies, low fire rate
- **Level 2+**: Speed increases by 0.5 per level
- **Fire Rate**: Enemy shooting frequency increases each level
- **No Limit**: Keep playing to see how far you can go!

## 🏆 Tips & Strategies

1. **Stay Mobile**: Keep moving to avoid enemy fire
2. **Target Bottom Rows First**: They're worth more points and pose the most immediate threat
3. **Time Your Shots**: You can only have a limited number of bullets on screen
4. **Use the Full Width**: Don't stay in the center - use the whole screen
5. **Watch Enemy Patterns**: Enemies become predictable after observation

## 💾 High Score System

Your highest score is automatically saved in your browser's local storage. Try to beat your personal best! The high score persists even after closing the browser.

## 🎵 Sound Controls

The game includes retro sound effects for:
- Laser fire
- Enemy explosions
- Game over
- Level completion

Toggle sound on/off using the **"SOUND"** button below the game canvas.

## 🐛 Known Issues

None at this time! If you encounter any bugs, please report them.

## 📝 Credits

**Game Design & Development**: Created as a tribute to classic 90s arcade games

**Inspired By**:
- Space Invaders (1978) - Taito
- Galaga (1981) - Namco
- Galaxian (1979) - Namco

**Special Thanks**: To all the arcade game developers of the 80s and 90s who created the games that defined a generation.

## 📜 Version History

### Version 1.0 (2025)
- Initial release
- Full game with progressive difficulty
- Sound effects and visual effects
- High score tracking
- Responsive design

## 🎮 Future Enhancements

Potential features for future versions:
- Power-ups (shield, rapid fire, multi-shot)
- Boss battles every 5 levels
- Additional enemy types
- Particle effects and more explosions
- Background music tracks
- Mobile touch controls
- Multiplayer mode

## 🤝 Contributing

This is a standalone nostalgic game project. Feel free to fork and create your own retro gaming experiences!

## 🌟 Enjoy!

Relive the golden age of arcade gaming! Can you beat the high score? How many levels can you conquer? 

**Ready Player One?** Click START GAME and show those aliens who's boss! 👾

---

*Made with 💚 for 90s gaming nostalgia*
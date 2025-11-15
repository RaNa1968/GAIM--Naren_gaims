# 🎮 narengaims - Classic Games Collection

Welcome to **narengaims**, your ultimate destination for classic arcade games! Play online, install as apps, or download to play offline anytime.

---

## 📋 Table of Contents

1. [Getting Started](#getting-started)
2. [Snake (Single Player)](#snake-single-player)
3. [Snake (2 Player Battle)](#snake-2-player-battle)
4. [Pac-Man](#pac-man)
5. [Installation Guide](#installation-guide)
6. [Technical Information](#technical-information)
7. [Troubleshooting](#troubleshooting)

---

## 🚀 Getting Started

### **Access the Games**

1. **Online**: Visit the narengaims website
2. **Login/Register**: Create an account or continue as guest
3. **Choose Your Game**: Select from Snake, 2 Player Snake, or Pac-Man
4. **Play Instantly**: No downloads required!

### **System Requirements**

- ✅ Modern web browser (Chrome, Firefox, Edge, Safari)
- ✅ JavaScript enabled (default)
- ✅ Internet connection (only for first visit if using PWA)
- ✅ No additional software needed!

---

## 🐍 Snake (Single Player)

### **Game Overview**
Classic Snake game where you control a growing serpent eating food while avoiding walls and your own tail.

### **Objective**
- Eat as much food as possible to grow your snake
- Achieve the highest score
- Survive as long as possible

### **Controls**

| Action | Keyboard |
|--------|----------|
| Move Up | ↑ Arrow or W |
| Move Down | ↓ Arrow or S |
| Move Left | ← Arrow or A |
| Move Right | → Arrow or D |
| Restart (after game over) | SPACE |

### **Rules**

1. **Movement**
   - Snake moves continuously in the current direction
   - Cannot reverse direction (can't go directly backward)
   - Snake wraps around screen edges (no tunneling)

2. **Eating Food**
   - Red pulsing circle = food
   - Eating food increases score by 10 points
   - Snake grows by 1 segment
   - New food appears randomly

3. **Speed Progression**
   - Speed increases by 1.25x every 10 points
   - Score 10: 1.25x speed
   - Score 20: 1.56x speed
   - Score 30: 1.95x speed
   - And so on...

4. **Game Over Conditions**
   - Hit the wall (edge of playing field)
   - Collide with your own body
   - Score is saved if it's a personal best

### **Scoring**
- Each food eaten: **10 points**
- Personal best is tracked and saved
- Total games played counter

### **Tips & Strategies**
- 🎯 Plan your path ahead
- 🔄 Use the middle of the field to maximize movement options
- ⚡ As speed increases, use wider turns
- 🎮 Practice makes perfect - learn speed patterns

---

## 🐍🐍 Snake (2 Player Battle)

### **Game Overview**
Battle mode where two players compete head-to-head on the same keyboard!

### **Objective**
- **Win Condition 1**: First player to reach 10 points
- **Win Condition 2**: Bite opponent's tail for instant victory
- **Win Condition 3**: Opponent crashes (wall or self-collision)

### **Controls**

| Player | Up | Down | Left | Right |
|--------|-----|------|------|-------|
| Player 1 (Green) | W | S | A | D |
| Player 2 (Blue) | ↑ | ↓ | ← | → |

### **Setup Phase**

Before each game:
1. **Choose Snake Skins**
   - Player 1: 6 green-based skins (Classic, Neon, Dark, Fire, Gold, Purple)
   - Player 2: 6 blue-based skins (Classic, Ocean, Deep, Cyan, Pink, Lime)
2. **Click Start Game** to begin

### **Rules**

1. **Starting Positions**
   - Player 1 starts on the left side
   - Player 2 starts on the right side
   - Both start moving toward center

2. **Food Competition**
   - Only ONE food on screen at a time
   - Either player can eat it
   - First to reach gets the point
   - Each food = 1 point

3. **Combat Rules**
   - Biting opponent's body = instant win
   - Head-on collision = longer snake wins (or tie)
   - Cannot bite opponent's head directly

4. **Win Conditions** (in order of priority)
   1. Reach 10 points first
   2. Opponent hits wall
   3. Opponent hits their own body
   4. Successfully bite opponent's body
   5. Head-on collision (longer snake wins)

5. **Standard Rules Apply**
   - Can't reverse direction
   - Must avoid walls
   - Can't hit own body
   - Snake grows when eating food

### **Scoring**
- Each food: **1 point** toward victory
- First to 10 points wins
- Win/loss records saved per player
- Total matches played tracked

### **Strategies**
- 🎯 Control the center for better food access
- 🛡️ Protect your body from opponent
- ⚔️ Trap opponent near walls
- 🏃 Sometimes avoiding food is strategic
- 👀 Watch opponent's length - head-ons favor longer snakes
- 🎮 Communication is key in close quarters!

### **Fair Play Tips**
- Take turns starting on different sides
- Agree on skin choices before starting
- Best of 3 or best of 5 matches recommended

---

## 👻 Pac-Man

### **Game Overview**
Navigate the classic maze as Pac-Man, eating dots while avoiding (or chasing!) four colorful ghosts.

### **Objective**
- Eat all dots and power pellets in the maze
- Avoid ghosts (unless powered up)
- Complete levels to increase difficulty
- Achieve the highest score

### **Controls**

| Action | Keyboard |
|--------|----------|
| Move Up | ↑ Arrow or W |
| Move Down | ↓ Arrow or S |
| Move Left | ← Arrow or A |
| Move Right | → Arrow or D |
| Restart (after game over) | SPACE |

### **Game Elements**

#### **Pac-Man (You)**
- Yellow circle with chomping mouth
- Moves continuously in chosen direction
- Can change direction at any time
- Slows briefly when turning

#### **Ghosts (Enemies)**
- **Blinky (Red)**: Chases Pac-Man directly
- **Pinky (Pink)**: Tries to ambush ahead
- **Inky (Cyan)**: Unpredictable movement
- **Clyde (Orange)**: Alternates chase and scatter

#### **Collectibles**
- **Small Dots**: 10 points each
- **Power Pellets** (large pulsing dots): 50 points each
  - Turn ghosts blue for ~10 seconds
  - Allows you to eat ghosts

### **Rules**

1. **Movement**
   - Pac-Man moves continuously
   - Can only turn at intersections
   - Wraps around left/right tunnels
   - Can queue next direction

2. **Eating Dots**
   - Collect all dots to complete level
   - Small dots: 10 points
   - Power pellets: 50 points
   - Level advances when maze is cleared

3. **Ghost Interactions**

   **Normal Mode:**
   - Touching ghost = lose 1 life
   - Ghosts chase you
   - AI follows different patterns per ghost

   **Frightened Mode (after power pellet):**
   - Ghosts turn blue
   - You can eat ghosts: 200 points each
   - Ghosts flash white when effect ending
   - Eaten ghosts return to center

4. **Lives**
   - Start with 3 lives (yellow circles)
   - Lose life when caught by ghost
   - Positions reset after losing life
   - Game over when all lives lost

5. **Level Progression**
   - Complete maze = advance to next level
   - Increased difficulty each level
   - Score carries over
   - Ghost AI becomes more aggressive

### **Scoring System**

| Item | Points |
|------|--------|
| Small Dot | 10 |
| Power Pellet | 50 |
| Ghost (1st in fright mode) | 200 |
| Ghost (2nd in fright mode) | 200 |
| Ghost (3rd in fright mode) | 200 |
| Ghost (4th in fright mode) | 200 |

### **Power Pellet Strategy**
- Save pellets for emergencies
- Use to clear crowded areas
- Chase all 4 ghosts for 800 points
- Effect lasts ~10 seconds
- Plan escape route before effect ends

### **Advanced Strategies**
- 🎯 **Corner Cutting**: Turn early at intersections
- 🔄 **Loop Patterns**: Use tunnels to lose ghosts
- 👻 **Ghost Behavior**: Learn each ghost's pattern
- ⚡ **Power Timing**: Save pellets for critical moments
- 🏃 **Speed Control**: Slow down by turning
- 🎮 **Safe Zones**: Know where to hide

### **Ghost AI Patterns**

**Blinky (Red)**
- Most aggressive chaser
- Directly follows your position
- Speeds up as dots decrease

**Pinky (Pink)**
- Tries to ambush ahead of you
- Targets 4 tiles in front
- Good at cutting you off

**Inky (Cyan)**
- Most unpredictable
- Behavior changes based on Blinky
- Can surprise you

**Clyde (Orange)**
- Least threatening
- Chases when far, scatters when close
- Good for beginners to practice on

---

## 📥 Installation Guide

### **Method 1: Install as PWA (Progressive Web App)**

Perfect for desktop icons and offline play!

#### **On Desktop (Chrome/Edge)**
1. Visit the game page
2. Look for install prompt OR
3. Click "📱 Install as App" button in sidebar
4. OR click the ⊕ icon in browser address bar
5. Click "Install"
6. Game appears on desktop/start menu
7. Launch anytime - works offline!

#### **On Mobile (Chrome/Safari)**
1. Visit the game page
2. **Android Chrome**:
   - Tap "📱 Install as App" button
   - OR tap menu (⋮) → "Add to Home screen"
3. **iOS Safari**:
   - Tap Share button (□↑)
   - Select "Add to Home Screen"
   - Name the app and add
4. Icon appears on home screen
5. Tap to play like native app!

### **Method 2: Download HTML File**

Works on ANY device, ANY browser!

#### **Steps**
1. Click "⬇️ Download HTML" button
2. File saved to Downloads folder
   - `snake-game-narengaims.html`
   - `snake-2player-narengaims.html`
   - `pacman-game-narengaims.html`
3. Find the file in your Downloads
4. Double-click to open in browser
5. Play offline anytime!

#### **Advanced: Organize Downloaded Games**
```
📁 My Games/
  ├── 🐍 snake-game-narengaims.html
  ├── 🐍🐍 snake-2player-narengaims.html
  └── 👻 pacman-game-narengaims.html
```

**Create Desktop Shortcuts:**
- Windows: Right-click file → Send to → Desktop
- Mac: Drag file to Dock
- Linux: Create launcher in applications menu

---

## 💻 Technical Information

### **Technology Stack**
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6)
- **Graphics**: HTML5 Canvas API
- **Storage**: Browser localStorage
- **PWA**: Service Workers, Web Manifest
- **No Dependencies**: Zero external libraries

### **File Structure**
```
narengaims/
├── login.html              # Authentication page
├── index.html              # Game hub/selection
├── snake.html              # Single player Snake
├── snake-2player.html      # 2 Player Snake Battle
└── pacman.html             # Pac-Man
```

### **Data Storage**

All data stored locally in browser using `localStorage`:

#### **User Data**
```javascript
{
  "narengaims_current_user": {
    "username": "YourName",
    "email": "your@email.com",
    "isGuest": false,
    "loginTime": "2024-01-01T00:00:00.000Z"
  }
}
```

#### **Snake Stats**
```javascript
{
  "snake_stats": {
    "personalBest": 150,
    "gamesPlayed": 42
  }
}
```

#### **2 Player Snake Stats**
```javascript
{
  "snake_2p_stats": {
    "p1Wins": 12,
    "p2Wins": 10,
    "totalGames": 22
  }
}
```

#### **Pac-Man Stats**
```javascript
{
  "pacman_stats": {
    "personalBest": 3420,
    "gamesPlayed": 28
  }
}
```

### **Browser Compatibility**

| Browser | Version | PWA Install | Offline Play | HTML Download |
|---------|---------|-------------|--------------|---------------|
| Chrome | 80+ | ✅ | ✅ | ✅ |
| Edge | 80+ | ✅ | ✅ | ✅ |
| Firefox | 75+ | ⚠️ | ✅ | ✅ |
| Safari | 13+ | ⚠️ | ⚠️ | ✅ |
| Mobile Chrome | Latest | ✅ | ✅ | ✅ |
| Mobile Safari | Latest | ✅* | ✅ | ✅ |

✅ = Fully Supported
⚠️ = Partial Support
\* = Via "Add to Home Screen"

### **Performance**

- **Frame Rate**: 60 FPS (Snake), 60 FPS (Pac-Man)
- **File Size**: 
  - Snake: ~50 KB
  - 2P Snake: ~65 KB
  - Pac-Man: ~70 KB
- **Load Time**: < 1 second
- **Memory Usage**: < 50 MB
- **No Server Needed**: 100% client-side

### **Privacy & Security**

✅ **No Data Collection**: Everything stored locally
✅ **No Tracking**: No analytics or cookies
✅ **No Ads**: Pure gaming experience
✅ **Open Source Ready**: Can be self-hosted
✅ **Offline First**: Works without internet

---

## 🔧 Troubleshooting

### **Common Issues**

#### **Game Won't Load**
**Problem**: Blank screen or loading forever

**Solutions**:
- ✅ Refresh the page (F5 or Ctrl+R)
- ✅ Clear browser cache
- ✅ Check if JavaScript is enabled
- ✅ Try different browser
- ✅ Disable browser extensions temporarily

#### **Can't Install as PWA**
**Problem**: No install button appears

**Solutions**:
- ✅ Use Chrome or Edge (best PWA support)
- ✅ Make sure you're on HTTPS (secure connection)
- ✅ Try manual install: Browser menu → "Install app"
- ✅ Use "Download HTML" as alternative

#### **Controls Not Working**
**Problem**: Keyboard doesn't control game

**Solutions**:
- ✅ Click inside game area to focus
- ✅ Check if another program is capturing keys
- ✅ Refresh the page
- ✅ Try different keys (WASD vs Arrows)

#### **Stats Not Saving**
**Problem**: High scores disappear after closing

**Solutions**:
- ✅ Don't use Incognito/Private mode
- ✅ Check browser allows localStorage
- ✅ Clear cookies/data and try again
- ✅ Make sure same browser is used

#### **Downloaded File Won't Open**
**Problem**: Double-click doesn't work

**Solutions**:
- ✅ Right-click → "Open with" → Choose browser
- ✅ Drag file into open browser window
- ✅ Check file extension is .html
- ✅ Make sure HTML files associated with browser

#### **Game Runs Slow**
**Problem**: Laggy or stuttering gameplay

**Solutions**:
- ✅ Close other browser tabs
- ✅ Update browser to latest version
- ✅ Check CPU usage (close background apps)
- ✅ Try different browser
- ✅ Reduce screen resolution if on old device

#### **Sound Issues**
**Problem**: No sound or audio problems

**Solutions**:
- ✅ Games currently have no sound (visual only)
- ✅ Feature may be added in future updates

### **Browser-Specific Issues**

#### **Safari (Mac/iOS)**
- PWA install via "Add to Home Screen" only
- Some localStorage issues in private mode
- Use Chrome/Firefox for best experience

#### **Firefox**
- PWA install button may not appear
- Use "Download HTML" method instead
- All gameplay features work perfectly

#### **Mobile Browsers**
- Controls designed for keyboard (desktop)
- Mobile controls not yet implemented
- Best played on desktop/laptop

---

## 📞 Support & Feedback

### **Need Help?**
- 📧 Contact website administrator
- 🐛 Report bugs or issues
- 💡 Suggest new features
- ⭐ Share feedback

### **Future Updates**
Planned features:
- 🔊 Sound effects and music
- 📱 Touch controls for mobile
- 🎮 More classic games
- 🏆 Global leaderboards
- 👥 Multiplayer online modes
- 🎨 More customization options

---

## 🎉 Quick Start Checklist

Ready to play? Follow these steps:

- [ ] Visit narengaims website
- [ ] Create account or continue as guest
- [ ] Choose your game from hub
- [ ] Read game-specific controls
- [ ] Start playing!
- [ ] (Optional) Install as PWA for offline play
- [ ] (Optional) Download HTML for portable gaming

---

## 📜 License & Credits

**narengaims** - Classic Games Collection

Games inspired by classic arcade titles:
- Snake: Nokia phone classic
- Pac-Man: Namco arcade classic

Built with ❤️ using modern web technologies.

---

## 🎮 Game On!

Thank you for playing **narengaims**! Whether you're chasing high scores in Snake, battling friends in 2 Player mode, or munching dots in Pac-Man, we hope you enjoy these classic games.

**Remember**: Games are meant to be fun. Take breaks, stay hydrated, and game responsibly!

---

*Last Updated: 2024*
*Version: 1.0*
*Compatible with all modern browsers*

# Motion-Based CAPTCHA Game

## About

This project reimagines CAPTCHA security for the age of Large Language Models. Created by Benedict Neo, Wei Chun Tan, and Adrian Lam, this game demonstrates a novel approach to human verification that's inherently resistant to AI manipulation.

### The Concept

While traditional CAPTCHAs may become vulnerable to increasingly sophisticated LLMs, our solution leverages a fundamental difference between human and AI perception: motion processing. Humans naturally experience and interpret motion blur in real-time, while AI systems process digital displays frame-by-frame. This distinction forms the basis of our innovative security approach.

### How It Works

The game presents users with various moving patterns, including circles, squares, triangles, and the special Figure-8 pattern. Players must identify and click specifically during the Figure-8 pattern to win. The addition of noise elements and continuous motion creates a challenge that's intuitive for humans but difficult for AI to interpret through static frame analysis.

## Features

- Multiple geometric patterns (Circle, Square, Figure-8, Triangle, Zigzag)
- Dynamic pattern transitions
- Visual noise elements for added challenge
- Smooth animations and transitions
- Dark mode support
- Responsive design

## How to Play

1. Click "Start Game" to begin
2. Watch the red target move in different patterns
3. Click when you see the special Figure-8 pattern (indicated by yellow pulsing)
4. Click during any other pattern and you lose!
5. Mouse leaving the game area will reset the game

## Technical Details

### Dependencies
- React 
- Tailwind CSS
- Geist Sans font

### Game Constants
```javascript
RADIUS = 200
BALL_SIZE = 24
TARGET_SIZE = 28
NOISE_SIZE = 16
PATTERN_DURATION = 5
SPEED_MULTIPLIER = 2
NUM_NOISE_CIRCLES = 8
```

### Patterns
The game includes five distinct patterns:
- Circle: Circular motion
- Square: Four-sided perimeter motion
- Figure-8: Special winning pattern
- Triangle: Three-sided perimeter motion
- Zigzag: Sine wave with vertical displacement

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/pattern-recognition-game.git
```

2. Install dependencies:
```bash
cd pattern-recognition-game
npm install
```

3. Run the development server:
```bash
npm run dev
```

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

MIT License - feel free to use and modify for your own projects.

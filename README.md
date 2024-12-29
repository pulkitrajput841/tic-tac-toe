# Real-Time Multiplayer Tic Tac Toe

A real-time multiplayer Tic Tac Toe game built with Python (Flask), WebSocket, and modern JavaScript. Players can create game rooms and share links with friends to play together in real-time.



## ✨ Features
- Real-time multiplayer gameplay powered by WebSockets
- Unique game rooms with shareable links
- Clean, modern, and responsive user interface
- Lightweight and fast: all game state managed in memory
- Cross-browser compatibility
- Mobile-friendly design

## 🛠️ Technology Stack
- **Backend**: Python (Flask Framework)
- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Real-time Communication**: WebSocket (Flask-SocketIO)
- **Deployment**: Docker, Render

## 🚀 Getting Started



### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe.git
   cd tic-tac-toe
2. Install dependencies:
3. Run the server:
  


4. Open your browser and visit [http://127.0.0.1:5000](http://127.0.0.1:5000).

## 📝 How to Play
1. Visit the homepage and click **"Create New Game"**.
2. Share the generated game link with a friend.
3. Wait for your friend to join.
4. Play alternately until someone wins or the game draws.
5. Click **"Play Again"** to start a new game.

## 🎯 Game Rules
- The game is played on a 3x3 grid.
- Players take turns marking their symbols (O or X) in empty squares.
- The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins.
- If all nine squares are filled without a winner, the game ends in a draw.

## 🔧 Project Structure
```
tic-tac-toe/  
├── app.py             # Main server file  
├── requirements.txt   # Python dependencies  
├── static/  
│   ├── css/  
│   │   ├── styles.css   # Homepage styles  
│   │   └── game.css     # Game page styles  
│   └── js/  
│       └── game.js      # Game logic  
└── templates/  
    ├── index.html      # Homepage template  
    └── game.html       # Game page template  
```

## 🤝 Contributing
Contributions are welcome! Please follow the steps below to submit your changes:

1. Fork the project.
2. Create your feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request.



## 🔮 Future Improvements
- Add game history tracking
- Implement user authentication
- Introduce a game timer
- Save game statistics
- Add sound effects
- Support for custom board sizes
- Integrate chat functionality
- Implement game replay features

## 📞 Contact
Project Link: [https://github.com/your-username/tic-tac-toe](https://github.com/your-username/tic-tac-toe)

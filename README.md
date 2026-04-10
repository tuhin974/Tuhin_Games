A modern browser-based Pong Game built using JavaScript, featuring smooth animations, AI opponent, and dynamic ball physics.

🚀 Live Demo

👉 https://github.com/tuhin974/Tuhin_Games

📌 Features
🎮 Smooth paddle movement (Mouse)
🤖 AI-controlled opponent
⚡ Realistic ball physics with spin effect
📊 Live score tracking
🔄 Reset game functionality
🏆 Win condition (First to 10 points)
🎨 Clean neon-style UI
🛠️ Tech Stack
HTML

🎯 Game Logic Highlights
🟢 Collision Handling
Detects collision between ball and paddles
Reverses ball direction on impact
Prevents ball from “sticking” inside paddles
🌀 Spin Mechanics
const deltaY = (ball.y - (paddle.y + paddle.height / 2)) / paddle.height;
ball.speedY += deltaY * 4;
Ball direction changes based on where it hits the paddle
Adds more realistic gameplay
⚖️ Speed Limiting
ball.speedY = Math.max(-ball.maxSpeed, Math.min(ball.maxSpeed, ball.speedY));
Keeps gameplay balanced and controlled

🕹️ Controls
🖱️ Mouse → Move paddle up/down
🤖 Computer → Controls right paddle automatically
🏆 Rules
First player to reach 10 points wins
If both reach 10 → Draw
Game resets automatically after result.


Feel free to fork this project and submit pull requests.

📬 Contact

If you have feedback or suggestions, feel free to connect with me on LinkedIn.

⭐ Acknowledgment

Built with the help of GitHub AI and further customized for improved gameplay and logic.

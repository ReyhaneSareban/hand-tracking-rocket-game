# Hand Tracking Rocket Game

A Python arcade game where you control a rocket using real-time hand tracking instead of a keyboard or mouse.

Built with **Pygame, OpenCV, and MediaPipe**, this project combines game development with computer vision.

## Features

- **Hand Tracking:** Move the rocket horizontally by moving your hand.
- **Gesture Shooting:** Make a fist to shoot bullets.
- **Stone Enemies:** Dodge and shoot moving obstacles.
- **Score System:** Earn points by hitting enemies.
- **Sound Effects:** Background music and shooting and collision sounds.
- **Game Over:** The game ends when the enemies reach the bottom.

## Technologies Used

- Python
- Pygame
- OpenCV
- MediaPipe
- Random and Math modules

## Requirements

Install the required libraries:

```bash
pip install pygame opencv-python mediapipe
```

## Project Setup

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Navigate to the project folder:

   ```bash
   cd hand-tracking-rocket-game
   ```

3. Make sure all game assets are in the project directory.

4. Run the Python script:

   ```bash
   python main.py
   ```

5. Allow access to your webcam when prompted.

## Controls

- Move your hand left or right to control the rocket.
- Make a fist to shoot.
- Destroy the stones to increase your score.

## Assets

The game requires the following files:

- `background.png`
- `rocket.png`
- `stone.png`
- `bullet.png`
- `background.mp3`
- `pew.mp3`
- `fire.mp3`

Place these files in the same directory as `main.py`.

## How It Works

MediaPipe Hands detects hand landmarks through the webcam. The wrist position controls the rocket's horizontal movement, while finger landmarks are used to detect a closed-fist gesture.

Pygame handles the game window, sprites, movement, collisions, scoring, and audio playback.

## License

This project is available for learning and personal use. Add a license file if you want to specify how others can use, modify, and distribute your code.

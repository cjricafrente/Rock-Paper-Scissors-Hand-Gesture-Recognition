#Rock Paper Scissors – Hand Gesture Recognition 

This project is an interactive Rock, Paper, Scissors game built with Python, OpenCV, and MediaPipe.
You play against the computer using your hand gestures in front of your webcam!

#Features

Real-time hand tracking using MediaPipe Hands.

Detects Rock , Paper , and Scissors gestures.

Countdown timer before each round for fair play.

Displays results (Win, Lose, or Draw) on the video feed.

Simple and fun computer opponent.

#Requirements

Make sure you have Python 3.7+ installed, then install the dependencies:

pip install opencv-python mediapipe

#How to Play

Clone or download this repository.

Run the Python script:

python play.py


When the game window opens:

Press SPACE to start the countdown.

Show your hand gesture when prompted ("PLAY NOW!").

The computer will randomly choose Rock, Paper, or Scissors.

Results are displayed on the screen.

Press ESC anytime to quit.

#Recognized Gestures

Rock → Closed fist

Paper → Open hand

Scissors → Index and middle finger up, others down

If your gesture is unclear, it will register as UNKNOWN.

#Project Structure
rock-paper-scissors/
│── play.py        # Main script (game logic + gesture detection)
│── README.md      # Project documentation

#Example Gameplay

When you press space:

Countdown starts.

After 3 seconds, show your gesture.

Game compares your move vs computer’s move and shows result.

#Future Improvements

Add score tracking (Player vs Computer).

Support for multiplayer over webcam.

More advanced hand gesture recognition.

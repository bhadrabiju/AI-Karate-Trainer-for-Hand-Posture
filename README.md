# AI-Karate-Trainer-for-Hand-Posture
Developed for correcting the position of the hand symbols in Karate.


📌 Project Overview
-------------------
AI Karate Trainer for Hand Posture is a computer vision–based system that detects whether a karate hand posture is performed correctly. The system validates the hand pose in real time, and only when the posture is correct, it identifies and displays the corresponding karate hand symbol.
This project helps users practice karate hand techniques without a physical trainer, by ensuring correct posture before recognizing the gesture.

🎯 Key Features
----------------
- Real-time hand posture detection using computer vision
- Pose validation logic to ensure correctness
- Symbol identification only after correct posture is detected
- Uses hand landmark analysis for accurate posture evaluation
- Lightweight and efficient real-time processing

🧠 How It Works
---------------
Captures live video input through camera and detects hand landmarks using MediaPipe also analyzes landmark positions to validate hand posture.

If the posture matches predefined criteria:
    It displays the name of the karate hand symbol

If posture is incorrect:
    It displays 'Adjust the position'

🛠️ Technologies Used
--------------------
Python
OpenCV
MediaPipe
NumPy
Hand Landmark Detection

🚀 Use Cases
------------
- Karate beginners practicing hand techniques
- Self-learning martial arts without a physical trainer
- AI-based posture validation systems
- Computer vision learning projects

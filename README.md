# Sign Language Visual Interpreter

A real-time Sign Language to Text & Speech conversion system built using **Python, OpenCV, Mediapipe, and Tkinter**.

## Features
- Detects hand gestures via webcam
- Converts sign language into text
- Speaks detected words using pyttsx3
- Intelligent spell correction suggestions

## Tech Stack
- TensorFlow / Keras (for model)
- Mediapipe & cvzone (for hand tracking)
- Tkinter (for GUI)
- Pyttsx3 (for text-to-speech)

## Run Locally
```bash
git clone https://github.com/<your-username>/Sign-Language-Visual-Interpreter.git
cd Sign-Language-Visual-Interpreter
pip install -r requirements.txt
python run_prediction.py

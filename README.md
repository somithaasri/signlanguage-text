# signlanguage-text
# Sign Language to Text Converter 

This project aims to **convert Indian Sign Language gestures into readable English text** using computer vision and machine learning. The system processes hand gestures via webcam input and provides real-time text output, enabling communication between deaf or mute individuals and non-sign language speakers.

---

## Features

- Real-time hand gesture detection using **MediaPipe**
- Keypoint extraction and classification using **TensorFlow**
- Conversion of static signs (like alphabets A-Z and common words) to text
- Trained ML model for recognizing multiple signs
- GUI/Console display for real-time output
- Numpy-based keypoint storage for faster processing and training

---

## Installation

1. **Clone the Repository**
```bash
git clone https://github.com/somithaasri/signlanguage-text.git
cd signlanguage-text

Install Dependencies
pip install -r requirements.txt

If requirements.txt is missing, manually install:
pip install opencv-python mediapipe tensorflow numpy

▶️ How to Run
Make sure your webcam is connected.
Run the main file:
python main.py
You’ll see a live video feed. Make a hand gesture (like A, B, C...), and the detected letter will appear as text on the screen.







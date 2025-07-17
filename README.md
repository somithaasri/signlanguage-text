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

🔧 Installation & Setup
Follow these steps to install and run the project on your local machine:

1. ✅ Clone the Repository
bash
Copy
Edit
git clone https://github.com/somithaasri/signlanguage-text.git
cd signlanguage-text
2. 🐍 Set Up a Virtual Environment (Recommended)
bash
Copy
Edit
# Create virtual environment
python -m venv venv

# Activate it
# Windows:
venv\Scripts\activate

# macOS/Linux:
source venv/bin/activate
3. 📦 Install Required Packages
If a requirements.txt file is present:

bash
Copy
Edit
pip install -r requirements.txt
Or manually install the core dependencies:

bash
Copy
Edit
pip install opencv-python mediapipe tensorflow numpy
▶️ Running the Project
Make sure your webcam is enabled before running.

1. Run the Main Application
bash
Copy
Edit
python main.py
2. What Happens Next?
A live webcam feed will open.

Show a hand gesture corresponding to a supported sign (e.g., 'A', 'B', 'C'...).

The predicted gesture will appear as text on the screen.









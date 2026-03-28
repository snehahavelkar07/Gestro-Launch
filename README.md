 # Gestro-Launch
Hand gesture-based PC control system using Python and MediaPipe
# Gestro Launch 🚀
*An AI-powered Hand Gesture Recognition & PC Control System*

Gestro Launch is an innovative project designed to provide touchless interaction with computers. Using Computer Vision and Machine Learning, this system allows users to navigate their PC, perform mouse actions, and even control remote systems (Teleport) using simple hand gestures.

---

## ✨ Key Features
* *Mouse Navigation:* Move the cursor smoothly across the screen using index finger tracking.
* *Clicking & Scrolling:* Perform left/right clicks and scroll up/down through intuitive gestures.
* *Teleport Feature:* Remotely control a second laptop/PC from the host machine using networked data transfer.
* *System Controls:* Execute system commands like volume control, camera toggle, or shutdown via specific hand landmarks.
* *Web Dashboard:* Interactive UI built with Streamlit for real-time monitoring.

---

## 🛠️ Tech Stack
* *Language:* Python 3.x
* *Computer Vision:* MediaPipe, OpenCV
* *GUI / Dashboard:* Streamlit
* *Automation:* PyAutoGUI
* *Data Handling:* NumPy, Pandas
* *Development:* VS Code, Jupyter Notebook

---

## 📁 Project Structure
* app.py: The main Streamlit web application and gesture processing engine.
* main_code.py: Core logic for hand landmark detection and gesture mapping.
* teleport_code.py: The receiver-side script to be run on the target laptop for remote control.
* requirements.txt: List of all Python dependencies required to run the project.

---

## 🚀 How to Run

1. *Clone the Repository:*
   ```bash
   git clone [https://github.com/snehahavelkar07/Gestro-Launch.git](https://github.com/snehahavelkar07/Gestro-Launch.git)
   cd Gestro-Launch

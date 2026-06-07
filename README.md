# 👁️🖐️ Vision-Guided Virtual Control System

## 📌 Overview

The Vision-Guided Virtual Control System is a computer vision-based Human-Computer Interaction (HCI) project that enables users to control a computer using eye movements and hand gestures. The system utilizes real-time webcam input to track facial landmarks, eye movements, and hand gestures, providing a touchless and intuitive interaction experience.

This project integrates eye tracking, hand tracking, and a virtual keyboard to create an accessible and futuristic control interface without requiring specialized hardware.

---

## 🚀 Features

* Real-time Eye Tracking
* Hand Gesture Recognition
* Virtual Keyboard Interface
* Touchless Computer Interaction
* Webcam-Based Control System
* Cursor Navigation Using Gestures
* Interactive User Interface
* Lightweight and Easy to Deploy

---

## 🛠️ Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy
* PyAutoGUI
* Computer Vision
* Machine Learning-Based Landmark Detection

---

## 📂 Project Structure

```text
Vision-Guided-Virtual-Control/
│
├── main.py                 # Main application entry point
├── eye_tracker.py          # Eye tracking module
├── hand_tracker.py         # Hand gesture detection module
├── virtual_keyboard.py     # Virtual keyboard implementation
├── controller.py           # Control logic and action mapping
├── utils.py                # Utility functions
├── requirements.txt        # Required dependencies
├── README.md
└── Directory.txt
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/veeramalla-manikanta/Vision-Guided-Virtual-Control.git
cd Vision-Guided-Virtual-Control
```

### Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Execute the main application:

```bash
python main.py
```

Ensure that your webcam is connected and accessible before running the program.

---

## 🖥️ System Workflow

1. Webcam captures live video feed.
2. Eye tracking module detects and monitors eye movements.
3. Hand tracking module identifies hand landmarks and gestures.
4. Controller processes user inputs.
5. Virtual keyboard allows touchless text input.
6. Actions are translated into computer commands in real time.

---

## 🎯 Key Modules

### Eye Tracker

* Detects facial landmarks.
* Tracks eye movement patterns.
* Enables gaze-based interaction.

### Hand Tracker

* Detects hand landmarks using MediaPipe.
* Recognizes gestures for control actions.
* Supports real-time tracking.

### Virtual Keyboard

* Displays an on-screen keyboard.
* Allows text entry through gestures.
* Eliminates the need for a physical keyboard.

### Controller

* Maps detected gestures and eye movements to system actions.
* Coordinates communication between modules.

---

## 📊 Applications

* Touchless Computing
* Accessibility Assistance
* Smart Workstations
* Virtual Input Systems
* Human-Computer Interaction Research
* Gesture-Controlled Applications
* Assistive Technology Solutions

---

## 🔮 Future Enhancements

* Voice Command Integration
* Custom Gesture Training
* Multi-Hand Tracking Support
* AI-Based Gesture Classification
* Improved Eye-Gaze Accuracy
* Cross-Platform Deployment
* Real-Time Performance Optimization

---

## 📸 Demo

Add screenshots, GIFs, or videos demonstrating the system here.

```markdown
![Demo Screenshot](demo.png)
```

---

## 📋 Requirements

The project dependencies are listed in:

```text
requirements.txt
```

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Manikanta Veeramalla**

Data Analyst | Power BI Developer | Computer Vision Enthusiast

GitHub:
https://github.com/veeramalla-manikanta


---

## ⭐ Support

If you found this project useful, consider giving it a star ⭐ on GitHub.

Contributions, suggestions, and feedback are always welcome!

---

## 📜 License

This project is licensed under the MIT License.


# ✋🖊️ Airboard – Virtual Handwriting Board Using Hand Tracking

Airboard is a virtual whiteboard application that uses **hand tracking via webcam** to allow users to draw in the air using their finger gestures. The application leverages computer vision techniques to detect hand landmarks and track finger movements for intuitive air-based interaction.

## 📌 Features

- 🖐️ **Real-time Hand Detection** using MediaPipe
- 🧠 **Index Finger Tracking** to detect drawing gestures
- 🧼 **Virtual Eraser** via gesture-based tool switching
- 🎨 **Air Drawing** with live webcam feed overlay
- ⚙️ Modularized into camera, hand tracking, and main app files

## 🗂️ File Structure

```
📦Airboard/
 ┣ 📜HandTrackingModule.py   # Hand detection and finger tracking module (MediaPipe-based)
 ┣ 📜app.py                  # Main application logic and UI handling
 ┣ 📜camera.py               # Webcam capture and frame management
 ┗ 📜README.md               # Project overview and setup instructions
```

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7+
- OpenCV
- MediaPipe
- NumPy

Install required packages:
```bash
pip install opencv-python mediapipe numpy
```

### ▶️ Run the Application

```bash
python app.py
```

Make sure your webcam is connected and accessible.

## 📷 How It Works

- Uses **MediaPipe Hands** to detect hand landmarks.
- Index finger tip (landmark 8) is tracked for drawing.
- Drawing is done by tracking movement across frames.
- Gesture toggling (e.g., between pen and eraser) can be added by detecting finger combinations.

## 🎯 Applications

- Touchless drawing apps
- Virtual classrooms and tutorials
- Gesture-controlled UI
- Human-computer interaction demos

## 👤 Author

**Mayur Agrawal**  
🔗 [GitHub](https://github.com/mayuragrawal21) | [LinkedIn](https://www.linkedin.com/in/mayur-agrawal21/)  
📧 [agrawalmayur2001@gmail.com](mailto:agrawalmayur2001@gmail.com)



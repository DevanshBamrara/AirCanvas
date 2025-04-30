# Hand Gesture Drawing App 🖊️

A Python-based app that enables you to draw on a virtual canvas using only hand gestures, detected through your webcam. It uses **MediaPipe** for hand tracking and **OpenCV** for drawing functionalities.

## 🔧 Features

- ✋ Draw using your **index finger**.
- 🖊 Choose from multiple colors: **Blue**, **Green**, **Red**, and **Yellow**.
- ♻ Clear the canvas with a single gesture.
- 📸 Take a **snapshot** of your drawing and save it as a PNG.
- 📺 Real-time interaction through webcam.

Make sure your webcam is connected and accessible by OpenCV.

## ⚡ Usage Instructions

- Use only **one hand** for accurate detection.
- Raise your **index finger** to draw.
- Touch the top on-screen buttons with your finger to:
  - **CLEAR**: Erase everything from the canvas.
  - **BLUE / GREEN / RED / YELLOW**: Change brush color.
  - **SNAPSHOT**: Save the current canvas to the `images/` directory.
- Press **'q'** to quit the application.

# Object Detection & Hand Gesture Drawing App 🎯✋🎨

This project contains two main functionalities:

1. **Object Detection** using YOLOv4-tiny via OpenCV's DNN module.
2. **AirFlow Drawing App** using hand gesture recognition powered by MediaPipe.

---

## 📦 Contents

- `main.py`: Runs YOLOv4-tiny object detection using a webcam.
- `AirFlow.py`: Launches a gesture-based virtual paint app using hand tracking.
- `dnn_model/`: Folder containing `yolov4-tiny.weights`, `yolov4-tiny.cfg`, and `classes.txt`.

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/jaya-sri6/Object_Detection.git
cd Object_Detection

**2. Install Dependencies**
bash
Copy
Edit
pip install opencv-python mediapipe numpy
✅ Ensure your dnn_model folder contains:

yolov4-tiny.weights

yolov4-tiny.cfg

classes.txt

**3. Run Object Detection**
bash
Copy
Edit
python main.py
Detects real-time objects using webcam.

Uses YOLOv4-tiny for fast and accurate inference.

**4. Run Hand Drawing App**
bash
Copy
Edit
python AirFlow.py
Draw on-screen using your index finger.

Color and clear buttons are recognized using hand gestures.

📌 Features
🎯 Real-time object detection with bounding boxes.

🎨 Paint using finger gestures on a virtual canvas.

🖱️ Click detection in object detection mode via mouse callback.

🎈 Uses lightweight models suitable for real-time use.


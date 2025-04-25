# 🎥 Real-Time Face Detection with OpenCV and Dlib

This project demonstrates real-time face detection using OpenCV and Dlib in Python. It captures video from your webcam, detects faces in each frame, and displays bounding boxes with labels for each detected face.

---

## 📸 Features

- ✅ Real-time video capture from your webcam
- ✅ Face detection using Dlib's frontal face detector
- ✅ Bounding boxes drawn around each face
- ✅ Sequential labeling of detected faces
- ✅ Mirror-like view with horizontal flip
- ✅ Press `q` to quit the app

---

## 🛠️ Requirements

Make sure you have Python installed, then install the required libraries:

```bash
pip install opencv-python numpy dlib
```


## How to Run 

1. Clone the repository:
```bash
git clone https://github.com/bridgeshayes/Face-Detection.git
cd Face-Detection
```

2. Run the script:
```bash
python faceDet.py
```

### How it Works
- Uses OpenCV's VideoCapture(0) to access your webcam
- Flips the frame horizontally for a natural selfie view
- Converts the frame to grayscale for faster processing
- Detects faces using dlib.get_frontal_face_detector()
- Draws green rectangles around detected faces
- Labels each face with a number using cv2.putText()


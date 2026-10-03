# handtapak

Hand detection experiments with Python using OpenCV and MediaPipe, built on a small `HandDetection` wrapper class.

## Features

- `handDetection.py`: wrapper class around MediaPipe Hands that finds hand landmarks in OpenCV frames.
- `main.py`: webcam app that reads the thumb-index distance, sets screen brightness, and draws a volume percentage bar on the video feed.
- `sketch.py`: live sketch camera (grayscale, blur, Canny edge filter).

## Requirements

- Python packages: opencv-python, mediapipe, numpy, screen-brightness-control, pycaw.

## Usage

```bash
python main.py     # brightness control and volume bar from hand gestures
python sketch.py   # live sketch camera
```

Press "p" in the OpenCV window to quit.

## Author

Haikal Akhalul Azhar

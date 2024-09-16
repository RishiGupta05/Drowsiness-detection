
# Face Detection and Blink Detector

This project uses OpenCV, dlib, and pygame libraries to detect faces in a video stream and determine if the user's eyes are open or closed (blinking). If the user's eyes remain closed for a certain period, an alert message is displayed, and an audio file (.WAV) is played.


## Tech Stack

** Requirements: ** 

- Python 3.x
- OpenCV
- dlib
- pygame
- imutils
- numpy


## Installation

Install the required libraries using pip:

```bash
  pip install opencv-python
  pip install opencv-python-headless
  pip install dlib
  pip install imutils
  pip install numpy
  pip install pygame
```

Download the following files and place them in the project directory:

1. music.wav()
2. shape_predictor_68_face_landmarks.dat


## Usage/Examples

Run the script:

```bash
1. python face_blink_detector.py

```
2. Allow the webcam access and observe the video stream. If the user's eyes remain closed for a certain period, an alert message is displayed, and an audio file is played.

3. Press 'q' to quit the application.

## Configuration


1. ["thresh"]: The threshold for detecting a blink.
2. ["frame_check"]: The number of frames required to trigger an alert.


## Future Development

1. Improve accuracy: Integrate more advanced machine learning models for face detection and   blink detection.

2. Multi-face support: Modify the script to detect and track multiple faces.

3. Real-time analytics: Display real-time statistics on blink frequency, duration, and other metrics.

4. Alert customization: Allow users to customize the alert message, audio, and duration.

5. Integration with other sensors: Integrate with other sensors, such as heart rate or skin conductance, to create a more comprehensive fatigue detection system.
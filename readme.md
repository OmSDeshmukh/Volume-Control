# Hand Gesture Recognition for Volume Control

This project implements hand landmark detection, tracking, determining left or right hand, angle detection between fingers, and device (Mac) volume control through hand gestures. The implementation is based on the `mediapipe` and `opencv` libraries, along with other necessary Python libraries.

## Features

- Hand Landmark Detection: Identifies key points on the hand.
- Hand Tracking: Tracks hand movement in real-time.
- Left/Right Hand Detection: Determines whether the detected hand is left or right.
- Finger Angle Detection: Measures the angle between fingers.
- Volume Control: Adjusts the device volume using hand gestures.

## Usage
1. Clone the repo

```bash
git clone https://github.com/yourusername/your-project.git
cd your-project
```

2. Create a Python Environment and activate it
```bash
python -m venv venv
source venv/bin/activate
```

3.Install the dependencies

```bash
pip install -r requirements.txt
```

4.Run the jupyter notebook

```bash
jupyter notebook main.ipynb
```

## References

- [MediaPipe Documentation](https://mediapipe.dev/)
- [OpenCV Documentation](https://docs.opencv.org/)
- [Nicholas Renotte YouTube Channel](https://www.youtube.com/c/nicholasrenotte) - Link to the YouTube channel for further reference.


## Aknowledgements
Special thanks to Nicholas Renotte whose YouTube video provided valuable insights and guidance in creating this project.


## License
This project is licensed under the MIT License.
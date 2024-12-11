# Hand Gesture Detection

This project is a simple hand gesture detection application built using OpenCV and MediaPipe. The application uses your webcam to detect hands in real-time and visualize the landmarks and connections between them.

## Features

- Real-time hand detection using a webcam.
- Visualizes hand landmarks and connections.
- Simple and lightweight implementation.

## Requirements

Make sure you have the following installed on your system:

- Python 3.6 or later
- Required Python libraries:
  - `opencv-python`
  - `mediapipe`

You can install the required Python libraries using the following command:
```bash
pip install opencv-python mediapipe
```

## How to Run

1. Clone or download this repository to your local machine.
2. Ensure your Python environment has the necessary dependencies installed.
3. Save the provided `main.py` file to your project directory.
4. Run the application using:
   ```bash
   python main.py
   ```
5. Allow access to your webcam if prompted.
6. The application will display a window showing the real-time video feed with hand landmarks and connections drawn. Press `q` to exit the application.

## How It Works

1. The application initializes the MediaPipe Hands solution to detect and track hand landmarks.
2. The webcam feed is captured frame by frame using OpenCV.
3. Each frame is processed by MediaPipe to detect hand landmarks.
4. If hands are detected, landmarks and connections are drawn on the video feed.
5. The processed video is displayed in a window.

## Controls

- Press `q` to quit the application.

## Example Output

The application will display a video window where detected hands are marked with points (landmarks) and lines (connections), similar to the following visualization:

- Points indicate the positions of hand landmarks.
- Lines connect these points to show the structure of the hand.

## License

This project is provided under the MIT License. Feel free to use and modify the code as needed.

## Acknowledgments

- [OpenCV](https://opencv.org/) for real-time computer vision.
- [MediaPipe](https://mediapipe.dev/) for its robust hand detection solution.


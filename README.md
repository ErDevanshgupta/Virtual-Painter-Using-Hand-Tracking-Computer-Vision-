

# Virtual Painter using Hand Tracking

This project utilizes computer vision techniques to create a virtual painting environment where users can draw using hand gestures captured by a webcam. The application tracks the movement of the user's hand in real-time and translates it into drawing strokes on a virtual canvas displayed on the screen.

## Features

- Real-time hand tracking and gesture recognition using MediaPipe library.
- Drawing functionality with adjustable brush thickness and eraser.
- Dynamic color selection for drawing strokes.
- Ability to pause drawing and switch between brush and eraser modes.

## How it Works

The application captures video frames from the webcam and processes them to detect the user's hand using the MediaPipe library. Once the hand is detected, the position of the index finger is tracked to determine the drawing movements. Drawing strokes are rendered on a virtual canvas overlaying the video feed based on the detected hand movements. Users can switch between brush and eraser modes and change the drawing color in real-time using keyboard shortcuts.

## Requirements

- Python 3.11.3
- OpenCV
- MediaPipe
- NumPy
   ```
## Usage

- Launch the application and position your hand in front of the webcam.
- Use your index finger to draw on the virtual canvas.
- Press 'c' to change the drawing color.
- Press 'e' to switch to the eraser mode.
- Press 'p' to pause/resume drawing.
- Press 'Esc' or 'q' to exit the application.

## Outputs
![Screenshot 2024-04-25 122355](https://github.com/ErDevanshgupta/Virtual-Painter-Using-Hand-Tracking-Computer-Vision-/assets/110588013/64b330a4-95c0-4725-bbbf-2ba810988bd5)

![Screenshot 2024-04-25 122233](https://github.com/ErDevanshgupta/Virtual-Painter-Using-Hand-Tracking-Computer-Vision-/assets/110588013/1f10f28a-ef1c-4ad7-9d87-226c1f113814)


## Acknowledgements

This project was inspired by [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) and implemented using the OpenCV library.





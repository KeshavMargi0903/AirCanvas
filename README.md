# AirCanvas

**AirCanvas** is an interactive drawing application that allows users to paint on a virtual canvas using hand gestures. The application utilizes computer vision techniques to track and identify colors and gestures, providing a dynamic and intuitive drawing experience.

## Features

- **Color Detection**: Adjust the color detection parameters using trackbars to fine-tune the application for different lighting conditions.
- **Dynamic Drawing**: Draw in real-time on a virtual canvas with four color options: Blue, Green, Red, and Yellow.
- **Clear Canvas**: Clear the canvas with a single click to start a new drawing.
- **Live Feedback**: See the drawing process and color detection in real-time through the webcam feed.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/KeshavMargi0903/AirCanvas.git
   cd AirCanvas
   ```

2. **Install dependencies:**

   Ensure you have Python 3.x installed. Install the required Python packages using `pip`:

   ```bash
   pip install numpy opencv-python
   ```

## Usage

1. **Run the application:**

   Execute the script using Python:

   ```bash
   python aircanvas.py
   ```

2. **Interact with the Application:**

   - Use the trackbars in the "Color detectors" window to adjust the color detection settings.
   - Select colors and clear the canvas using the buttons displayed in the webcam feed.
   - Draw on the canvas by moving your hand in front of the webcam.

3. **Exit the Application:**

   Press the 'q' key while the application window is focused to quit the program.

## Code Overview

- **Color Detection**: Uses OpenCV to capture webcam feed, convert it to HSV color space, and detect colors based on user-defined thresholds.
- **Drawing Functionality**: Utilizes contours to track hand movements and draw lines on the canvas.
- **GUI Elements**: Includes buttons for color selection and clearing the canvas, integrated into the live webcam feed.


## Acknowledgements

- Inspired by various OpenCV and computer vision projects.
- Special thanks to the OpenCV community for their support and resources.

# Python Object Detection Security CAM

This is a Python script that uses OpenCV to start the camera and record
video when it detects a face or body in the frame. It is a simple
implementation of computer vision techniques for real-time object
detection.

## Prerequisites

- Python 3.x - OpenCV library - Numpy library

## Installation

1. Clone the repository:

``` git clone
https://github.com/your-username/face-body-detection-camera.git
```

2. Navigate to the project directory:

``` cd face-body-detection-camera ```

3. Install the required dependencies:

``` pip install -r requirements.txt ```

## Usage

1. Run the script:

``` python camera.py ```

2. The camera will start, and the live video feed will be displayed in
a window.

3. When a face or body is detected in the frame, the script will start
recording a video.

4. Press `q` to stop the camera and exit the script.

5. The recorded videos will be saved in the `output` directory.

## Customization

You can customize the behavior of the script by modifying the following
parameters in the `camera.py` file:

- `face_cascade_path`: Path to the Haar cascade XML file for face
detection. You can replace it with your own trained cascade file if
desired. - `body_cascade_path`: Path to the Haar cascade XML file for
body detection. You can replace it with your own trained cascade file if
desired. - `output_directory`: Directory where the recorded videos
will be saved. By default, it is set to the `output` directory.

## Acknowledgments

- The face detection functionality in this script is based on the
OpenCV library. - The body detection functionality in this script is
based on the OpenCV library.

Feel free to contribute, open issues, or submit pull requests to improve
this project.

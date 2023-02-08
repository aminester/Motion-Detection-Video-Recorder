# Motion Detection Video Recorder

This is a Python script that uses OpenCV to capture video from a camera and detect motion. If motion is detected, the script starts recording a video, and continues recording until the motion stops.

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

# Prerequisites


You will need to install the following libraries:

  - OpenCV
  - Numpy

You can install these libraries using the following command:
```
 pip install opencv-python numpy
```

# Usage

Run the script using the following command:

```
  python motion_detection.py
```
The script will start capturing video from the default camera. If motion is detected, a video file will be created and recording will start. The video recording will stop when motion is no longer detected.

# Configuration

You can adjust the following parameters in the script to change its behavior:

  - SECONDS_TO_RECORD_AFTER_DETECTION: The number of seconds to continue recording after motion is no longer detected.

  - frame_size: The size of the captured video frame.

  - fourcc: The FourCC code used for video compression.

To visualize the script's tracking frame, uncomment the following code in the script:

  
      for (x, y, width, height) in faces:
        cv2.rectangle(frame, (x, y), (x + width, y + height), (255, 0, 0), 3)

# Built With:

OpenCV - An open-source computer vision and machine learning software library.

Numpy - A library for the Python programming language, adding support for large, multi-dimensional arrays and matrices.

# License:

This project is licensed under the MIT License - see the LICENSE file for details.

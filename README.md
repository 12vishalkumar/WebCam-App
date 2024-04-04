# My Camera Application

<p align="justify">✍ This application provides a simple interface for capturing images from a webcam using Python. It features a GUI built with Tkinter, allowing users to view the camera feed in real-time and take snapshots that are saved to the file system.</p>

## Features
- Real-time video feed display from the webcam.
- Button to capture and save snapshots.
- User-friendly GUI built with Tkinter.
- Dynamic button text update based on application state.

## Prerequisites

Before you can run this application, ensure you have Python installed on your system along with the following Python packages:

- `opencv-python` (cv2)
- `Pillow` (PIL)

You can install these packages using pip:

```bash
pip install opencv-python Pillow
```

### Running the Application
To run the application, navigate to the directory containing the script and execute it with Python:

``` bash
python your-file-name.py
```

### How to Use
- Upon launching the application, you'll see a window displaying the live feed from your webcam.
- Click the "Shot" button to capture an image. The image will be saved as myPic.png in the script's directory.
- After taking a photo, the button will change to allow you to reconfigure the camera for another shot.

### Limitations
- This application is designed to work with the first webcam your system recognizes (usually at index 0).
- The application saves captured images with a fixed filename, overwriting the previous capture.

### Output Screen
- Take the picture of the camera.
#### Picture
  ![picture](myPic.png)
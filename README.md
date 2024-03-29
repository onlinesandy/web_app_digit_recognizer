# Digit Recognizer Web App

This is a Python Flask web application for recognizing hand-written digits using a pre-trained deep learning model.

## Features

- Allows users to draw a digit on the web interface
- Recognizes the drawn digit using a deep learning model
- Displays the recognized digit along with confidence level

## Requirements

- Python 3.x
- Flask
- numpy
- opencv-python

Install dependencies using `pip install -r requirements.txt`.

## Usage

1. Clone this repository:

    ```
    git clone https://github.com/onlinesandy/web_app_digit_recognizer.git
    ```

2. Navigate to the project directory:

    ```
    cd web_app_digit_recognizer
    ```

3. Run the Flask app:

    ```
    python cv_web_app.py
    ```

4. Access the app in your web browser at `http://localhost:5000`

## How it Works

- The user draws a digit on the web interface.
- The drawn image is sent to the server.
- The server uses OpenCV to process the image.
- The processed image is fed into a deep learning model for digit recognition.
- The recognized digit along with confidence level is sent back to the client.
- The client displays the recognized digit and confidence level.

## Model

The deep learning model used for digit recognition is included in the project as `model.onnx`. It is loaded using OpenCV's `cv2.dnn.readNetFromONNX()` function.

## Authors

- [Sandy](https://github.com/onlinesandy)



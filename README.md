# Emotion Detection App

This is a Flask-based web application for detecting emotions from webcam feed using a pre-trained deep learning model.

## Features

- Real-time emotion detection from webcam feed
- Uses a convolutional neural network (CNN) for emotion recognition
- Displays detected emotions on the video feed

## Project Structure

```plaintext
emotion-detection-webapp/
├── app.py
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── script.js
├── haarcascade_frontalface_default.xml
└── model_file_30epochs.h5


## Getting Started

### Prerequisites

- Python 3.6 or higher

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/emotion-detection-app.git
    cd emotion-detection-app
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Download the pre-trained model and Haar Cascade file:**

    - Ensure `model_file_30epochs.h5` and `haarcascade_frontalface_default.xml` are in the root directory of the project.

### Running the Application

1. **Run the Flask application:**

    ```bash
    python app.py
    ```

2. **Open your browser and go to:**

    ```
    http://127.0.0.1:5000
    ```

## Usage

- The application will access your webcam and start detecting emotions in real-time.
- Detected emotions will be displayed on the video feed.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Acknowledgements

- The Haar Cascade classifier for face detection is provided by OpenCV.
- The pre-trained emotion detection model is built using TensorFlow and Keras.
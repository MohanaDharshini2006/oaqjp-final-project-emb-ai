# Emotion Detection Application

Final project: **Emotion Detector**, a web application built with Python and Flask that uses the Watson NLP Emotion Predict service to analyze text.

## Features

- Detects anger, disgust, fear, joy and sadness in a statement
- Returns the dominant emotion
- Handles blank or invalid input with a clear error message
- Packaged as the `EmotionDetection` Python package
- Includes unit tests and static code analysis (pylint score 10/10)

## Project structure

- `EmotionDetection/` - package containing the `emotion_detector` function
- `server.py` - Flask web application
- `test_emotion_detection.py` - unit tests
- `templates/` and `static/` - web page and JavaScript

## Run the application

```
pip3 install flask requests
python3 server.py
```

Then open the app on port 5000.

## Author

Mohana Dharshini

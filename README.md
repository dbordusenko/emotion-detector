# Final Project: Emotion Detector

An AI-based web application that detects emotions in text using the
**Watson NLP `EmotionPredict`** embeddable library, served through **Flask**.

## Project Structure

```
final_project/
├── EmotionDetection/
│   ├── __init__.py              # Task 4: package initializer
│   └── emotion_detection.py     # Tasks 2, 3, 7: core emotion_detector()
├── templates/
│   └── index.html               # Web interface
├── static/
│   └── mywebscript.js           # Front-end AJAX call
├── server.py                    # Tasks 6, 7: Flask web server
├── test_emotion_detection.py    # Task 5: unit tests
└── README.md
```

## Emotions Detected
anger, disgust, fear, joy, sadness — plus the dominant emotion.

## Run

```bash
python server.py
```

Then open http://localhost:5000/ in a browser.

## Author
IBM AI Developer Professional Certificate — Final Project.

# Emotion Detection Web Application

An AI-powered web application built with **Python**, **Flask**, and the **Watson NLP Emotion Predict API**. This project processes user-provided text to evaluate emotional tone, returning individual emotion scores and identifying the dominant emotion.

## Features

- **Watson NLP Integration:** Communicates with IBM's Watson Emotion Predict service to score `anger`, `disgust`, `fear`, `joy`, and `sadness`.
- **Flask Web Interface:** Clean web server providing a REST API endpoint `/emotionDetector` and an interactive UI.
- **Error Handling:** Robust handling for empty or malformed inputs (returns HTTP status code 400 with friendly user messages).
- **Unit Testing:** Integrated `unittest` suite validating core emotion analysis functions.
- **Code Quality:** Compliant with PEP 8 standards, achieving a **10.0/10.0** PyLint score.

---

## Project Structure

```text
final_project_emotion_detection/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── test_emotion_detection.py
├── server.py
└── README.md

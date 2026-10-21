# Emotion Detector (oaqjp-final-project-emb-ai)

An AI-based web application that detects emotions (anger, disgust, fear, joy, sadness) in text
using the Watson NLP library, served with Flask.

## Project structure
- `EmotionDetection/` - Python package containing `emotion_detector`
- `server.py` - Flask web server
- `test_emotion_detection.py` - unit tests
- `templates/index.html`, `static/mywebscript.js` - web front end

## Run
```bash
pip install flask requests pylint
python3.11 server.py
```
Open http://localhost:5000

## Test
```bash
python3.11 test_emotion_detection.py
```

## Static code analysis
```bash
pylint server.py
```

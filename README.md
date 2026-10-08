# Emotions_Detector

This is the final project for the IBM Coursera course "Developing AI Applications with Python and Flask".

## Description
This project implements an Emotion Detection web application using the IBM Watson NLP library. The application allows a user to input a text string, which is then analyzed to determine the likelihood of five specific emotions: anger, disgust, fear, joy, and sadness. The system also identifies the dominant emotion.

## Project Structure
- `EmotionDetection/`: A Python package containing the core application logic.
  - `emotion_detection.py`: Contains the `emotion_detector` function which interacts with the Watson NLP API.
- `server.py`: A Flask web application that serves the frontend and handles backend requests.
- `test_emotion_detection.py`: Contains unit tests for validating the emotion detection logic.
- `templates/index.html`: The frontend user interface for the application.

## Technologies Used
- Python
- Flask
- IBM Watson NLP API
- HTML/JavaScript
- `unittest` for testing

## How to Run Locally
1. Ensure you have Python installed.
2. Install the required dependencies:
   ```bash
   pip install Flask requests
   ```
3. Run the Flask server:
   ```bash
   python server.py
   ```
4. Open a web browser and navigate to `http://localhost:5000` to interact with the application.

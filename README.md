# Repository for final project
# Emotion Detector Application

## Overview

The Emotion Detector application is a web-based tool that analyzes text input to detect the emotions conveyed. The application utilizes IBM Watson's NLP service to predict emotions like anger, disgust, fear, joy, and sadness. The dominant emotion is then identified and displayed to the user.

## Features

- **Emotion Analysis**: Analyze text to determine the emotions expressed.
- **Error Handling**: Handles blank input entries and returns appropriate messages.
- **User Interface**: A simple web interface to input text and view emotion results.
- **Unit Testing**: Comprehensive unit tests to validate the emotion detection functionality.
- **Static Code Analysis**: Code quality maintained with Pylint for a clean and maintainable codebase.

## Project Structure

- 'final_project/'
  - `emotion_detection.py`: Contains the core logic for emotion detection using the Watson NLP service.
  - `test_emotion_detection.py`: Unit tests for the `emotion_detector` function.
  - `templates/`
    - `index.html`: The main HTML file for the user interface.
  - `static/`
    - `mywebscript.js`: JavaScript file for client-side logic (provided, no updates required).
  - `server.py`: The Flask server that handles requests and renders the user interface.

## Installation

### Prerequisites

- Python 3.11 or higher
- Flask
- Requests library




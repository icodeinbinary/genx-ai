# Google Gemini Vision Pro

![Google Gemini Vision Pro](https://img.icons8.com/color/32/000000/google-logo.png)

Google Gemini Vision Pro is a powerful tool designed to analyze images using cutting-edge AI technology. It employs a combination of image processing, speech recognition, and text-to-speech capabilities to provide users with detailed descriptions of images captured from their webcam.

## Features

- **Webcam Detection:** Seamlessly captures images from your webcam using WebRTC, OpenCV, and PIL.
- **Speech to Text:** Transcribes spoken prompts into text using Google Cloud Speech to Text API.
- **Text to Speech:** Converts text prompts and image descriptions into speech using Google Cloud Text to Speech API.
- **Image Processing:** Utilizes the Gemini AI Pro Vision API to analyze images and generate accurate descriptions.
- **Logging:** Implements Python logging for comprehensive error tracking and debugging.
- **Error Handling:** Robust exception handling ensures smooth operation even in case of unexpected errors.

## Modules Used

- **Streamlit:** Web App framework used for building the user interface.
- **Streamlit Webrtc:** Enables seamless integration of webcam functionality into the app.
- **OpenCV:** Powerful library for image processing and computer vision tasks.
- **PIL:** Python Imaging Library for image manipulation and conversion.
- **gTTS:** Provides easy-to-use interface for text-to-speech conversion.
- **SpeechRecognition:** Library for performing speech recognition in Python.
- **google.cloud.speech:** Official Google Cloud client library for Speech-to-Text conversion.

## Usage

1. **Installation:**
   
   Install the required dependencies and run the application:
   ```bash
   pip install -r requirements.txt
   streamlit run your_app.py
API Key Setup:

Enter your Gemini Vision API key in the sidebar of the application.
Functionality:

Use the provided buttons to capture an image from your webcam, speak a prompt, and request Gemini to describe the captured image.

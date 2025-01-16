# Image-captioning-and-Tagging-software
## Overview
The **Image Captioning and Tagging App** is a Streamlit-based web application that generates captions and hashtags for uploaded images using Google's Generative AI model. This project demonstrates the integration of AI-powered models to simplify the tasks of image content description and tagging.

## Features
- Upload an image in `.jpg`, `.png`, or `.jpeg` format.
- Automatically generate captions for the uploaded image.
- Generate five relevant hashtags for the image.
- Interactive and user-friendly interface powered by Streamlit.
- Error handling for invalid API keys and other potential issues.
- Simple setup and execution.

## How It Works
1. **Upload an Image**: Users can upload an image via the file uploader.
2. **Enter API Key**: The app requires a valid API key from [Google MakerSuite](https://makersuite.google.com/app/apikey).
3. **Generate Captions and Tags**: On uploading an image and entering the API key, the app:
   - Generates a caption describing the image.
   - Creates five relevant hashtags.
4. **Display Results**: The image, caption, and hashtags are displayed interactively in the app.

## Technologies Used
- **Streamlit**: For building the web interface.
- **Pillow (PIL)**: For handling image processing.
- **Google Generative AI API**: For generating captions and hashtags.
- **Python**: Programming language for application development.

## Requirements
To run the app, you need:
- Python 3.7 or higher.
- An active Google API key (can be obtained from [Google MakerSuite](https://makersuite.google.com/app/apikey)).

### Required Python Libraries
The following libraries are required and can be installed via `requirements.txt`:
```text
streamlit
Pillow
google-generativeai
```

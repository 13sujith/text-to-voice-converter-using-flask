# Text Generation Web App

This project is a simple text generation web app using GPT-2 for generating coherent paragraphs, combined with a basic Flask backend and a front-end HTML interface.

## Overview

- Uses GPT-2 model from the Hugging Face Transformers library for text generation.
- Provides a Flask server as backend.
- Includes a basic HTML frontend to interact with the text generation service.
- Debug support configured via launch.json for Visual Studio Code.

## Installation

Install dependencies listed in `requirements.txt`:


## Running the Project

Start the Flask backend server:


You should see the message `"✅ Flask is working! This is your web app."` at the root URL `/`.

Open `index.html` in a web browser to use the frontend interface.

## Project Structure

- `app.py`: Flask backend application.
- `text_generation.py`: Script to run GPT-2 text generation (can be integrated into Flask).
- `index.html`: Frontend HTML user interface.
- `launch.json`: VS Code debugger configuration.
- `requirements.txt`: Python dependencies list.
- `README.md`: This documentation file.

## Usage

- Enter a text prompt in the frontend interface.
- The backend generates continuation text using GPT-2.
- Display generated results on the webpage.

## Customization

- Modify `text_generation.py` to adjust generation parameters such as max length.
- Extend the Flask app to serve generation dynamically.
- Style the frontend interface in `index.html` further.

## License

This project is for educational purposes.



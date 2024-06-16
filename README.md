# Voice/Video Translator

This project demonstrates a real-time voice and video translator. It was developed during the GDG Baku Build AI event. The project leverages Google Cloud services for speech recognition and translation, converting Azerbaijani speech to English text and vice versa.

## Features

Real-time voice translation: Listens to speech in Azerbaijani and translates it to English.

Real-time video translation: Captures video, processes the audio in real-time, translates it, and displays the translated text on the video feed.

Text-to-speech: Converts the translated text to speech and plays it back.

## Setup
Prerequisites

Python 3.x

Google Cloud credentials (for Google Cloud Translate and Speech-to-Text services)

## Installation

Clone the repository:

````
git clone https://github.com/Lala2398/voice-video-translator.git
cd voice_video_translator
````

Install the required packages:

````
pip install -r requirements.txt
````

Set up Google Cloud credentials:

Follow the instructions to create and download a service account key file for the Google Cloud API.

Set the GOOGLE_APPLICATION_CREDENTIALS environment variable to the path of your service account key file:

````
export GOOGLE_APPLICATION_CREDENTIALS="path/to/your/service-account-file.json"
````

## Usage

- Run the script
- Interact with the video feed:

    The program will open a webcam feed.
    Speak into the microphone, and the translated text will be displayed on the video feed.
    Press 'q' to quit the video feed.

## Project Files 
- Voice_video_translator.ipnyb : The main script for the voice / video translation features.
- requirements.txt: The file listing all the required Python packages.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.


# Acknowledgments

This project was developed during the GDG Baku Build AI event. Special thanks to the organizers and participants for their support and contributions.


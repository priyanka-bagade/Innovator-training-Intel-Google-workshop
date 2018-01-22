# Innovator-training-Intel-Google-workshop

# Overview
Here is the code for speech recognition using Sphinx and Google cloud Speech API with input from micorphone. The text from speech recognition is then used as input to Google cloud Natural language API for sentiment analysis. We need a microphone to provide audio input to the program. 

# Dependencies
- PyAdudio package,  `$ pip install pyaudio`
- Pocketsphinx package, `$ pip install pocketsphinx`  
- Speech recognition, `$ pip install SpeechRecognition`
- Install Google Speech API client, `$ pip install --upgrade google-cloud-speech`
- Install Google Natural Language API client, `$ pip install --upgrade google-cloud-language`
- Authenticating to Google Cloud ML API, https://cloud.google.com/natural-language/docs/auth

# Usage
Run following code in the terminal,

`python speech_recognition_NL_processing.py`



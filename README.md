# Whisper Replit starter
How to use our Whisper API in Python

https://replit.com/@ezzcodeezzlife/WhisperREPLIT#main.py

or

```python
import requests

# Welcome to our Replit Starter!
# You can use our Whisper API to transcribe your audio fast and easy.

# We will select our audio file
file = [('audio_file', ('test1.mp3', open('./test1.mp3', 'rb'), 'audio/mpeg'))]

# Now transcribe the audio and print the text. There is also /detect-language to only detect the language in the audio
url = "https://whisper2.lablab.ai/asr"
print("Transcribing...")
response = requests.request("POST", url, files=file)

# This will return the text and more information like segments & language
print(response.text)

```
Read more about Whisper here: https://lablab.ai/tech/whisper

---

[![Artificial Intelligence Hackathons, tutorials and Boilerplates](https://storage.googleapis.com/lablab-static-eu/images/github/lablab-banner.jpg)](https://lablab.ai)


## Join the LabLab Discord


![Discord Banner 1](https://discordapp.com/api/guilds/877056448956346408/widget.png?style=banner1)  
On lablab discord, we discuss this repo and many other topics related to artificial intelligence! Checkout upcoming [Artificial Intelligence Hackathons](https://lablab.ai) Event


[![Acclerating innovation through acceleration](https://storage.googleapis.com/lablab-static-eu/images/github/nn-group-loggos.jpg)](https://newnative.ai)

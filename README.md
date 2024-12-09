Creating a basic voice assistant like Siri in Python can be done using libraries like SpeechRecognition for recognizing voice commands, pyttsx3 for text-to-speech, and wikipedia for information retrieval. Below is an example Python program that mimics basic Siri-like functionality.

Before running the code, you need to install the following libraries:

pip install SpeechRecognition pyttsx3 wikipedia

How it works:
SpeechRecognition: Captures audio input from the microphone and converts it into text.
pyttsx3: Converts text to speech to provide responses.
Wikipedia: Provides quick information retrieval for Wikipedia-based queries.
webbrowser: Opens YouTube and Google based on commands.
Features:
Greets the user based on the time of day.
Listens for commands like:
"Search Wikipedia for [something]"
"What time is it?"
"Open YouTube"
"Open Google"
"Exit" to stop the program.

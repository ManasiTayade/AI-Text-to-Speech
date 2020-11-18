# AI-Text-to-Speech
***
## Introduction:
Text-to-speech (TTS) is the mechanism by which words are translated into verbal audio form. The program, tool, or software takes an input text from the user and understands the linguistics of the language being used methods of natural language processing and performs logical inference on text. This processed text is moved into the next block where the processing of digital signals is carried out on the processed text. This processed text is eventually transformed using several algorithms and transformations. The process of translating text input into audio data is called synthesis and the output of synthesis is called synthetic speech. Speech Synthesizer has two main block where the text is converted to speech is 1. Natural Language processing and 2. Digital Signal Processing. 
## gTTS in Python:
gTTS (Google Text-to-Speech) is a Python library and CLI tool to interface with Google Translate text-to-speech API. 

***
## Installation of gTTS module:
1. The installation of the gTTS module is simple and can be done using the following command in the command prompt terminal —<br>
   !pip install gTTS

2. We can use gTTS module to convert our typed text into a speech converted output. Open the python file and give it a name of your choice and make sure it ends with the .py format. 
3. IPython.display lets you play audio directly in an IPython notebook.
4. The text variable is a string used to store the user’s input. The text can be replaced by anything of your choice within the quotes. Another alternative can be to use the input statement for the user to type their own desired input each time the program is run.
5. The tts variable is used to perform the Google text-to-speech translation on the user’s input. The output of the converted text is stored in the form of speech in the tts variable.
6. The tts.save function allows us to save the converted speech in a format that allows us to play sounds. I have saved it in a file called 10 and, in a format, called .wav. Other formats like .mp3 format can also be used.
7. Audio provide bindings for the PortAudio library for cross-platform playback of WAV files.

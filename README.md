# Personalised-TODO-with-AI
This is a Basic AI Assistant which is programmed as Todo App to work as a virtual assistant in real life.

Firstly we need to import some packages:
1.Typing module-Introduced since Python 3.5, Python’s typing module attempts to provide a way of hinting types to help static type checkers and 
linters accurately predict errors.

Write this command in your terminal - pip install typing

From typing module we import Mapping (typing.Mapping is an object which defines the __getitem__,__len__,__iter__ magic methods. typing. MutableMapping is an object 
which defines same as Mapping but with __setitem__,__delitem__ magic methods as well.)

2.Neuralintents module - Simple interface for working with intents and chatbots.

Write this command in your terminal - pip install neuralintents

It is maintained by NeuralNine, for this module 1.Set Up a basic assistant
                                                2.Binding functions to request.
                                                3.Sample intents.json file
                                                
For more information go here - https://pypi.org/project/neuralintents/

3.SpeechRecognition 3.8.1 - Library for performing speech recognition, with support for several engines and APIs, online and offline.

Write this command in your terminal - pip install SpeechRecognition 
To quickly try it out, run python -m speech_recognition after installing.

for more in formation visit - https://pypi.org/project/SpeechRecognition/

4.pyttsx3 2.90 - Text to Speech (TTS) library for Python 2 and 3. Works without internet connection or delay. Supports multiple TTS engines, including Sapi5, nsss, and espeak.

Write this command in your command - pip install pyttsx3

Installation
pip install pyttsx3
If you recieve errors such as No module named win32com.client, No module named win32, or No module named win32api, you will need to additionally install pypiwin32.

For more information go to - https://pypi.org/project/pyttsx3/

5.sys (System-specific parameters and functions) - This module provides access to some variables used or maintained by the interpreter and to functions that interact 
strongly with the interpreter.It is always available.


For more information go to - https://docs.python.org/3/library/sys.html

After importing all the required packages Write the code and map the contents to the intents.json file so the main code can fetch details form intrnts.json and 
train the models accordingly.

Happy programming!

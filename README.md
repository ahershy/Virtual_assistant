# Virtual_assistant
Transcribe speech to text, then receive a virtual assistant response to what you say from openai

This application is broken up into two files: main and openai_helper.
The ‘main’ script is used for the voice-to-text API connection. It involves setting up a WebSockets server, filling in all the parameters required for pyaudio, and creating asynchronous functions required for sending and receiving the speech data concurrently between our application and the AssemblyAi’s server.
The openai_helper file is short and is used solely to connect to the open ai “text-davinci-002” engine. This connection is used to receive answers to our questions.

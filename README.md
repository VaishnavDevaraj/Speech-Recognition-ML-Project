This Python project utilizes the SpeechRecognition library to capture and process voice commands. It listens for specific phrases and responds accordingly, providing a basic structure for a voice-activated system. The project can recognize simple commands such as greetings, farewells, and inquiries about well-being.

Installation:-

Prerequisites

Make sure you have Python installed. This project also requires the SpeechRecognition library. You can install it using:

pip install SpeechRecognition

Additionally, you need to install PyAudio to access the microphone:

On Windows:

Download the compatible PyAudio .whl file from here and install it using:

pip install path/to/downloaded/file.whl


On macOS or Linux:

pip install pyaudio


Usage:-

Run the main script to start the voice recognition program:

python your_script_name.py

The program will listen to the microphone and respond to specific voice commands, such as:

Hello: Responds with a greeting message.

Goodbye: Responds with a farewell message and stops the program.

How are you: Responds with a brief message.


Voice Commands:-

The program can recognize and respond to the following commands:

"hello" - Responds with "Hello! How can I help you?"

"goodbye" - Responds with "Goodbye! Have a great day!" and exits the program.

"how are you" - Responds with "I am fine! Hope you're doing good too!"


If the program doesn’t recognize a command, it will ask the user to try again.

Functions:-

capture_voice_input(): Captures audio input from the microphone.

convert_voice_to_text(audio): Converts the captured audio to text using Google's Speech Recognition API.

process_voice_command(text): Processes recognized text to determine if a specific command was issued.

main(): Main loop of the program that continues until the "goodbye" command is received.


Contributing:-

Contributions are welcome! Feel free to submit a pull request or report issues.


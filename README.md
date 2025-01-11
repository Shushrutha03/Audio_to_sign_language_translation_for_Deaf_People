# Audio_to_sign_language_translation_for_Deaf_People

This project translates spoken audio and text into sign language animations, aiming to bridge the communication gap for deaf individuals. The solution uses Python and Tkinter to create an interactive GUI and employs OpenCV for image processing.

**Features**
Audio-to-Sign: Converts recorded audio into sign language animations.
Text-to-Sign: Converts user-entered text into sign animations.
Interactive GUI: Simple interface for easy navigation and interaction.
Customizable Data: Add custom GIFs for specific words or letters.

**How It Works**
*Input Options:*
>Enter text manually in the provided field.
>Use the microphone to record audio, which is converted into text using speech recognition.
*Animation Generation:*
>For each recognized word, the program checks for a corresponding animation (GIF).
>If a word GIF is unavailable, animations for individual letters are displayed.

**Output:**
The animations are displayed in the GUI sequentially as a GIF.

**Prerequisites**
Python 3.x

**Required Libraries:**
Install the necessary libraries using the following command:
pip install numpy opencv-python pillow SpeechRecognition


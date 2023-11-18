# BARD-TTS-ENGLISH-RUSSIAN

Text-to-Speech
This repository contains a Python script that can be used to generate audio recordings of text. The script is based on the Silero TTS model (https://models.silero.ai/models/tts/ru/ru_v3.pt), (https://models.silero.ai/models/tts/ru/ru_v3.pt) which is a Russian language model trained on a large corpus of text and audio.
The script can be used to generate audio recordings of text in both Russian and English. It can also be used to generate audio recordings of text that contains numbers.
To use the script:
 1 Clone the repository.
 2 Install the required dependencies.
 3 Run the script with the following command:
python text_to_speech.py [text] [speaker] [sample_rate]
Where:

* [text] is the text to be spoken.
* [speaker] is the speaker to be used.
* [sample_rate] is the sample rate of the audio recording.

Example:
python text_to_speech.py "This is a test" "baya" 48000

This will generate an audio recording of the text "This is a test" spoken by the speaker "baya" at a sample rate of 48000 Hz.
Additional information:
 • The script is compatible with Python 3.7 or later.
 • The required dependencies can be installed with the following command:
pip install -r requirements.txt

Author:
Bard, a large language model from Google AI

License:
The script is licensed under the MIT License.


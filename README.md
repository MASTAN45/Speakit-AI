Speakit AI
Advanced Speakit AI is an interactive text-to-speech (TTS) and speech-to-text (STT) application built with Python using Tkinter for the GUI, Pyttsx3 for TTS, and various other libraries for added functionality. This application offers several advanced features such as emotion detection from text, speech recognition, text bookmarking, language translation, and a simple chatbot for user interaction.

Features

- Text-to-Speech (TTS): Convert entered text into speech using various voice options.
- Speech-to-Text (STT): Convert spoken words into text using a microphone.
- Emotion Detection: Analyze the sentiment of the entered text and detect emotions (e.g., happy, sad, etc.) using machine learning models.
- Chatbot: Interact with a simple chatbot that responds to basic inputs.
- Language Support: Supports multiple input and output languages for both speech and text (e.g., English, Hindi, Japanese, etc.).
- Audio Saving: Save the generated speech as an audio file (MP3 format).
- Text Bookmarking: Highlight and save specific portions of text for later reference.
- Adjustable Speech Parameters: Control the speech rate and pitch for TTS output.

Requirements

- Python 3.x
- Install required Python libraries:
  - tkinter: GUI framework for building the application interface.
  - pyttsx3: Text-to-speech conversion.
  - speech_recognition: Convert speech to text.
  - gTTS: Google Text-to-Speech for saving audio.
  - pygame: Used for audio playback.
  - transformers: For emotion detection and other NLP tasks.
  - textblob: For text analysis and sentiment detection.
  - torch: For working with machine learning models.

To install the necessary dependencies, run:

```bash
pip install pyttsx3 speechrecognition gtts pygame transformers torch textblob
```

Getting Started

1. Run the Application:
   - Clone this repository or download the script.
   - Run the script in your terminal or preferred Python environment:

   ```bash
   python speakit_ai.py
   ```

2. Interface Overview:
   - Text Entry: Enter the text you want to convert to speech or use for chatbot interactions.
   - Voice Selection: Choose from available voices for TTS.
   - Language Selection: Select input and output languages for speech recognition and synthesis.
   - Speech Rate & Pitch: Adjust the rate and pitch of the speech output.
   - Speech-to-Text: Click the "Speech-to-Text" button to convert spoken words to text.
   - Text-to-Speech: Click the "Text-to-Speech" button to hear the entered text.
   - Save Audio: Save the generated speech to an audio file.
   - Bookmark Text: Highlight and save important text.
   - Chat: Interact with the chatbot for a simple conversation.

3. *Emotion Detection*: The application uses an emotion detection model to analyze the text you input. It will display the detected emotion and the confidence score.

4. *Speech Recognition*: Use the microphone to speak your input. The app will convert your speech to text, which will also be analyzed for emotions.

Example Use Case

1. Enter text into the "Enter Text" field.
2. Choose a voice, language, and adjust the rate/pitch if desired.
3. Click the "Text-to-Speech" button to hear the text spoken aloud.
4. Click "Save Audio" to save the spoken text as an MP3 file.
5. Select a portion of text in the "Highlight Text" area and click "Add Bookmark" to save it for later.
6. Test the "Speech-to-Text" functionality by speaking into the microphone.
7. Interact with the chatbot by typing phrases like "hello" or "how are you".

Known Issues

- The speech recognition may not work well in noisy environments.
- The chatbot is currently a simple rule-based system and does not handle complex queries.
- The emotion detection model might not always provide accurate results for every type of text.

Credits

- *Pyttsx3*: For text-to-speech functionality.
- *SpeechRecognition*: For converting speech to text.
- *gTTS*: For saving audio files.
- *Transformers*: For emotion detection and sentiment analysis.
- *TextBlob*: For basic text processing tasks.

OUTPUT IMAGES

![WhatsApp Image 2024-11-18 at 19 40 30_5a7b7ae1](https://github.com/user-attachments/assets/347eeb9d-1661-4db4-925a-8f33be1e267f)


Contribution

Feel free to fork the project and create pull requests with any improvements or new features! Contributions are always welcome.

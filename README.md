# Speech-to-Speech Translation System
A beginner-friendly Speech-to-Speech Translation System built using Python, Google Colab, and open-source libraries. The system:
1. Takes **speech input** from an uploaded `.mp3` file,
2. Converts it to **text** using Google Speech Recognition,
3. Translates the text to the **target language** using Google Translate,
4. Synthesizes the **translated speech output** using gTTS (Google Text-to-Speech),
5. Plays the result directly in the notebook.

---

## 📁 Project Structure
SpeechToSpeech-Translator/
│
├── SpeechToSpeech_Translator_Colab.ipynb # Main Colab notebook
├── README.md # This file
└── sample_inputs/ # Optional folder for test mp3 files
---

## Features

- Accepts `.mp3` audio input (converted internally to `.wav`)
- Recognizes English speech using Google's Speech Recognition API
- Translates to any language supported by Google Translate (Tamil, Hindi, French, etc.)
- Outputs translated audio using gTTS and plays it in Colab
- Lightweight, simple, and beginner-friendly

---

## Technologies Used

- Python 3.11+
- [Google Colab](https://colab.research.google.com/)
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [googletrans](https://pypi.org/project/googletrans/)
- [gTTS](https://pypi.org/project/gTTS/)
- [pydub](https://pydub.com/) + `ffmpeg` for audio format conversion

---



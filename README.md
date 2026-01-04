# 🎤 Voice Language Translator (Python)

A Python-based voice translator that listens to spoken input in one language,
translates it into another language, and speaks the translated output aloud.

This project works as a **local desktop application** and requires access to
the system microphone and speakers.

---

## 🚀 Features
- Voice input using microphone
- Speech-to-text conversion
- Language translation between multiple languages
- Text-to-speech output of translated text
- Supports a wide range of languages

---

## 🛠️ Technologies & Libraries Used
- Python
- `speech_recognition` – for voice input
- `googletrans` – for language translation
- `gTTS` – Google Text-to-Speech
- `playsound` – for audio playback
- `pyaudio` – microphone access

---

## 🌍 Supported Languages
The program supports many languages such as:

- English (`en`)
- Hindi (`hi`)
- French (`fr`)
- Spanish (`es`)
- German (`de`)
- Japanese (`ja`)
- Korean (`ko`)
- And many more...

At runtime, the program displays a full list of supported language codes.

---

## ⚙️ How the Program Works
1. The user selects:
   - Input language code (language spoken)
   - Output language code (language to translate into)
2. The program listens to the user's voice through the microphone
3. Speech is converted into text
4. The text is translated into the selected output language
5. The translated text is converted into speech and played as audio

---

## 📦 Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/voice-language-translator.git
cd voice-language-translator
```
### 2️⃣ Install Required Libraries
```bash
pip install googletrans==4.0.0-rc1
pip install SpeechRecognition
pip install gTTS
pip install playsound
pip install pyaudio
```

⚠️ Note:
Installing pyaudio may require extra steps depending on your operating system.

3️⃣ Run the Program
```
python voice_translator.py
```
⭐Make sure your microphone is connected and your system volume is on.
⭐The program will prompt you for input and output language codes before listening.

🖥️ Usage
1. Run the program.
2. When prompted, enter the language code you want to speak in.
      Example: en for English, hi for Hindi.
3. Enter the language code you want the translation in.
      Example: fr for French, es for Spanish.
4. Speak clearly into the microphone.
5. The program will:
   - Convert your speech to text
   - Translate the text to the selected language
   - Play the translated text as speech


📝 About the Session
- Each program run is considered a single session.
- During a session:
   - You can speak once, and the program will output the translated audio.
   - If you want multiple translations, restart the program for a new session.
- Supported languages are displayed at the start, so you can select the correct language codes.
- The session relies on an internet connection for Google Translation and Text-to-Speech services.

⚡ Notes & Tips
- Ensure quiet surroundings for better speech recognition accuracy.
- If pyaudio fails to install:
   - On Windows: install the prebuilt wheel from here
   - On Linux: sudo apt-get install portaudio19-dev python3-pyaudio
- googletrans may occasionally fail due to API changes; try updating to the latest release if needed.

```python3 []
THE CODE OF THE LANGUAGES ARE RESPECTIVELY
code   :  language
en : english
hi : hindi
fr : french
...

ENTER THE LANGUAGE CODE IN WHICH YOU WANT TO SPEAK:- en
ENTER THE LANGUAGE CODE IN WHICH YOU WANT TO SPEAK:- hi
SPEAK NOW
Hello, how are you?
Text: Hello, how are you?
Translation: नमस्ते, आप कैसे हैं?
Audio played: hello.mp3
```

💡 Tips for Best Results
- Speak clearly in a quiet environment
- Ensure microphone permissions are allowed
- Restart the program for multiple translations

⚡ Try it Now
1. Clone the repo
2. Install dependencies
3. Run voice_translator.py
4. Speak and enjoy instant voice translation!

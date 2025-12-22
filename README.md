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

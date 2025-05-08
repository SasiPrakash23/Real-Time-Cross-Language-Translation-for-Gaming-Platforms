
# 🎮 Real-Time Cross-Language Translation for Gaming Platforms

**Real-Time Cross-Language Translation for Gaming Platforms** is an AI-powered multilingual assistant designed to enable seamless communication between players in global gaming environments. It offers real-time speech-to-text conversion, translation, and speech synthesis, helping users break language barriers effortlessly.

---

## 🚀 Features

- 🎙️ **Real-Time Speech Recognition**  
  Converts spoken words into accurate transcriptions using Whisper AI.

- 🌍 **Instant Translation**  
  Translates the recognized text into a target language using the DeepL API.

- 🔊 **Text-to-Speech Synthesis**  
  Generates lifelike spoken audio in the target language using VoiceVox (for Japanese).

- 🖥️ **Subtitling Module**  
  Displays translated speech as subtitles on-screen for enhanced comprehension.

- 💻 **Simple GUI Interface**  
  A user-friendly Tkinter-based interface to control the translation workflow.

---

## 🧰 Tech Stack

- **Languages**: Python
- **Frameworks/Libraries**:
  - [`whisper`](https://github.com/openai/whisper) – Real-time speech recognition
  - [`deep_translator`](https://github.com/nidhaloff/deep-translator) – DeepL-based translation
  - [`VoiceVox`](https://voicevox.hiroshiba.jp/) – Japanese text-to-speech
  - `tkinter` – GUI for control panel
- **Tools**:
  - `.env` configuration for secrets and API keys
  - `pyaudio` for real-time audio input/output

---

## 📁 Project Structure

```
Real-Time-Cross-Language-Translation-for-Gaming-Platforms/
├── docs/                   # Documentation and references
├── src/                    # Core application logic
│   ├── voice_translator.py # Main program: speech → translation → speech
│   └── subtitler.py        # Subtitling logic
├── requirements.txt        # Python dependencies
├── .env.sample             # Sample env vars file (rename to .env)
├── LICENSE                 # MIT License
└── README.md               # Project overview (this file)
```

---

## ⚙️ Setup & Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/SasiPrakash23/Real-Time-Cross-Language-Translation-for-Gaming-Platforms.git
   cd Real-Time-Cross-Language-Translation-for-Gaming-Platforms
   ```

2. **Install Dependencies**  
   Make sure Python 3.8+ is installed. Then:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**  
   - Rename `.env.sample` to `.env`.
   - Add your required API keys and configurations:
     ```
     DEEPL_API_KEY=your_deepL_key
     VOICEVOX_ENGINE_URL=http://localhost:50021
     ```

4. **Run the Application**  
   Navigate to the source directory:
   ```bash
   cd src
   python voice_translator.py
   # or
   python subtitler.py
   ```

> 💡 Make sure VoiceVox engine is running locally if you're using Japanese TTS.

---

## 🧪 Usage Scenarios

- 🧠 **Language Learning** – Practice foreign pronunciation and listening.
- 🎮 **Multiplayer Gaming** – Communicate with international players.
- 💼 **Virtual Collaboration** – Translate conversations in cross-language meetings.
- 📺 **Watching Foreign Content** – Get subtitles and speech in your native language.

---

## 📝 Notes

- **Voicevox Setup**: Follow [this guide](https://github.com/VOICEVOX/voicevox_engine) to install and run the local TTS engine.
- **Performance**: Depends on your hardware and mic quality.
- **Customizable**: Easily add support for more languages or TTS/translation APIs.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> **Empowering cross-lingual gaming conversations, one word at a time.**

# 🌐 Language Leap

**Language Leap** is an AI-powered multilingual assistant designed to bridge communication gaps by providing real-time speech translation and transcription. Leveraging cutting-edge technologies, it facilitates seamless conversations across different languages, making it ideal for global collaboration, gaming, and learning environments.

---

## 🚀 Features

- 🎙️ **Real-Time Speech Recognition**: Converts spoken language into text using advanced models.
- 🌍 **Instant Translation**: Translates recognized text into the target language efficiently.
- 🔊 **Text-to-Speech Synthesis**: Generates natural-sounding speech in the desired language.
- 🖥️ **Subtitling**: Displays translated text as subtitles for better understanding.
- 🛠️ **Modular Architecture**: Easily extendable to support additional languages and services.

---

## 🧰 Tech Stack

- **Programming Languages**: Python, Jupyter Notebook
- **AI Models**:
  - [WhisperAI](https://openai.com/research/whisper): For speech recognition
  - [Voicevox](https://voicevox.hiroshiba.jp/): For Japanese text-to-speech synthesis
  - [DeepL API](https://www.deepl.com/pro-api): For text translation
- **Containerization**: Docker, Docker Compose
- **Others**: Tkinter for GUI, Ngrok for tunneling

---

## 📁 Project Structure

```
language-leap/
├── docs/                   # Documentation and resources
├── src/                    # Source code
│   ├── voice_translator.py # Handles speech recognition and translation
│   └── subtitler.py        # Manages audio subtitling
├── .env.sample             # Sample environment variables
├── docker-compose.yml      # Docker configuration
├── requirements.txt        # Python dependencies
└── README.md               # Project overview
```

---

## ⚙️ Setup & Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/RanjithKannan03/language-leap.git
   cd language-leap
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**:
   - Rename `.env.sample` to `.env`.
   - Populate the `.env` file with your API keys and configurations.

4. **Run Docker Containers**:
   Start the necessary services using Docker Compose:
   ```bash
   docker-compose up -d
   ```

5. **Execute the Application**:
   Navigate to the `src` directory and run the desired module:
   ```bash
   python voice_translator.py
   # or
   python subtitler.py
   ```

---

## 🧪 Usage Scenarios

- **Language Learning**: Practice pronunciation and comprehension in real-time.
- **Gaming**: Communicate with international players seamlessly.
- **Remote Collaboration**: Break language barriers in virtual meetings.
- **Content Consumption**: Watch foreign media with live translations.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

*Empowering conversations beyond boundaries.*

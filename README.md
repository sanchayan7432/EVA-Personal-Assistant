# EVA-Personal-Assistant
It is an exe file which opens in cmd and can run in background, no trigger voice, only give tasks


# 🤖 EVA - Secure Voice Assistant using Gemini & OpenAI

EVA is an intelligent, leak-proof voice assistant powered by Google's Gemini and OpenAI APIs. It can understand speech input, respond with synthesized speech, generate images, open websites, and even play YouTube videos—all while remaining secure against prompt injection and leakage attacks.

## 🎯 Features

- 🎙️ Voice recognition (English and Bengali)
- 🧠 Conversational AI using Gemini & OpenAI
- 🖼️ Image generation via DALL·E
- 🔗 Web and YouTube integration
- 🔐 Immunity to prompt leakage and injection attacks
- 🗣️ Female voice response using `pyttsx3`

## 🛠️ Requirements

- Python 3.10+
- `google-generativeai`
- `openai`
- `pyttsx3`
- `speechrecognition`
- `yt-dlp`
- `pyaudio` (for microphone access)
- `re`, `webbrowser`, `os` (standard libraries)

Install dependencies:
```bash
pip install -r requirements.txt

🚀 Running the Assistant
python eva.py   ## main python file
Then speak your query (e.g., "Play Shape of You on YouTube", "Generate image of a futuristic city", "What is AI?").

🔒 Security
EVA is built with hardened system and role prompts to resist prompt leakage, injection, and indirect inference attacks.

🧾 License
MIT License

👨‍💻 Author
Developed by Sanchayan Ghosh
```

##You can easily install the Eva.exe file from this link : "https://drive.google.com/file/d/1a3ORwDGuVGfh_LpTi7-0ypqcw4VDGn2z/view?usp=sharing"

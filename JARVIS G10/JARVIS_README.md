<h1 align="center">🤖 J.A.R.V.I.S — G10</h1>

<p align="center">
  <b>Just A Rather Very Intelligent System</b><br/>
  A Python-based voice assistant with face recognition authentication
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-Face%20Recognition-green?logo=opencv"/>
  <img src="https://img.shields.io/badge/Speech-Recognition-orange"/>
  <img src="https://img.shields.io/badge/License-MIT-lightgrey"/>
</p>

---

## ✨ Features

| Category | Capability |
|----------|-----------|
| 🔐 Authentication | Dynamic face recognition login (OpenCV) |
| 🗣️ Voice I/O | Speech recognition + TTS (pyttsx3) |
| 📰 News | Live headlines via News API |
| 🌤️ Weather | Temperature, humidity, wind speed by location |
| 📧 Email | Send emails by voice command |
| 🧠 Knowledge | Wikipedia-powered Q&A with spell correction |
| 🎵 Media | YouTube search + video downloader |
| 📝 Tasks | Persistent to-do list |
| 🗺️ Maps | Google Maps search by voice |
| 💻 System | CPU usage, battery status, screenshots |
| 😄 Fun | Jokes (pyjokes), voice persona switch (JARVIS ↔ FRIDAY) |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Webcam (for face recognition)
- Microphone

### Install

```bash
git clone https://github.com/kaustubh-x/JARVIS_G10.git
cd JARVIS_G10
pip install -r requirements.txt
```

> **Windows PyAudio:** Download the `.whl` from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio) and install manually before running `pip install -r requirements.txt`.

> **Ubuntu/Debian:**
> ```bash
> sudo apt-get install espeak portaudio19-dev
> ```

### Run

```bash
python helpers.py
```

---

## 🗂️ Project Structure

```
JARVIS_G10/
├── helpers.py          # Core assistant logic & voice commands
├── news.py             # News API integration
├── OCR.py              # Optical character recognition module
├── amazon.py           # Amazon search helper
├── Face-Recognition/
│   ├── Sample generator.py   # Capture face samples
│   ├── Model Trainer.py      # Train the recognition model
│   └── Face recognition.py  # Auth gate
├── data.json           # User config & contacts
├── requirements.txt
└── images/             # UI assets
```

---

## 🔧 Tech Stack

- **Language:** Python 3.10
- **CV/ML:** OpenCV (face detection & recognition)
- **Voice:** SpeechRecognition, pyttsx3, PyAudio
- **APIs:** OpenWeatherMap, News API, Wikipedia
- **Automation:** PyAutoGUI, psutil

---


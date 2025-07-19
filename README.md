# ValuEnable Voice Assistant

🎙️ A multilingual voice-based insurance assistant built using Flask, Speech AI, NLP, and Google Translation.

---

## 💡 Overview

This project allows users to **speak** insurance-related queries and receive **real-time spoken responses** in **English, Hindi, Telugu, Tamil, or Kannada**.

The assistant listens, translates, understands via NLP, and replies with relevant information from a pre-defined FAQ database.

---

## 🚀 Features

- 🎙️ Voice input (Speech Recognition)
- 🌐 Multi-language support (En, Hi, Te, Ta, Kn)
- 🧠 Semantic + fuzzy FAQ matching (spaCy + FuzzyWuzzy)
- 🔊 Voice output (Google Text-to-Speech)
- ⚡ Response caching for faster replies
- 🧾 Simple web interface with Flask backend

---

## 📂 Files Included

| File Name         | Description |
|------------------|-------------|
| `app.py`          | Flask server routes (`/` and `/ask`) |
| `chatbot (2).py`  | Main bot logic (audio input, NLP, TTS) |
| `faq_data.json`   | Static FAQ-based knowledge base |
| `chatbot.html`    | Frontend UI |
| `requirements.txt`| All required Python libraries |

---

## 🔧 Installation & Setup

> Prerequisites: Python 3.8+ and pip installed

```bash
git clone https://github.com/Devi-cloud/valuenable-voice-assistant
cd valuenable-voice-assistant
pip install -r requirements.txt
python -m spacy download en_core_web_md
python app.py


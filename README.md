# 🤖 Jarvis – Voice Controlled AI Assistant

> A Python-based voice assistant that listens, thinks, and responds — powered by AI.

**Jarvis** is a desktop voice assistant built using Python that listens for a wake word, understands voice commands, performs predefined actions, and intelligently falls back to **AI-generated responses** when needed.

This project demonstrates how **speech recognition, automation, and AI** can work together in a real-world application.

---

## 🚀 What Jarvis Can Do

- Listen for a **wake word**
- Accept and process **voice commands**
- Speak responses using **text-to-speech**
- Open websites like Google, YouTube, and LinkedIn
- Play songs from a custom music library
- Fetch and read out news headlines
- Answer general questions using **OpenAI**

---

## 🧠 How It Works (In Simple Terms)

1. Jarvis listens continuously for a wake word  
2. After activation, it listens for a command  
3. If the command is known → it performs the action  
4. If unknown → it asks AI and speaks the response  

This combines **rule-based logic + AI intelligence**.

---

## 🛠 Tech Stack

- Python  
- Speech Recognition  
- Text-to-Speech (pyttsx3)  
- Web Automation  
- OpenAI API  
- NewsAPI  
- Custom Music Library  

---

## ▶️ How to Run Jarvis

1. Install the required dependencies:
   ```bash
   pip install SpeechRecognition pyttsx3 requests openai
2. Ensure you have a working microphone connected to your system.
3. Add your API keys:
    -Set your OpenAI API key inside the script (or via environment variables).
    -Add your NewsAPI key to the NEWS_API_KEY variable.
4. Make sure your musicLibrary file is present and properly configured with song names and URLs.
5. Run the Jarvis script:
   ```bash
   python jarvis.py
6. Speak the wake word “hello” when prompted, then give your command.

Jarvis will listen, process your command, and respond using voice output.

## 🎯 Who Is This For?

- Python beginners building real projects  
- Students learning voice automation  
- Developers exploring AI assistants  
- Anyone curious about how Alexa-like systems work  

---

## 🌱 What You’ll Learn

- Voice input handling in Python  
- Text-to-speech output  
- API integration  
- Command-based logic design  
- AI fallback systems  

---

## ⚠️ Note

This is a **learning-focused project**, not a production-ready assistant.  
Designed to help you understand how voice assistants work internally.

---

**Build it. Break it. Improve it.**  
Happy coding 🤖🚀

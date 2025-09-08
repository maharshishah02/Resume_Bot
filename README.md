# 💼 Resume Bot — Maharshi Shah

An interactive **Gradio chatbot** that acts as my AI assistant.  
You can ask it questions about my **background, skills, experience, and projects**.  
It uses **Google Gemini API** for responses, **Pushover API** for notifications, and loads data from my resume & summary files.

---

## ✨ Features
- 📄 Reads my resume (`resume.pdf`) and summary (`summary.txt`) for context  
- 🤖 Answers career-related questions using **Gemini**  
- 🔔 Sends push notifications via **Pushover API**  
- 📬 Records user details and unanswered questions  
- 🌐 Can be deployed on **Hugging Face Spaces** for public access  
- 🎨 User-friendly **Gradio Chat Interface** with title, description, and example prompts  

---

## 📸 Screenshot
![Chatbot Screenshot](assets/chatbot.png)

---

## 🛠️ Tech Stack
- [Python](https://www.python.org/)  
- [Gradio](https://www.gradio.app/) — Chat UI  
- [Google Gemini API](https://ai.google.dev/) — AI responses  
- [Pushover](https://pushover.net/) — Notifications  
- [python-dotenv](https://pypi.org/project/python-dotenv/) — Secret management  
- [PyPDF](https://pypi.org/project/pypdf/) — Resume parsing  
- [Requests](https://pypi.org/project/requests/) — API calls  

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/maharshishah02/Resume_Bot.git
cd Resume_Bot
```
### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Add secrets in .env
Create a .env file in the root folder:

env
```
GEMINI_API_KEY=your-gemini-key-here
PUSHOVER_TOKEN=your-pushover-token-here
PUSHOVER_USER=your-pushover-user-key-here
```

### 5. Run locally
```bash
python app.py
```
You’ll get a local Gradio link like:
```
http://127.0.0.1:7860
```

🚀 Check it out on Hugging Face space
```bash
https://huggingface.co/spaces/maharshi02/resume_bot
```

🤝 Contributing
This project is for showcasing my portfolio bot. If you’d like to adapt it for yourself, feel free to fork the repo.

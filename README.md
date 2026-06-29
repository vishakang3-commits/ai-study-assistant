# 📚 AI Study Assistant with Automated Study Tracking

An AI-powered study assistant that helps students revise more efficiently by summarizing study notes, generating revision questions, providing an AI-powered chat assistant, and automatically tracking study progress through workflow automation.

> **Note:** Sensitive credentials (API keys, webhook URLs, and authentication tokens) have been removed from this repository for security reasons.

> **Project Context:** This project was developed during my Generative AI Internship at **Novus Solutions**, where I gained hands-on experience in AI integration, Flask development, and workflow automation using Make.com.

## 🚀 Features

- 📝 AI-powered note summarization
- ❓ Automatic revision question generation
- 💬 AI chatbot for answering questions from study notes
- 📊 Automatic study progress tracking using Google Sheets
- ☁️ Google Drive integration for storing study data
- 📧 Gmail notifications through workflow automation
- 🔄 Make.com automation for seamless task execution

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Backend | Python, Flask |
| Frontend | HTML, CSS, JavaScript |
| AI | OpenRouter API, Google Gemma 4 |
| Automation | Make.com |
| Storage | Google Sheets, Google Drive |
| Notifications | Gmail |
| Deployment | Google Colab, ngrok |
| Version Control | Git & GitHub |

---

## 🏗️ System Architecture

```text
                Student Notes
                      │
                      ▼
              Flask Backend (Python)
                      │
                      ▼
      OpenRouter API (Google Gemma 4)
                      │
         ┌────────────┼────────────┐
         ▼            ▼            ▼
     Summary      Questions      AI Chat
                      │
                      ▼
           Make.com Workflow Automation
                      │
         ┌────────────┼────────────┐
         ▼            ▼            ▼
 Google Sheets   Google Drive    Gmail
```

---

## 📂 Project Structure

```text
AI-Study-Assistant/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── screenshots/
│   ├── home.png
│   ├── summary.png
│   ├── questions.png
│   ├── chat.png
│   └── automation.png
│
└── LICENSE
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/ai-study-assistant.git
```

### Navigate to the project

```bash
cd ai-study-assistant
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

The application will start locally and can also be exposed using **ngrok** if required.

---

## 📸 Screenshots

### Home Page
<img width="1918" height="960" alt="image" src="https://github.com/user-attachments/assets/3f0edf72-e134-48fd-879c-db7d1f231512" />



### AI Chat
<img width="1861" height="1005" alt="image" src="https://github.com/user-attachments/assets/5248ad5a-3c14-4fab-b341-bd7b9d3740bf" />

























## 🎯 Future Improvements

- 🎤 Voice-to-notes input
- 📱 Mobile application
- 🌍 Multi-language support
- ☁️ Cloud deployment (Render, Railway, AWS)
- 🔐 User authentication
- 🧠 Retrieval-Augmented Generation (RAG)
- 📈 Personalized learning dashboard

---

## 📖 Learning Outcomes

Through this project, I gained practical experience in:

- Building AI-powered web applications using Flask
- Integrating LLMs through OpenRouter API
- Implementing workflow automation using Make.com
- Connecting Google Sheets, Google Drive, and Gmail APIs
- Developing interactive AI-based learning tools
- Deploying applications using Google Colab and ngrok

---
## 👨‍💻 Author

**G Vishakan**

B.Tech Computer Science Engineering  
VIT-AP University

**Generative AI Intern – Novus Solutions**

**Interests:** Artificial Intelligence • Generative AI • Automation • Full-Stack Development

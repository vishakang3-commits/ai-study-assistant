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
- ❓ Revision Question Generator
<img width="922" height="997" alt="Screenshot 2026-06-29 104418" src="https://github.com/user-attachments/assets/b981465d-c764-4978-9b4f-81ef91c3fcf0" />
- 💬 AI Chat Assistant
<img width="1877" height="1013" alt="Screenshot 2026-06-29 104441" src="https://github.com/user-attachments/assets/80600bb9-5340-4b67-b297-3ff159bd7f9d" />
- 📊 Google drive
<img width="1907" height="1032" alt="image" src="https://github.com/user-attachments/assets/f25723ff-ba85-4783-8cc9-1cc37a3a7363" />

- 📧 Gmail Notification<img width="1883" height="992" alt="image" src="https://github.com/user-attachments/assets/01a54677-94b2-417b-9e6c-e6d4e701ab44" />

  - 
  -   📊 Google Sheets Study Tracking
      <img width="1918" height="1016" alt="image" src="https://github.com/user-attachments/assets/05d477c8-c399-4075-8995-2df11b33e2ff" />

     - 
- 🔄 Make.com Workflow
- <img width="1918" height="983" alt="image" src="https://github.com/user-attachments/assets/b97eb181-58bb-4830-af7c-d92e296af67a" />




























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

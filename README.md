# AI Chatbot with Gemini API Integration 🤖

A responsive AI chatbot web application built with a sleek interface, supporting real-time messaging, file uploads, and emoji reactions. Powered by Google's Gemini API, it delivers dynamic, context-aware responses to user interactions.

## ⚡ Features

- 💬 **Interactive chat UI** – Send and receive messages seamlessly.
- 📎 **File upload support** – Attach PDFs, images, and other files.
- 😀 **Emoji reactions** – Express yourself with emojis.
- 🔗 **Gemini API integration** – Generates intelligent AI responses.
- 📱 **Responsive design** – Optimized for both desktop and mobile.
- 🌙 **Theme support** – Light and dark mode toggle (optional).

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (vanilla or framework of your choice)
- **Backend**: Node.js / Express or Flask / FastAPI
- **AI Service**: Google Gemini generative language model API
- **Version Control**: Git & GitHub

## 📁 Project Structure

/
├── frontend/ # Client-side UI code
│ ├── index.html
│ ├── styles.css
│ ├── script.js
│ └── assets/
├── backend/ # Server-side logic
│ ├── server.js (or app.py)
│ ├── routes/
│ ├── controllers/
│ └── .env # environment variables (not committed)
├── README.md
├── .gitignore
└── package.json / requirements.txt

## 🚀 Getting Started

### Setup and Run Locally

1. **Clone the repo**  
   git clone https://github.com/guptavaibhav654/ai-chatbot.git
   cd ai-chatbot

Configure environment variables
Create a .env in the backend/ folder:

GEMINI_API_KEY=your_api_key_here
(Replace with your actual Gemini API key)

Start the server

Open frontend/index.html in your browser, or serve via a static server.

🔗 Demo
<img width="688" height="688" alt="project 6" src="https://github.com/user-attachments/assets/01ac04ab-1ecc-42af-b3f1-72960979fa58" />

✨ Improvements
Add chat history with persistent storage (e.g., MongoDB or Firebase).

Enhance messages with Markdown support or rich media.

Integrate user authentication for personalized sessions.

📝 License
This project is licensed under the MIT License.

📫 Contact
GitHub: @guptavaibhav654

Email: work.vaibhav06@gmail.com

🙏 Acknowledgments
Thanks to the Gemini API team for NLP support.

Inspired by many open-source chatbot projects and UI libraries.

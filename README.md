AI Mentor Chatbot

🚀 Live Demo:
👉 https://ai-mentor-chatbot.onrender.com/

An AI-powered mentor chatbot built using Flask, OpenAI GPT models, and Server-Sent Events (SSE) for real-time streaming responses.
This chatbot provides career guidance, interview preparation, technical explanations, academic help, and general Q&A with a modern, clean UI.

⭐ Features

🧠 AI-powered chatbot using OpenAI GPT models

⚡ Real-time streaming responses (like ChatGPT) using SSE

🌐 Flask backend + REST API

🎨 Modern responsive frontend with HTML, CSS & JS

🔥 Error handling, loading animation, clean architecture

🚀 Deployed on Render

🛠️ Tech Stack
Backend

Python

Flask

OpenAI API

SSE (Server-Sent Events)

Frontend

HTML

CSS (Flexbox + responsive)

JavaScript (Vanilla JS)

Deployment

Render (Web Service)

📁 Project Structure
ai-mentor-chatbot/
│── static/
│   ├── style.css
│   ├── script.js
│── templates/
│   ├── index.html
│── app.py
│── requirements.txt
│── README.md

⚙️ Installation & Setup (Local Development)
1. Clone the Repository
git clone https://github.com/your-username/ai-mentor-chatbot.git
cd ai-mentor-chatbot

2. Create Virtual Environment
python -m venv venv
venv/Scripts/activate     # For Windows
source venv/bin/activate  # For Mac/Linux

3. Install Dependencies
pip install -r requirements.txt

4. Add Your OpenAI API Key

Create a .env file:

OPENAI_API_KEY=your_api_key_here

5. Run the App
python app.py


App will run on:

http://127.0.0.1:5000/

🚀 Deployment (Render)

Push project to GitHub

Create a New Web Service on Render

Select your GitHub repo

Build command:

pip install -r requirements.txt


Start command:

gunicorn app:app


Add environment variable:

OPENAI_API_KEY


✔️ Done — your app will deploy automatically.

📸 Screenshots

(Add when available)

🤝 Contributing

Feel free to open issues or pull requests to improve the project.

📜 License

This project is licensed under the MIT License.

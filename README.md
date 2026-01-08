#chatbot model
# 🤖 Chatbot with Persistent Memory

A simple Python-based chatbot project that stores **chat history persistently** using SQLite. This repository is designed for local experimentation and can be easily extended into an API or MCP-compatible service.

---

## 📂 Project Structure

```
project-root/
│── .env                 # Environment variables (API keys, config)
│── chatbot.py           # Main chatbot logic
│── chat_history.db      # SQLite database for chat history
│── requirements.txt     # Python dependencies
│── README.md            # Project documentation
│
└── .git/                # Git repository metadata
```

---

## 🚀 Features

* Python chatbot implementation
* Persistent chat history using **SQLite**
* Environment-based configuration with `.env`
* Lightweight and easy to understand
* Git version controlled

---

## 🛠️ Setup Instructions

### 1️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv .venv
.venv\Scripts\activate   # Windows
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```env
API_KEY=your_api_key_here
MODEL_NAME=your_model_name
```

---

## ▶️ Running the Chatbot

Start the chatbot locally:

```bash
python chatbot.py
```

---

## 🗄️ Chat History Database

### `chat_history.db`

* Stores conversation messages
* Enables memory across chatbot sessions
* SQLite-based (no external DB required)

> ⚠️ For production systems, consider migrating to PostgreSQL or MySQL.

---

## 🧪 Development Notes

* Keep secrets out of source code
* Use `.env` for configuration
* Add logging for better debugging

---

## 📌 Possible Enhancements

* Add **multiple model support**
* Convert to **FastAPI** REST service
* Expose chatbot as an **MCP (Model Context Protocol) server**
* Add user authentication
* Add conversation analytics

---

## 📄 License

This project is open-source and intended for learning and experimentation.

---

💡 *If you want, I can:*

* Convert this into an **MCP server**
* Add **multi-model routing**
* Add **Docker support**
* Refactor into clean architecture


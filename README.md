# ChatGPT Clone with Gemini AI

A simple ChatGPT-style web application built with **Python Flask** and **Google Gemini API**. The application provides a clean chat interface where users can send messages, maintain conversations, switch between previous chats, and store conversations locally.

### Features

- Chat with Google Gemini AI
- Maintains conversation context
- Create and switch between chats
- Delete conversations
- Local JSON-based chat storage
- Code block formatting
- Simple responsive interface
- Flask backend with HTML, CSS and JavaScript frontend

### Technologies Used

- Python
- Flask
- Google Gemini API
- OpenAI Python SDK
- HTML
- JavaScript
- Tailwind CSS
- JSON

### Project Structure

```text
chatgpt-clone-gemini/
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── js/
│       └── script.js
├── data/
│   └── conversations.json
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

### Setup

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install the required packages using `pip install -r requirements.txt`.
4. Create a `.env` file using `.env.example`.
5. Add your own Gemini API key.
6. Run the application using `python app.py`.
7. Open `http://127.0.0.1:5001` in your browser.

**Note:** Never upload your `.env` file or expose your Gemini API key publicly.

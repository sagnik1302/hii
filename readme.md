# ChatGPT Clone

A clone of OpenAI's ChatGPT using HTML, Tailwind CSS, JavaScript for the frontend, and Python with an API for the backend. This project demonstrates how to build a basic chatbot interface that communicates with a backend API to generate responses similar to ChatGPT.

## Features
- **Real-time Chat:** Communicate with the chatbot and receive real-time responses.

- **API-powered Backend:** Uses Python with an API to handle chat requests and generate responses.

## Tech Stack

### Frontend:

- HTML
- Tailwind CSS
- JavaScript

### Backend:

- Python
- Flask (or FastAPI)
- OpenAI API (or other AI API)
- MongoDB

## Getting Started

### Prerequisites
Ensure you have the following tools installed on your system:

Python (>=3.7)
Node.js (for managing JavaScript dependencies)

### Installation
**1.Clone the Repository (from the forked repo):**
```bash
git clone https://github.com/techiuv/chatgpt-clone.git
cd chatgpt-clone
```

**2.Backend Setup (Python):**
- Create and activate a virtual environment:
  ```bash
  python3 -m venv venv
  source venv/bin/activate  # Linux/Mac
  # On Windows:
  # venv\Scripts\activate
  ```

- Install required Python dependencies:
  ```bash
  pip install -r requirements.txt
  ```
**3.Frontend Setup (Tailwind & JavaScript):**
- Install Tailwind CSS and JavaScript dependencies:
  ```bash
  npm install
  ```


**4.Set Up Environment Variables:** Create a `.env` file in the root directory and add your API keys:
```bash
OPENAI_API_KEY=your_openai_api_key
```

## Running the Application

**1.Start the Backend:** Run the Python Flask (or FastAPI) server:
```bash
python app.py
```
This will start the backend API at `http://localhost:5000`.

**2.Serve the Frontend:** You can serve the HTML and JavaScript files with a local server or simply open `index.html` in your browser.


## Usage
- Open the application in your browser at `http://localhost:5000`.
- Type a message in the chat input field and press enter to communicate with the chatbot.
- The chatbot will respond using the AI-powered backend.

**Forked from [codeWithHarry](https://github.com/codeWithHarry)**

# Rule-Based Chatbot 🤖

A simple rule-based chatbot built with Python and Flask.

## What it does
- Accepts user messages through a web interface
- Processes messages using Python if-else logic
- Returns predefined responses based on keywords
- Deployed as a web app using Flask

## Tech Stack
- **Python** — core logic using if-else rules
- **Flask** — web framework to handle requests
- **HTML/CSS** — frontend interface

## How it Works
1. User types a message on the webpage
2. Message sent to Flask backend via POST request
3. `get_reply()` function matches keywords and returns response
4. Response displayed back to user

## Project Structure

├── app.py          # Flask server and routes
├── logic.py        # Rule-based reply logic
├── templates/
│   └── index.html  # Frontend chat interface
└── requirements.txt



## Run Locally
```bash
pip install -r requirements.txt
python app.py
```

## What I Learned
- How Flask handles HTTP requests
- REST API basics (POST, JSON)
- Deploying Python apps on Render

## Next Step
This project evolved into an AI-powered chatbot using 
Google Gemini API and Streamlit — check that repo too!

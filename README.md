
# Chatbot Using Flask

A simple **AI chatbot** built with **Python** and **Flask**. The bot can answer greetings, exam-related questions, project guidance, and provide motivational responses.

## Features
- Web-based chatbot interface  
- Responds to greetings, study questions, project help, and motivational prompts  
- Easy to extend with NLP or AI models  

## Installation
```bash
git clone https://github.com/HarithaNetha8/chatbot-using-flask.git
cd chatbot-using-flask
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install flask werkzeug
````

## Run

```bash
python app.py
```

Then open `http://127.0.0.1:5000/` in your browser.

## API

* **GET /chat?msg=your_message**
  Returns JSON: `{"response": "Chatbot reply here"}`

## Customize

* Add more patterns and responses in `chatbot_response()`
* Integrate NLP/ML models for smarter replies
* Deploy on **Heroku**, **Railway**, or **PythonAnywhere**

## License

Open-source and free to use.

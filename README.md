# Basic LangChain Chat Application

This is a simple Python application that uses LangChain and OpenAI's GPT model.

## Features
- Loads the API key from a `.env` file
- Uses `ChatOpenAI`
- Sends a prompt to the model
- Prints the model's response

## Installation

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

Run the application:

```bash
python app.py
```
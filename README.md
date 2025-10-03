# Streamlit Generative AI ChatBot

This project is a simple, fast chatbot application built with Python, LangChain, and Streamlit. It uses Groq's hosted LLaMA 3.3 70B Versatile model for generating responses via the LangChain integration.

Environment variables are managed securely through a `.env` file (excluded from version control). A sample `env_template.txt` is included for setup reference.

---
## Live Demo

The chatbot is deployed on Streamlit Cloud:
https://sl-genai-chatbot.streamlit.app/
## Features

- Uses Groq's LLaMA 3.3 70B Versatile model via LangChain
- Chat history is preserved using Streamlit `session_state`
- Built with a minimal and responsive Streamlit UI
- Environment variables are managed with `python-dotenv`
- Easy to run locally or extend for deployment

---
## How It Works

1. The app loads environment variables using `load_dotenv()`
2. Streamlit renders a chat interface with history preserved using `session_state`
3. User input and prior messages are passed to Groq's LLaMA 3 model using LangChain
4. The assistant’s response is displayed and appended to the session state

TRY IT OUT! 

---

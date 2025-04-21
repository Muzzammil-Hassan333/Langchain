# Langchain
📦 Langchain – LLM Chatbot with OpenAI & Ollama
This repository demonstrates how to build an interactive chatbot using LangChain, Streamlit, and two different LLM backends: OpenAI (gpt-3.5-turbo) and Ollama (LLaMA 2).

🚀 Features
🔗 LangChain-powered chains for prompt handling and output parsing

💬 Streamlit UI for a simple web-based chatbot

🤖 Switch between OpenAI's GPT-3.5 Turbo and local Ollama models (like LLaMA 2)

📊 Built-in support for LangSmith tracing

🔐 Environment variables via .env for API key management

📁 Project Structure
app.py — Chatbot using OpenAI’s gpt-3.5-turbo

locallama.py — Chatbot using local Ollama model (llama2)

.env — Store your API keys (OPENAI_API_KEY, LANGCHAIN_API_KEY)

📦 Requirements
Python 3.10+

langchain

langchain-openai

langchain-community

streamlit

python-dotenv

(Optional) Ollama for local model support

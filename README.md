# Gemini-pro-LLM-Chatbot
This repository is about building a chatbot using Google's Gemini-Pro with streamlit.
# 💬 Gemini Pro Chatbot using Streamlit
# Gemini‑Pro Streamlit Chatbot 🤖

This project is a **chatbot web application** built using **Google Gemini Pro API** and **Streamlit**. It allows users to interact with a powerful AI model through a simple chat interface built entirely with Python.
A sleek, interactive chatbot powered by **Google’s Gemini‑Pro** model, built using **Streamlit**.

---

## 🌟 What is Streamlit?
## 🚀 Features

[Streamlit](https://streamlit.io/) is an open-source Python library that helps you create **interactive web apps** easily — without writing any HTML, CSS, or JavaScript.
- ✅ Live chat interface in the browser via `Streamlit`
- ✅ Powered by Gemini‑Pro using the `google-generativeai` Python SDK
- ✅ Session‑based chat history and state management
- ✅ Easily deployable locally or on cloud platforms (e.g., Hugging Face Spaces)

In this project, Streamlit is used to:
---

## 🧰 Tech Stack

| Component               | Purpose                                     |
|------------------------|----------------------------------------------|
| `streamlit`            | Front-end UI framework for web applications |
| `google-generativeai` | Gemini‑Pro API client                      |

---

- Create a chat-like interface.
- Take user input (questions).
- Show AI responses in chat format.
- Maintain chat history using session state.
## 📂 Repository Structure

📌 Example:
```python
import streamlit as st
st.title("Gemini Chatbot")
prompt = st.chat_input("Ask something")
st.chat_message("user").write(prompt)
<pre> Gemini‑pro‑Streamlit‑Chatbot
  ├── main.py # Streamlit app entry point 
  ├── .env # Environment file (not committed) 
  ├── requirements.txt # Project dependencies 
  └── README.md # You are here! </pre>

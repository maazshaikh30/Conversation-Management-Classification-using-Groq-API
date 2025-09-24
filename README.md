# Conversation-Management-Classification-using-Groq-API
# Conversation Management & Classification using Groq API

## Overview
This repository contains a Google Colab notebook that demonstrates:

1. **Conversation Management with Summarization**  
   - Maintains running chat history between user and assistant.
   - Performs **periodic summarization** after every k-th conversation run.
   - Supports truncation by **number of turns, character limit, or word limit**.
   - Stores summarized conversation in a compact form.

2. **JSON Schema Classification & Information Extraction**  
   - Extracts structured information from chat messages (name, email, phone, location, age).  
   - Uses **OpenAI-compatible function calling** via Groq API.  
   - Validates parsed data against a JSON schema.

---

## Notebook
The main notebook is:  
**`Conversation_Management_Groq_API.ipynb`**  

### Features
- Demonstrates **conversation history management** with sample user messages.
- Shows **k-th run summarization** with retained recent messages.
- Implements **structured extraction** for multiple sample chats.
- Performs **validation** of extracted data against a JSON schema.

---

## Requirements
- Python 3.x
- `requests` library
- Groq API Key (set in the notebook as `GROQ_API_KEY`)

---

## How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/).  
2. Install dependencies (if not already installed):
   ```python
   !pip install requests

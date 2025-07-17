# 🤖 langchain-agent

> This project is developed in collaboration with [Mahmoud Touil](https://github.com/MahmoudTouil25) and [Malek Esseyah](https://github.com/MalekEssayeh).


A Django-based project that integrates a LangChain agent for intelligent web scraping and data reasoning tasks. Includes a Jupyter notebook for prototyping and experimentation.

---

## 🚀 Features

- LangChain agent powered by Gemini
- Web scraping tools and logic
- Django backend for future API integration
- Jupyter notebooks for agent development
- Virtual environment support

---

## 📁 Structure

langchain_agent/
├── langchain_agent/ # Django project

├── scraper/ # Django app

├── notebooks/ # Jupyter notebooks

├── manage.py

├── requirements.txt

├── .gitignore

└── README.md

## 🛠️ Setup

1. Create a virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\Activate

2. Install dependencies:
    pip install -r requirements.txt

3. Run the server:
     ```bash
     python manage.py runserver

4. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
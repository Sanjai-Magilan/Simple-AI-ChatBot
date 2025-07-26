🤖 Simple AI Chatbot

A lightweight AI chatbot built with FastAPI and integrated with Google's Gemini 1.5 API. This project features a clean API interface tested via Swagger UI, powered by Uvicorn, and organized using Poetry for modern Python project management.

Ideal for beginners exploring AI APIs, FastAPI, or looking to understand chatbot backends.

INSTALL DEPENDENCIS through your console

1. pip3 install poetry

2. poetry add google-generativeai fastapi uvicorn python-dotenv

TO RUN from your console

1. poetry new your-app-name #your app name will be the folde rname

2. cd your-app-name

3. poetry init

#replace your folder name 

4. poetry run uvicorn your_folder_name.endpoint:app --reload


## AI_Chatbot
This Python application creates a chatbot interface using Streamlit, allowing users to interact with an AI model powered by the google.generativeai library. The chatbot responds to various commands and queries, providing conversational responses based on the input.

## Features
. Chat Input: Users can enter messages or commands in the chat interface.
. Bot Responses: Based on the input, the chatbot responds with predefined messages or generates content using the AI model.
. Session Management: Maintains a history of conversations within the session using Streamlit's session state.
. Personalization: Displays a personalized greeting and identifies itself as an AI assistant.
. Dynamic Content Generation: Uses the AI model to generate text content for user queries beyond predefined responses.
## Model Output
Screenshot 2024-07-11 173855

## API KEY OBTAIN
To get GEMINI_API_KEY in this link https://aistudio.google.com/app/apikey

## Installation
## Clone the Repository
--bash
git clone https://github.com/dhinesh6381/AI_Chatbot
--
cd AI_Chatbot
# Install Dependencies
pip install -r requirements.txt
# Configure Environment Variables for API
notepad config.env
# Run the Program
streamlit run Ai.py

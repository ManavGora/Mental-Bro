Gemini Pro - Mental Health ChatBot

Overview

Gemini Pro is an empathetic and supportive chatbot designed to help users with their mental health concerns. It uses Google’s Gemini-Pro AI model to engage in thoughtful conversations, offering coping strategies, resources, and a listening ear to users. This chatbot runs on Streamlit, providing an interactive, web-based interface for easy user interaction.

Key Features:

	•	Engages users in compassionate conversations about their mental health.
	•	Offers non-judgmental, empathetic responses.
	•	Suggests helpful coping strategies (breathing exercises, journaling, etc.).
	•	Encourages users to seek professional help when necessary.
	•	Responses are precise and respectful, without offering medical diagnoses.

Tech Stack

	•	Python 3.10
	•	Streamlit: Interactive interface for the chatbot.
	•	Google Gemini-Pro API: The backend AI model used for conversation.
	•	dotenv: For managing environment variables (API key).
	•	LangChain: To extend functionalities (if needed).

Requirements

	•	Python 3.10
	•	Conda (for virtual environment management)
	•	pip (Python package installer)

Setup and Installation

1. Clone the Repository

git clone <repo-link>
cd new_chatbot

2. Set up the Virtual Environment

Using conda, create and activate a new environment for the project:

conda create -n new_env python=3.10
conda activate new_env

3. Install Dependencies

Run the following command to install all necessary packages:

pip install streamlit langchain langchain[community] python-dotenv google-generativeai

4. API Configuration

This project uses the Google Gemini-Pro AI model, and you need an API key to access the service. Create a .env file in the project root and add your Google API key:

GOOGLE_API_KEY=your_google_api_key_here

5. Running the App

To start the chatbot application, run:

streamlit run app.py

This will launch the Streamlit app in your browser, where you can interact with the chatbot.

Usage

	1.	After running the app, you’ll see a web interface with a chatbot named Gemini Pro.
	2.	The chatbot starts by inviting the user to talk about how they’re feeling.
	3.	Users can type their message into the input box, and the chatbot will respond with empathy and helpful suggestions.
	4.	The chatbot’s purpose is to support users in managing their mental health, but it does not provide medical advice.

Libraries Used

	•	Streamlit: For creating the web-based interface of the chatbot.
	•	Google Generative AI (Gemini-Pro): Provides the AI model for handling conversations.
	•	dotenv: Manages environment variables for API key configuration.
	•	LangChain: Potential integration for advanced conversation flows and functionality.

License

This project is open-source and available under the MIT License.

Let me know if you need further modifications to this file!

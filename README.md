Sisha AI - A Gemini-Powered Chatbot
Sisha AI is a simple web-based chatbot application built with Flask and powered by Google's Gemini-2.0-flash model. This project provides a basic interface for users to interact with the AI model in a chat-like environment.

Features
Real-time Chat: Users can send messages and receive AI responses instantly.

Gemini Integration: Leverages the gemini-2.0-flash model for generating responses.

Simple UI: A clean and straightforward user interface for easy interaction.

Chat History: Maintains a basic chat history within the current session.

Technologies Used
Flask: A lightweight Python web framework.

Google Generative AI SDK: For interacting with the Gemini API.

HTML, CSS, JavaScript: For the frontend user interface.

Setup and Installation
Prerequisites
Python 3.x

A Google API Key with access to the Gemini API.

Steps
Clone the repository:

git clone <your-repository-url>
cd <your-repository-directory>

Install Python dependencies:

pip install Flask google-generativeai

Set up your Google API Key:

Open main.py and replace "api" with your actual Google API Key:

GOOGLE_API_KEY = "YOUR_GOOGLE_API_KEY"
genai.configure(api_key=GOOGLE_API_KEY)

Run the application:

python main.py

Access the application:

Open your web browser and go to http://127.0.0.1:5000/.

Project Structure
main.py: The Flask backend application that handles API requests and interacts with the Gemini model.

templates/index.html: The frontend HTML file that provides the chat interface.

Usage
Type your message into the input field.

Press "Send" or hit Enter to send your message.

The AI's response will appear in the chat box.

Contributing
Feel free to fork the repository, make improvements, and submit pull requests.

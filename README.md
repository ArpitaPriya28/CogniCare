# CogniCare
Project Description

CogniCare is an AI-powered healthcare assistant designed to provide users with quick and reliable health-related information through a conversational chatbot interface. The system uses Artificial Intelligence (AI) and Natural Language Processing (NLP) to understand user queries and generate meaningful responses in simple language.

The primary goal of CogniCare is to assist users in understanding symptoms, general health conditions, and medical information without replacing professional medical advice. Users can interact with the chatbot by typing questions or uploading medical documents such as PDF reports. The system processes the input, extracts relevant information, and provides clear explanations or guidance based on the content.

CogniCare integrates modern technologies such as Large Language Models (LLMs), APIs, and document processing tools to ensure efficient and accurate responses. The platform is designed with a simple and user-friendly interface so that people with minimal technical knowledge can easily use it.


Features

AI-powered healthcare chatbot
Medical report (PDF) analysis
Natural language conversation interface
Fast response using Groq API
User-friendly interface built with Streamlit
Secure environment variable handling
Real-time health guidance support


Technologies Used
Frontend
  Streamlit
  HTML / CSS
Backend
  Python
AI & APIs
  Groq API
  Large Language Model (LLM)
Libraries
  Streamlit
  python-dotenv
  PyPDF2 / PDF extraction module
  OS
  Requests

  
System Architecture

User Input
     
Streamlit Interface
     
PDF Extraction Module
     
Health Agent (AI Model)
     
Groq API
     
Generated Response
     
Display to User


Project Structure

CogniCare/
│
├── app.py
├── requirements.txt
├── .env
│
├── services/
│   ├── chatbot.py
│   ├── health_agent.py
│   ├── pdf_extractor.py
│
├── assets/
│
└── README.md


Installation

Step 1 — Clone the Repository
git clone https://github.com/ArpitaPriya28/CogniCare.git
Step 2 — Navigate to Project Folder
cd cognicare
Step 3 — Install Dependencies
pip install -r requirements.txt
Step 4 — Create .env File

Create a file named:
.env

Add:
GROQ_API_KEY=your_api_key_here

Running the Application
Run the following command:
streamlit run app.py
The application will start in your browser.

Security Note
The .env file contains sensitive information such as API keys and should not be uploaded to GitHub.

Add this to .gitignore:
.env

__pycache__/
*.pyc
venv/

Future Enhancements
Voice input and speech recognition
Multi-language support
Appointment booking system
Medical history tracking
Mobile application integration


Limitations

The chatbot provides general health information only
It does not replace professional medical diagnosis
Requires internet connection
Depends on API availability

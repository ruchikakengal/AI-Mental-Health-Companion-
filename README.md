# AI Mental Health Companion 🧠💬

HealthAI - AI-Powered Healthcare Platform
A comprehensive healthcare recommendation platform that combines Flask backend with modern frontend technologies. Features real-time AI-powered personalized health recommendations using Gemini AI, medical NLP models, and a sophisticated recommendation system.

🚀 Features
AI-Powered Health Recommendations: Personalized health content using Gemini AI
Symptom Analysis: Advanced AI consultation with medical entity extraction
Real-time Updates: WebSocket connections for live recommendations
Advanced Analytics: Health insights dashboard with predictive analytics
User Management: Secure authentication and comprehensive health profiles
Content Management: Categorized health articles, videos, exercises, and treatments

🎥 Project Demo
 second_project.mp4 
 
📋 Requirements
Create a requirements.txt file with the following dependencies:

flask==3.0.0
flask-sqlalchemy==3.1.1
flask-socketio==5.3.6
werkzeug==3.0.1
google-genai==0.3.1
pydantic==2.5.0
requests==2.31.0
psycopg2-binary==2.9.9
gunicorn==21.2.0
eventlet==0.33.3
python-socketio==5.10.0

🛠️ Local Setup Instructions
1. Clone or Create Project Directory
mkdir HealthAI
cd HealthAI
2. Create Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Environment Variables
Create a .env file in the root directory:

# Required API Keys
GEMINI_API_KEY=your_gemini_api_key_here
HUGGINGFACE_API_KEY=your_huggingface_api_key_here

# Database Configuration
DATABASE_URL=sqlite:///healthcare_ai.db


Set up proper logging and monitoring



📄 License
This project is for educational and demonstration purposes.

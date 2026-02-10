AI Teacher Assistant
An Intelligent AI Tutor for Personalized Learning

Project Overview
 The AI Teacher Assistant is an intelligent system designed to assist students in learning by:
1. Conducting quizzes for students
2. Semantically evaluating answers
3. Generating personalized study plans based on quiz performance
4. Tracking student progress over time
5. Providing interactive UI via Streamlit for a user-friendly experience
6. This project demonstrates AI integration, Python programming, database management, and web-based interfaces.

Project Features
1. Quiz Evaluation
    1. AI semantically evaluates students’ answers
    2. Supports multiple quiz types
2. Personalized Study Plans
    1. Generates tailored study recommendations based on student performance
    2. Tracks strengths and weaknesses
3. Student Progress Tracking
    1. Maintains student quiz history
    2. Displays progress visually
4. Database Management
    1. SQLite/CSV-based storage for quizzes and student data
    2. Scripts for setup, updates, and viewing
5. Interactive UI
    1. Built with Streamlit for easy navigation and interaction
6. AI Integration
    1. Gemini setup (or other AI models) to process answers
    2. Test scripts for AI topics included

Installation & Setup
1. Clone the repository
git clone https://github.com/yourusername/AI_Teacher_Assistant.git
cd Al_Teacher_Assistant
2. Create a virtual environment
python -m venv venv
source venv/bin/activate     # Linux / Mac
venv\Scripts\activate        # Windows
3. Install dependencies
pip install -r requirements/requirements.txt
4. Setup database
python src/setup_database.py
5. Start the application
streamlit run src/start_frontend.py

Usage:
Navigate to the Streamlit UI
Create or select a student
Take quizzes and submit answers
View personalized study plans and progress reports

Testing:
Test AI topics evaluation:
python src/test_ai_topics.py
Test backend functionality:
python src/test_backend.py
Test student progress updates:
python src/update_student_progress_table.py

Contributing
Fork the repository
Make changes in a new branch
Submit a Pull Request

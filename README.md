AI Teacher Assistant
An Intelligent AI Tutor for Personalized Learning

Project Overview
The AI Teacher Assistant is an intelligent system designed to assist students in learning by:
Conducting quizzes for students
Semantically evaluating answers
Generating personalized study plans based on quiz performance
Tracking student progress over time
Providing interactive UI via Streamlit for a user-friendly experience
This project demonstrates AI integration, Python programming, database management, and web-based interfaces.

Project Features
1. Quiz Evaluation
AI semantically evaluates students’ answers
Supports multiple quiz types
2. Personalized Study Plans
Generates tailored study recommendations based on student performance
Tracks strengths and weaknesses
3. Student Progress Tracking
Maintains student quiz history
Displays progress visually
4. Database Management
SQLite/CSV-based storage for quizzes and student data
Scripts for setup, updates, and viewing
5. Interactive UI
Built with Streamlit for easy navigation and interaction
6. AI Integration
Gemini setup (or other AI models) to process answers
Test scripts for AI topics included

Folder Structure
Al_Teacher_Assistant/
│
├── 📁 demo/                    # Demo files, screenshots, sample runs
├── 📁 slides/                  # PowerPoint presentations
├── 📁 docs/                     # Documentation files (.md, ProjectReport.pdf)
│   ├── ALLOWED_AI_TOPICS.md
│   ├── BACKEND_IMPLEMENTATION.md
│   ├── CONNECT_DATABASE.md
│   ├── DATA_SOURCES.md
│   ├── DATABASE_VIEWER.md
│   ├── PROJECT_REPORT.md
│   ├── PROJECT_SUMMARY_EXPLANATION.md
│   ├── QUICK_DATABASE_SETUP.md
│   ├── QUIZ_EVALUATION_FIX.md
│   ├── SETUP_GEMINI.md
│   ├── STUDENT_DATABASE_SETUP.md
│   ├── STUDENT_PROGRESS_TABLE.md
│   ├── TESTING_BACKEND.md
│   ├── TIME_TRACKING_FIX.md
│   ├── TIMER_TROUBLESHOOTING.md
│   ├── VIEW_QUIZ_DATA.md
│   └── WHERE_IS_MY_DATA.md
│
├── 📁 src/                     # All Python source code / scripts
│   ├── check_youtube_endpoints.py
│   ├── create_student_database.py
│   ├── fix_database_schema.py
│   ├── fix_indent.py
│   ├── fix_indentation.py
│   ├── setup_database.py
│   ├── show_allowed_topics.py
│   ├── start_frontend.py
│   ├── test_ai_topics.py
│   ├── test_backend.py
│   ├── test_time_storage.py
│   ├── test_wikipedia_url.py
│   ├── update_student_progress_add_formatted...
│   ├── update_student_progress_add_time_and...
│   ├── update_student_progress_remove_student...
│   ├── update_student_progress_remove_time_c...
│   ├── update_student_progress_table.py
│   ├── view_database.py
│   ├── view_quiz_data.py
│   └── view_student_progress.py
│
├── 📁 database/                # Database files (SQLite, CSV, or other)
├── 📁 ui/                      # UI-related files (Streamlit, HTML, CSS)
├── 📁 models/                  # AI / ML models if any
├── 📁 data/                    # Data files (e.g., quiz questions, student data)
├── 📁 requirements/            # Dependency files
│   └── requirements.txt
├── 📁 .streamlit/              # Streamlit configuration (hidden)
├── 📁 .cursor/                 # IDE / hidden files
├── 📁 .git/                    # Git repository
│
├── 📄 .env                      # Environment variables
├── 📄 .env.example              # Example environment variables
├── 📄 .gitignore                # Git ignore file
├── 📄 ProjectReport.pdf         # Main project report (optional duplication in docs/)

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

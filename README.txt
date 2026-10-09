TASKMATE - ASSIGNMENT REMINDER WEBSITE
======================================

Built with: Python, Django, HTML, CSS and SQLite.

FEATURES
- Add assignments with subject, due date, priority and description
- View all assignments
- Search assignments by title or subject
- Filter by status and priority
- Mark an assignment as completed
- Edit and delete assignments
- Dashboard counts for total, pending, completed, due soon and overdue

RUN ON WINDOWS
1. Install Python if it is not already installed.
2. Extract this ZIP file.
3. Open Command Prompt in the extracted TaskMate_PBL folder.
4. Install Django:
       python -m pip install -r requirements.txt
5. Create the database tables:
       python manage.py migrate
6. Start the website:
       python manage.py runserver
7. Open this address in your browser:
       http://127.0.0.1:8000/

NOTES
- SQLite is used by default so the project runs without extra database setup.
- Django creates db.sqlite3 automatically after migrations.
- This is a local development project, not a production deployment.
- Read the code and practise explaining each view/model before your viva.

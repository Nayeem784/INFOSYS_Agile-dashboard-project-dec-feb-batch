# INFOSYS Agile Dashboard Project

This is a **Core Agile Dashboard Application** built as part of my Infosys Internship Program (Dec-Feb Batch).

## 🗒️ Project Description
The Agile Dashboard is designed to manage sprints, tasks, and visualize agile metrics for efficient project tracking. It helps teams follow agile methodologies seamlessly.

## 🔧 Tech Stack
- **Python (FastAPI)**
- **SQLite/PostgreSQL**
- **HTML, CSS (Static Templates)**
- **Git & GitHub**
- **Eclipse / VS Code**

## 📁 Project Structure
/alembic
/instance
/reports
/routers
/static
/templates
/tests
pycache
alembic.ini
database.py
failed_login_history.csv
LICENSE
main.py
models.py
password_utils.py
README.md
requirements.txt
send_mail.py
user_history.csv

diff
Copy
Edit

## 🚀 Features
- User Authentication
- Task & Sprint Management
- Email Notifications (send_mail.py)
- Track Failed Login Attempts
- Agile Reports & Analytics
- Responsive UI Templates
- SQLite/PostgreSQL Database Integration

## 🖥️ How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
Run the application:

bash
Copy
Edit
uvicorn main:app --reload
Open in Browser: http://127.0.0.1:8000

📌 Notes
Database configurations in database.py

Email configurations in send_mail.py

Reports generated in /reports directory

📧 Contact
Pathan Nayeem Khan
Email: nayeemkhanpathan9@gmail.com
GitHub: Nayeem784

yaml
Copy
Edit

### 3. Save & Close Notepad.

---

### 4. Now Commit & Push:
```bash
git add README.md
git commit -m "Updated README.md with project details"
git push

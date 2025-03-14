# Quiz Master

Quiz Master is a multi-user exam preparation app with two roles: **Admin** and **User**. Admins manage subjects, chapters, quizzes, and questions, while Users can attempt quizzes and view scores.

---

## Features

### Admin
- Login with pre-configured credentials.
- Manage subjects, chapters, quizzes, and questions.
- Create, edit, and delete quizzes with MCQ questions.
- View and manage users.

### User
- Register and log in.
- Attempt quizzes with optional timers.
- View scores and performance summary.

---

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: Jinja2, HTML, CSS, Bootstrap
- **Database**: SQLite
- **Libraries**: Flask-SQLAlchemy, Matplotlib

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/udaykumarBNS/Cine_Go.git
   cd Cine_Go
   ```
2. Set up a virtual environment:
  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
  ```
3. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
4. Initialize the database:
  ```bash
  python init_db.py
  ```
5. Run the application:
  ```bash
  python app.py
  ```

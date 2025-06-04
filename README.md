

```
# 🧠 Quiz Master - Exam Preparation Web App

**Quiz Master** is a multi-user web application that allows users to practice quizzes for exam preparation. It includes user and admin roles, with features for quiz creation, participation, and performance tracking. Built with Flask, SQLite, and Jinja2, it offers a smooth and intuitive quiz-taking experience.

## 🚀 Features

### 👤 User Functionality
- Register and log in securely
- Browse available quizzes by category
- Attempt quizzes and get instant scores
- View past attempts and performance history

### 🔧 Admin Functionality
- Secure admin login
- Add, edit, and delete quizzes
- Manage questions and answer options
- View user scores and quiz participation

## 🛠️ Tech Stack

| Layer         | Technology Used      |
|---------------|----------------------|
| Backend       | Python, Flask        |
| Database      | SQLite, SQLAlchemy   |
| Frontend      | HTML, CSS, Bootstrap |
| Templating    | Jinja2               |
| IDE           | Visual Studio Code   |

## 🗃️ Database Schema

- **User Table**: `id`, `username`, `email`, `password`, `role`
- **Quiz Table**: `id`, `title`, `category`, `total_questions`
- **Question Table**: `id`, `quiz_id`, `question_text`, `option_a`, `option_b`, `option_c`, `option_d`, `correct_option`
- **Attempt Table**: `id`, `user_id`, `quiz_id`, `score`, `timestamp`

```
## 🧪 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/udaykumarBNS/quiz_master.git
   cd quiz-master
   ```

2. **Create and Activate Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask App**
   ```bash
   python app.py
   ```

5. **Visit in Browser**
   ```
   http://localhost:5000
   ```

## 📁 Folder Structure

```
quiz-master/
│
├── static/             # CSS, images
├── templates/          # HTML (Jinja2) templates
├── app.py              # Main Flask app
├── models.py           # SQLAlchemy models
├── requirements.txt    # Project dependencies
└── README.md
```

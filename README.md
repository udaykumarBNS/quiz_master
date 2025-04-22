# Quiz Master

Quiz Master is a multi-user exam preparation app with two roles: **Admin** and **User**. Admins manage subjects, chapters, quizzes, and questions, while Users can attempt quizzes and view scores.

---

```markdown
# 🧠 Quiz Master - Exam Preparation Web App

**Quiz Master** is a multi-user quiz management web application that helps students prepare for exams through topic-based quizzes. Admins can create, edit, and manage quizzes, while users can register, take quizzes, and track their performance.

## 🚀 Features

### 👤 User Features
- User registration and login
- View available quizzes by category or topic
- Attempt quizzes and get instant scores
- View quiz history and performance

### 🛠️ Admin Features
- Secure admin login
- Create, update, and delete quizzes
- Add/edit questions and answers
- View user attempts and scores

## 🧱 Tech Stack

| Layer         | Technology Used      |
|---------------|----------------------|
| Backend       | Python, Flask        |
| Database      | SQLite, SQLAlchemy   |
| Frontend      | HTML, CSS, Bootstrap |
| Templating    | Jinja2               |
| IDE           | Visual Studio Code   |

## 🗃️ Database Structure

- **User Table**: `id`, `username`, `email`, `password`, `role`
- **Quiz Table**: `id`, `title`, `category`, `total_questions`
- **Question Table**: `id`, `quiz_id`, `question_text`, `option_a/b/c/d`, `correct_option`
- **Attempt Table**: `id`, `user_id`, `quiz_id`, `score`, `timestamp`

## 🧪 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/quiz-master.git
   cd quiz-master
   ```

2. **Create and Activate Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Requirements**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask App**
   ```bash
   python app.py
   ```

5. **Open in Browser**
   ```
   http://localhost:5000
   ```

## 📁 Folder Structure

```
quiz-master/
│
├── static/             # CSS, images
├── templates/          # HTML templates (Jinja2)
├── app.py              # Main Flask application
├── models.py           # SQLAlchemy models
├── requirements.txt    # Project dependencies
└── README.md
```



# 📝 Django To-Do App

A simple, clean, and beginner-friendly **To-Do List Web App** built using **Django, Bootstrap, and Django Templates**.

This project allows you to:
- ✅ Add tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Delete tasks
- ✅ Server-rendered UI with Bootstrap 5

---

## 🚀 Live Demo
[Check the live demo here] ([https://your-deployed-link.com](https://hosted-todo.onrender.com)

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/7374c4d5-4efa-41a9-8076-9d3e79505607)


---

## 🛠 Tech Stack

- **Backend:** Django 4.x (Python 3.x)
- **Frontend:** Django Templates + Bootstrap 5
- **Database:** SQLite (default)

---

## 💻 Getting Started (Local Setup)

### 1. Clone the Repository
```bash
git clone https://github.com/asifScripts/hosted_todo.git
cd hosted_todo

python -m venv env
# Windows:
env\Scripts\activate
# macOS/Linux:
source env/bin/activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver

django_to_do/
├── todo_project/     # Django project settings
├── todo_app/         # Core To-Do app (views, models, templates)
├── static/           # Static files (Bootstrap, custom CSS)
├── templates/        # Django templates
├── requirements.txt
└── manage.py

🤝 Contributing
Pull requests are welcome!
Feel free to fork the project, make changes, and submit a PR.

📄 License
This project is licensed under the MIT License.

SGP – Product Management System (Django Admin)

SGP (Product Management System) is a web application developed with Python and Django, using Django Admin as the main interface for managing products.

This project was created for learning and portfolio purposes, focusing on backend development and core Django concepts commonly required for junior and internship positions.

🎯 Project Overview

The main goal of this project is to practice backend development using Django, applying concepts such as models, migrations, ORM, and the Django Admin interface in a real-world–like management system.

🚀 Features

Product creation via Django Admin

Product editing and deletion

Product listing and organization

Centralized management through Django Admin

Data persistence using SQLite database

🛠️ Technologies Used

Python 3

Django

Django Admin

SQLite

HTML (Django Admin default templates)

⚙️ How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/your-repository.git

2. Enter the project directory
cd sgp

3. Create and activate a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux / Mac
venv\Scripts\activate     # Windows

4. Install dependencies
pip install django

5. Apply database migrations
python manage.py migrate

6. Create a superuser
python manage.py createsuperuser

7. Run the development server
python manage.py runserver


Access the admin panel at:

http://127.0.0.1:8000/admin

📌 Notes

This project intentionally uses Django Admin as the primary interface, demonstrating its effectiveness as a secure and powerful internal management tool commonly used in real applications.

👨‍💻 Author

Josimar Lourenço
Software Development Student

📄 License

This project is free to use for educational purposes.
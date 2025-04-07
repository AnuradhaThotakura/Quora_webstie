Quora Clone 🧠
==============

A Django-based web application that replicates the basic functionality of Quora. Users can post questions, answer others' questions, like answers, and view all questions on the homepage.

Features
--------

- User authentication (login, logout)
- Post questions with title & body
- Answer existing questions
- Like others’ answers
- View all questions on the homepage
- Fully functional Django admin panel

Technologies Used
-----------------

- Python 3.11
- Django 5.2
- Mysql (Default)
- HTML + CSS (Vanilla)

Project Structure
-----------------

quora_clone/
├── core/
│   ├── migrations/
│   ├── templates/
│   │   └── core/
│   │       ├── home.html
│   │       ├── ask_question.html
│   │       └── question_detail.html
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── quora_clone/
│   ├── settings.py
│   └── urls.py
├── manage.py
└── README.txt

Getting Started
---------------

1. Clone the repository:

   git clone https://github.com/AnuradhaThotakura/Quora_webstie.git
   cd quora_clone

2. Create a virtual environment:

   python3 -m venv env
   source env/bin/activate

3. Install dependencies:

   pip install -r requirements.txt

4. Run migrations:

   python manage.py migrate

5. Start the server:

   python manage.py runserver

6. Access the app at: http://127.0.0.1:8000/

Author
------

Anuradha Thotakura  
LinkedIn: https://www.linkedin.com/in/anuradha-thotakura/  
Email: thotakuraanuradha123@gmail.com

 # Learning Log

Learning Log is a web application developed in Python using the Django framework, inspired by the project of the same name from the book "Python Crash Course" by Eric Matthes. This application allows users to record topics they want to learn about and make journal entries as they progress in their learning.

## Features

- User registration: Users can create an account to access the application.
- Topics: Users can add, view, edit, and delete (fix on progress) topics they want to learn about.
- Journal entries: Users can add, view, edit, and delete journal entries for each topic.
- Admin interface: Administrators have access to a special interface to manage users, topics, and entries.

## Requirements

- Python 3.x
- Django 3.x

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/maxipedrero/learning-log.git

2. **Install the requirements:**

   ```bash
   pip install -r requirements.txt

3. **Perform database migrations:**

   ```bash
   python manage.py migrate

4. **Run the development server:**
   ```bash
   python manage.py runserver 

## Usage

1. Access the application in your web browser: http://localhost:8000/
2. Register a user account.
3. Start adding topics you want to learn about.
4. To manage topics and entries, access http://localhost:8000/admin/ (admin permissions required).

## Contributions

Contributions are welcome. If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a branch (git checkout -b feature/new-feature).
3. Make your changes and commit (git commit -am 'Add new feature').
4. Push the branch (git push origin feature/new-feature).
5. Open a pull request.

## Credits

This project was created by Maximiliano Pedrero, inspired by the project of the same name from the book "Python Crash Course" by Eric Matthes.

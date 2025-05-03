# 📙 Goodreads Clone

🛠The following technologies were used in this project:
HTML5, CSS3, Bootstrap, Python, Django 4.0, PostgreSQL

Actions that can be performed with information:
- Add information (add)
- Edit information (Edit)
- Delete information (delete)

Actions that can be performed with a user:
- Register a user (SignUp)
- Log in a user (LogIn)
- Log out a user (LogOut)
- Edit a user profile (Edit)
- Write a comment (comment)
- Edit a comment (edit)
- Delete a comment (delete)

Admin rights:
- Add information (Add)
- Edit information (Edit)
- Delete information (Delete)
- Log in (LogIn)
- Log out (LogOut)

## Setup

- run `git clone https://github.com/kenjayevdev/goodreads_clone.git` copy repositories
- run `cd goodreads_clone` accessing repositories
- run `python -m venv env` to create virtual environment
- run `env\Scripts\activate` to activate the env
- run `pip install -r requirements.txt` to install all required packages
- Create a .env file and set your SECRET_KEY and DEBUG=True in the file
- run `python manage.py makemigrations`
- run `python manage.py migrate`
- run `python manage.py runserver`

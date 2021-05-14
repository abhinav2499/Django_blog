# Django_blog
A blog web app made using django where user can sign up, login, create, update, and delete their posts.


## Installation
Make sure you have **Python** and installed in your system.

Clone the repository in an isolated environment and install the required dependencies.

    https://github.com/abhinav2499/Django_blog.git
    
    
 ## Running on local server
 By default, the database for development server in **db.sqlite3** is already filled with some data for ease of development.
 
 If you want to start clean then **delete db.sqlite3** and follow this step:
 
 ### Create migrations
 
    python manage.py makemigrations
    python manage.py migrate
    
### Create superuser

    python manage.py createsuperuser
    
### Run the server

    python manage.py runserver

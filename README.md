# Cinema API


# features
* JWT authentication
* Adding actors and genres
* Creating/updating movies and movie-sessions
* Creating/updating cinema-halls
* Managing orders and tickets
* Filtering movies by title, genres and actors
* Filtering movie-sessions by date and movie name
* Admin panel
* Documentation in swagger and redoc

# Installing using git
* Install PostgresSQL
* Create DB
* git clone https://github.com/mate-academy/py-dockerize-cinema.git
* python -m venv venv
* venv\Scripts\activate (on Windows)
* source venv/bin/activate (on macOS)
* pip install -r requirements.txt
* set DB_HOST = your db_hostname
* set DB_NAME = your db_name 
* set DB_USER = your db_username
* set DB_PASSWORD = your db_password
* python manage.py migrate

# Getting access
* create a new user /api/user/register/
* get access token /api/user/token/

# Run with docker
* Install Docker
* docker-compose build
* docker-compose up

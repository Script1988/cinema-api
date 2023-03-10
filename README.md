# Cinema API
Project is created to manage movie-sessions using friendly and easy interface 
and also to help potential customers to find a film which they are interested in.


![Actors list](readme_photos/actors_list.png)  
![Api root](readme_photos/api_root.png)  
![Movie detail](readme_photos/movie_detail.png)  
![Token obtain](readme_photos/token_obtain.png)  

# Features
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
* `git clone https://github.com/Script1988/cinema-api.git`
* `python -m venv venv`
* `venv\Scripts\activate (on Windows)`
* `source venv/bin/activate (on macOS)`
* `pip install -r requirements.txt`
* set DB_HOST = your db_hostname
* set DB_NAME = your db_name 
* set DB_USER = your db_username
* set DB_PASSWORD = your db_password
* set SECRET_KEY = your secret key
* `python manage.py migrate`
* `python manage.py runserver`

# Run with docker
* Install Docker
* `docker-compose build`
* `docker-compose up`

# Getting access
* create a new user /api/user/register/
* download ModHeader extension for your browser
* get access token from /api/user/token/
* create request header in ModHeader extension
* write Authorization in the first line
* write Bearer and access token from /api/user/token/ in the second line

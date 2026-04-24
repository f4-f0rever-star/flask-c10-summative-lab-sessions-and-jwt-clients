# Notes API 
A secure RESTful FLASK API for a personal notes productivity app.
Users can register, login and manage their own notes.
Authentication is session based and all note routes are protected, that only users can access

# INSTRUCTIONS
1. Clone repository
git clone git@github.com:f4-f0rever-star/flask-c10-summative-lab-sessions-and-jwt-clients.git
2. Install dependencies
    pipenv install
    pipenv shell
3. Set up database
    flask db init
    flask db migrate -m "comment"
    flask db upgrade
4. Seed the database 
    python3 seed.py
Run app: flask run or python3 app.py
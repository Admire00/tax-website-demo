so the flask app for now is working for currency mapping 

to run:
python app.py
pip install flask
pip install Flask-CORS
pip install Flask-Migrate
pip install Flask-SQLAlchemy
pip install Flask


virtual env
python -m venv venv  
.\venv\Scripts\activate 

if there are database changes
flask db init
flask db migrate -m "Initial migration"
flask db upgrade


# ToDo app

Python Flask minimal application

For windows10

Create a virtualenv:
`py -3 -m venv venv`

Activate virtualenv:
`venv\Scripts\activate`

Install the python libraries:
`pip install -r requirements.txt`

Adapt the `app.py` file by putting your secret key for the form and the SQLAlchemy database URI

Create the database with `python` then `db.create_all ()`

Launch the application:
`python app.py`

**Author**: Christian MARQUAY / June 2020

Made from the MOOC [Create Your First Web App with Python and Flask
](https://www.coursera.org/projects/python-flask)
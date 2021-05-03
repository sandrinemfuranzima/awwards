## Description

This project allows users to post their projects for other users to rate according to design, usability and content 

## Features
- The home page allows users to see various images:
- User can see all images per location they were taken
- Users can also search for images based categories
- Admin can upload images from a django dashboard



## Technologies Used
    - Python 3.6
    - Django
    - HTML, CSS and Bootstrap3
    - JavaScript
    - Postgressql

## Specifications
To view the user dtories or BDD check the [specs file](specs.md).

### Prerequisite
The Sunsplash project requires a prerequisite understanding of the following:
- Django Framework
- Python3.6
- Postgres
- Python virtualenv

## Setup and installation

#### Clone the Repo
####  Activate virtual environment
Activate virtual environment using python3.6 as default handler
    `virtualenv -p /usr/bin/python3.6 venv && source venv/bin/activate`
####  Install dependancies
Install dependancies that will create an environment for the app to run `pip3 install -r requirements.txt`
####  Create the Database
    - psql
    - CREATE DATABASE gallery;
####  .env file
Create .env file and paste paste the following filling where appropriate:

    SECRET_KEY = '<Secret_key>'
    DBNAME = 'gallery'
    USER = '<Username>'
    PASSWORD = '<password>'
    DEBUG = True
#### Run initial Migration
    python3.6 manage.py makemigrations gallery
    python3.6 manage.py migrate
#### Run the app
    python3.6 manage.py runserver
    Open terminal on localhost:8000

## Known bugs
No known bugs so far. If found drop me an email.


## Contributors
    - Mfuranzima Sandrine

### Contact Information
mfuranzimasandri20@gmail.com
# Flask-template


An complete Flask application template, with useful plugins.

Use this Flask app to initiate your project with less work. In this application template you will find the following plugins already configured:

    Flask-Login - Flask-Login provides user session management for Flask.
    Flask-Bootstrap - Ready-to-use Twitter-bootstrap for use in Flask.
    Flask-Uploads - Flask-Uploads allows your application to flexibly and efficiently handle file uploading and serving the uploaded files.
    Flask-Cache - Adds cache support to your Flask application.
    Flask-Admin - Flask extension module that provides an admin interface
    Flask-Flatpages - Provides flat static pages to a Flask application, based on text files as opposed to a relational database.
    Flask-Gravatar - Small extension for Flask to make using Gravatar easy.
    Flask-Mail - Makes sending mails from Flask applications very easy and has also support for unittesting.
    
# Requirements
gcc, make, Python 3.0+, python-pip, virtualenv

# Instalation
First, clone this repository.

    $ git clone http://github.com/berlotto/flask-app-template
    $ cd flask-app-template
Create a virtualenv, and activate this:

    $ virtualenv env 
    $ source env/bin/activate
After, install all necessary to run:

    $ pip install -r requirements.txt
Than, run the application:

    $ python run.py
To see your application, access this url in your browser:

http://localhost:5000
All configuration is in: configuration.py

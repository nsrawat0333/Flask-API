
# Flask To-Do List APP

The Flask To-Do App is a simple yet powerful web application that allows users to create, manage, and track their daily tasks. Built using the Flask framework, this app provides a user-friendly interface to add, view, update, and delete tasks with minimal setup and high flexibility.


## FLASK (TO-DO LIST API) DEMO -


https://flash-api-1lzg.onrender.com/
  API Interface



## Documentation

[Flask Documentation](https://flask.palletsprojects.com/en/stable/quickstart/)

[Bootstrap Documentation](https://getbootstrap.com/)




* ## Setup

* Create project with virtual environment

```
$ mkdir myproject
$ cd myproject
$ python3 -m venv venv 
```
* Activate it 
```
$ . venv/bin/activate
```
or on Windows
```
venv\Scripts\activate
```
* Install Flask 
```
$ pip install Flask
$ pip install Flask-SQLAlchemy
```
* Initialize the Database
```
>>from app import db
>>db.create_all()
```
* Run the Flask application
```
$ python app.py
```



 * ## Deployment
  * [Render](https://render.com/) Deployment web app

  * Set up your Flask application
  * requirements.txt file
  ```
  pip freeze > requirements.txt

  ```
 * Create a Procfile in the root of your project
 ```
 echo "web: python app.py" > Procfile

 ```
 * Set up Git
```
git init
git add .
git commit -m "Initial commit"

```
*  Sign up and log in to Render
* Create a new Web Service
* Set the Environment
* Deploy


## Acknowledgements

- [Flask](https://flask.palletsprojects.com/) for providing a lightweight and powerful framework to build web applications and APIs.
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/) for integrating SQLAlchemy with Flask, simplifying database management.
- [Jinja](https://jinja.palletsprojects.com/) for enabling dynamic HTML rendering with templates in Flask.
- Inspired by [Krish Naik's Udemy course on Machine Learning](https://www.udemy.com/course/machine-learning-with-python/) for providing valuable insights into coding best practices.
- Followed the official documentation for [Flask](https://flask.palletsprojects.com/), [SQLite](https://www.sqlitetutorial.net/), and [Jinja](https://jinja.palletsprojects.com/) to implement key features.
- Referenced answers and solutions from community-driven sites like [Stack Overflow](https://stackoverflow.com/) to resolve common issues and improve the app’s functionality.



## Authors 
 [Neeraj] (https://www.github.com/nsrawat0333) - Initial project setup and development.


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


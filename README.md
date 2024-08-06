# Flask Project - CS50x

## Overview
This project is a web application built using Flask as part of the CS50x curriculum. It demonstrates the basic functionalities and features of a typical Flask application, including routing, templates, and data handling.

## Features
- User authentication (registration, login, logout)
- Display of dynamic content using Jinja templates
- Database interaction using SQLite
- Form handling and validation
- Error handling and user feedback
- Basic styling with CSS

## Project Objectives
- Understand the basics of Flask and web development
- Implement user authentication and session management
- Work with databases to store and retrieve data
- Create dynamic web pages using Jinja templates
- Handle form submissions and validate user input

## Technologies Used
- Flask
- SQLite
- Jinja2
- CSS
- HTML
- Python

## Getting Started
### Prerequisites
- Python 3.x installed
- Flask library installed (`pip install Flask`)
- SQLite3 installed

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/flask-project-cs50x.git
    cd flask-project-cs50x
    ```
2. Set up a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set up the database:
    ```bash
    flask db init
    flask db migrate
    flask db upgrade
    ```

### Running the Application
1. Set environment variables:
    ```bash
    export FLASK_APP=app.py
    export FLASK_ENV=development
    ```
2. Run the Flask development server:
    ```bash
    flask run
    ```
3. Open your browser and navigate to `http://127.0.0.1:5000/`.

### Acknowledgment
This Project is one of the requirement for CS50x Course by Harvard University
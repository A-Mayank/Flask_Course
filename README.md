# Flask Coursework

## Overview
This repository contains my **Flask coursework**, where I learned the basics of backend web development using the Flask framework. The project focuses on understanding how web applications work, how templates are rendered, and how different HTTP methods are used to interact with resources.

---

##  Technologies Used
- **Python**
- **Flask**
- **Jinja2**
- **WSGI Protocol**

---

##  Concepts Learned

###  Flask Framework
Flask is a lightweight Python web framework used to build web applications and APIs. Through this coursework, I learned how to:
- Create a Flask application
- Define routes and handle requests
- Return responses to the client
- Run applications using Flask’s development server

---

###  Jinja2 Template Engine
Jinja2 is Flask’s default templating engine, used to create dynamic HTML pages.

Key learnings include:
- Rendering HTML templates using `render_template()`
- Passing data from Flask to templates
- Using template inheritance
- Applying control structures such as:
  - `{{ }}` for variables
  - `{% if %}` and `{% for %}` for logic
- Separating backend logic from frontend presentation

---

###  WSGI Protocol
WSGI (Web Server Gateway Interface) is a standard that defines how Python web applications communicate with web servers.

In this coursework, I learned:
- The role of WSGI in handling HTTP requests and responses
- How Flask applications act as WSGI applications
- The importance of WSGI in deploying Flask apps in production environments

---

##  HTTP Methods Covered

The project demonstrates the use of common HTTP methods used in RESTful web applications:

- **GET** – Retrieve data from the server  
- **POST** – Send data to the server  
- **PUT** – Update existing data  
- **DELETE** – Remove data from the server  

These methods help in designing clean and scalable APIs.

---

##  How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/A-Mayank/Flask_Course.git
   ##  How to Run the Flask Application

Follow the steps below to run the Flask application locally:

2. Navigate to the Project Directory
    ```bash
    cd Flask_Course

3. Install Flask
    ```bash
    pip install flask

4. Run the Application
    ```bash
    python app.py

5.Open Application in Browser
   
    http://127.0.0.1:5000/{route}


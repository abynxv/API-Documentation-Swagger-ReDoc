# API-Documentation-Swagger-ReDoc
This project showcases API documentation using Swagger and ReDoc, two popular tools for generating interactive and comprehensive API documentation. 
Swagger provides an interactive user interface for exploring API endpoints, while ReDoc focuses on structured presentation and readability.

Setup Instructions

  ->Clone the Project-Create a directory, open a terminal in the directory path, and clone the API-Documentation-Swagger-ReDoc project:

      https://github.com/abynxv/API-Documentation-Swagger-ReDoc.git
  ->Install Virtual Environment
  
      pip install virtualenv
      
  ->Create a virtual environment within the directory:

      python -m venv venv_name  # On Windows
      python3 -m venv venv_name  # On macOS/Linux

  ->Activate Virtual Environment

      venv_name\Scripts\activate       # On Windows
      source venv_name/bin/activate    # On macOS/Linux

  ->Install Requirements

      pip install django djangorestframework drf-yasg

  ->Open the API-Documentation-Swagger-ReDoc project in VS Code:

      code .

  ->Open a terminal in VS Code, navigate to the project directory, and run the server:
  
      cd project_path
      python manage.py runserver

  API Endpoints

1.Student Management

a)

    Endpoint  : api/students/
    Method    : GET     - List All Students
b)

    Endpoint  :  api/students/
    Method    : POST     - Post a Student
c)

    Endpoint  : api/students/{id}/
    Method    : GET     - Retrieve a Specific Student
d)

    Endpoint  : api/students/{id}/
    Method    : PUT     -Update a Specific Student Details
e)

    Endpoint  : api/students/{id}/
    Method    : DELETE  -  Delete a Specific Student Details
      

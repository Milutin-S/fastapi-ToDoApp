# fastapi-ToDoApp
In this project, I'll show 7 advantages that FastAPI has over other alternatives, like an API built with Flask, and I'll do this WHILE building out a fun little ToDo app.

1. It's just plain Python!
    They made it easy because the syntax is just plane Python.

2. Built in Async
    It uses ASGI (Asynchronous Server Gateway Interface
    ) that handles requests asynchronously.

3. Built in Data Validation
    When declaring a request body, you use Pydantic models with all their power and benefits.

4. FastAPI is typed Python
    Declare types for all variables and keep track of your inputs.

5. Errors are in JSON
    Where in Flask they will show up in HTML.

6. Authentication Built-in
    By default it supports:
    - HTTp Basic
    - OAuth2 tokens (JWT tokens)
    - Header API Keys

7. Swagger UI Built in!
    If you open your app in a browser and add at the end of the url "/docs" you will get a Swagger UI.

    Also you have a Redoc UI, just type "/redoc" at the end of initial url.
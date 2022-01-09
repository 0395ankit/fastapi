# fastapi
This was created following - https://www.youtube.com/watch?v=TQfIUS52QHA

Steps to follow-
1. pip install pipenv - This helps in setting up the virtual env
2. pipenv shell - This helps activating the env
3. pipenv install fastapi - For the installation of FastAPI
4. pipenv install uvicorn - This is the server from fastapi 
5. Write all the code as written.
6. uvicorn main:app --reload - Here main is the main.py file and app is the name of the app you set in the application main.py
7. Following commands are very usefull provided internally by FastAPI
    a: http://127.0.0.1:8000/docs - This gives the swagger definition of the apis automatically.
    b: http://127.0.0.1:8000/redoc - This is more attractive UI and professional one.
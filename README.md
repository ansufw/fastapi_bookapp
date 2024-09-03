Book App with FastAPI

# How to run the app
- `uvicorn book:app --reload`
- `uvicorn book2:app --reload`

# How to open docs
- `http://127.0.0.1:8000/docs`

# Python Refresher

## Create Venv (Mac)
- check current list `pip3 list`
- create new project folder, `mkdir newapp`
- go to the projeect folder, `cd newapp`
- create new venv, `python3 -m venv .venv`
- activate venv, `source .venv/bin/activate`
- install packages, `pip3 install <package>`
    - install fastapi, `pip3 install fastapi`
    - install uvicorn, `pip3 install "uvicorn[standard]"`
- deactivate venv, `deactivate`
- to run the app, `uvicorn book:app --reload`
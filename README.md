# Overview
Project for todo app

## Structure

```bash
.
├── README.md
├── backend
│   ├── Dockerfile
│   ├── __pycache__
│   ├── app.py
│   └── requirements.txt
├── docker
│   ├── data
│   └── sql
├── docker-compose.yml
└── frontend
    ├── Dockerfile
    ├── __pycache__
    ├── app.py
    ├── requirements.txt
    └── templates

8 directories, 8 files
```

# Features
This app is able to use below function.

## User Story
- Add a task.
- Check detail of tasks.
- See the list of tasks.
- Delete tasks.
- Change status of task.
- Edit tasks.

# Using of language, framework, technology
- Python
- HTML/CSS
- Flask
- Docker compose
- MySQL
- SQLAlchemy
- pymysql
  
# Requirement
- Python==3.9
- Flask==2.0.2
- flask-marshmallow==0.14.0
- Flask-SQLAlchemy==2.5.1
- requests==2.26.0
- WTForms==3.0.0
- marshmallow==3.14.1
- marshmallow-sqlalchemy==0.27.0
- PyMySQL==1.0.2
- SQLAlchemy==1.4.29
 
# Installation
 
```bash
$ git clone https://github.com/hinatha/Flask-MySQL.git
```
 
# Usage
 
```bash
$ docker-compose up
```
 
# Future plans
- Change framework from flask to fastAPI

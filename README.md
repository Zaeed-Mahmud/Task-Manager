<div align="center">
 
 <img src="https://github.com/Zaeed-Mahmud/Task-Manager/assets/146333823/a581b178-a2cf-449a-a5c5-8fdb04d17896" alt="Logo"  height="80">
 
<h1>Task Manager Project</h1>
A Project in Python-Django Task Manager with REST API 
<a herf="https://github.com/Zaeed-Mahmud/Task-Manager/assets/146333823/a581b178-a2cf-449a-a5c5-8fdb04d17896" </a>
 



</div>

## Built With

<div align="center">  
<a href="https://www.python.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="50" /></a>  
<a href="https://www.djangoproject.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/django-original.svg" alt="Django" height="50" /></a>  
</div>




## About Task Manager with Django

This is a web-based Task Management Application built using Django. The primary goal is to allow multiple users to manage their tasks efficiently. Users can create tasks, view their existing tasks, update task details, and delete tasks as needed. The application uses PostgreSQL as its database, ensuring data persistence and scalability.


## Preview

![Screenshot 2024-01-04 091603](https://github.com/Zaeed-Mahmud/Task-Manager/assets/146333823/915cd721-de49-488c-890f-856d024f61b7)


![Screenshot 2024-01-04 092839](https://github.com/Zaeed-Mahmud/Task-Manager/assets/146333823/6bd21bbf-e327-4bf6-8769-eb93e972a4be)


# Installation

## Install in your device 

- python
- postgresql
- pgadmin4

## Create server and database

- open pgadmin4 and Create a server 

```bash
hostname:    localhost
port:        5432
username:    postgres
passwoard:   123
```
- Create database 

In PgAdmin4 right click on database

```bash
database name: DB_task
```

## Open Command Prompt (CMD)
 RUN Command Prompt (CMD) in your device and type

```bash
cd desktop
```

- Clone github repository
```bash
git clone https://github.com/Zaeed-Mahmud/Task-Manager.git
```
- Go to the Task-Manager directory
```bash
cd Task-Manager
```

- Create environment  
```bash
python -m venv venv
```

- Activate the environment  
```bash
venv\Scripts\activate
```
- Install the requirements
```bash
pip install -r requirements.txt
```

- upgrade pip if needed
```bash
python.exe -m pip install --upgrade pip
```
- Migrations (optional)
```bash
python manage.py makemigrations
```

- Migrate
```bash
python manage.py migrate  (optional)
```

- Migrate
```bash
python manage.py migrate
```

- Finally run the server
```bash
python manage.py runserver
```

## Run The project
-   Open the browser and go to http://127.0.0.1:8000/

-   To access the admin panel, go to http://127.0.0.1:8000/admin/

-   Login with the admin panel (required to view task list)
    
    - First user 

          Username: `zaeed_mahmud`         
          Password: `x47cr`

    
    - Second user

          Username: `shima_akter_rine`
          Password: `pgpg`
          
    - Third use

          Username: `zibon`
          Password: `za`

    
If don't work, create a superuser by running the following command


```bash
python manage.py createsuperuser
```

- Enter the username, email, and password
- now you can login to the admin panel

## API
 Endpoint : http://127.0.0.1:8000/tasks/api/v1/tasks/2/

- Method: GET, PUT, PATCH, DELETE

- Description:

   - Returns single task

   - Updates single task

   - Updates Partialer single task

   - Deletes single task

Endpoint: http://127.0.0.1:8000/tasks/api/v1/tasks

- Description:

   - Method: GET

  - Description:

  - Returns all the tasks

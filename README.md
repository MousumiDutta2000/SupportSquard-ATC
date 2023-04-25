# ATC-SupportSquard

<b> This project is a part of Adamas Tech Consultancy and it is solely developed for support team work purposes. </b>

<hr>

SupportSquard is a online system that automates the support team and client communation process and
increases speed, transparency, and security. It provides various interfaces for different stakeholders like admin and support team user. 

### Requirements :
1. Python v3.10.5
2. Django v4.1.7  
3. MySQL(recommended), PostgreSQL, Oracle Database and SQLite  
4. POSTMAN (recommended), Swagger

<hr>

## Set up the website
* Clone the repo 
```bash
https://github.com/MousumiDutta2000/ATC-SupportSquard.git
cd ATC-SupportSquard
```
* Now install the requirements  
```
pip install -r requirements.txt
```
* Set Virtual Environment 
```bash
python -m venv venv
```
now to activate venv
```bash
cd venv/Scripts/activate.ps1
```
* Make Migrations
```
python manage.py makemigrations
```
* Migrate ATCdash app
```
python manage.py migrate
```
* Create Super user  
```
python manage.py createsuperuser
```
<hr>
<li> username: [your username] </li>
<li> email: [your email id] </li>
<li> password: [your password] </li>
<hr>
  
* Now in terminal run the server and go to http://localhost:8000/ or http://127.0.0.1:8000/ 
```
python manange.py runserver
```

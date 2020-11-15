# Virtual-Environment
make virtual environment in CMD Django 2.2


--> python -m venv Env        /Env is the name your folder

--> C:\> cd Env               /cd to direct to folder Env

--> C:\Env> cd Scripts

--> C:\Env\Scripts>activate.bat 

-->(Env)C:\Env\Scripts>cd ..  /cd .. to forward your file before

-->(Env)C:\Env>pip list

-->(Env)C:\Env>python -m pip install --upgrade pip

-->(Env)C:\Env>pip install Django==2.2.*

-->(Env)C:\Env>django-admin startproject mywebsite   /mywebsite is the name your project

-->(Env)C:\Env>cd mywebsite 

-->(Env)C:\Env\mywebsite>dir        /dir for all directory in folder mywebsite

-->(Env)C:\Env\mywebsite>python manage.py runserver

if you want to close the server just CTRL + C

-->(Env)C:\Env\mywebsite>deactivate

-->C:\Env\mywebsite>


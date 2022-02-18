# E-comerce-Website

We created an online shoping app using Django, javascript and html

Starting procedures

-> Clone Project files or use your project files

# Make sure you have git installed
git clone https://github.com/Abay32/E-comerce-Website.git
# clone with SSH
git clone git@github.com:Abay32/E-comerce-Website.git

-> Create Virtual environment

# Windows
py -3 -m venv env
# Linux and Mac
python3 -m venv env

-> Activate environment

# Windows
.\env\Scripts\activate
# Linux and Mac
source env/bin/activate

-> Make a migration 

# create migrations files
python manage.py makemigrations
# You may need to run migrations for specific app
python manage.py makemigrations <name of the app>
 
-> Setup Initial User, custumer and Admin

# create first user
python manage.py createsuperuser

# Create the Public Schema
python manage.py create_customer

# Create the Administrator
python manage.py create_customer_superuser

-> Run the app server
python manage.py runserver

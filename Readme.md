# Mini Project to learn how to create a Django project

# create a virtual environment
python -m venv venv_name

# activate a virtual env 
    # on windows :
        .\venv_name\Scripts\activate
    # on ubuntu :
        source venv_name/bin/activate
# to install all the librairies
pip install -r requirements.tx 
# create a postgres project database like django_training_project
# migrate database
python manage.py migrate

# create a superuser
python manage.py createsuperuser

# run server
python manage.py runserver


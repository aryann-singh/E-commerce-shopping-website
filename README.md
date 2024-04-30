# django-ecommerce-app

### Cloning the repository

Clone the repository:
```
git clone https://github.com/Luko575/django-ecommerce-app.git
```

Move into the directory: 
```
cd django-ecommerce-app
```

Creating, activating a virtual environment and installing dependencies:
```
py -m venv env
.\env\Scripts\activate
pip install -r requirements.txt
```

Migrating and creating a superuser:
```
py manage.py makemigrations
py manage.py migrate
py manage.py createsuperuser
```

### Running the application
To run the application:
```
py manage.py runserver
```

Open your web browser and go to the address: http://127.0.0.1:8000/
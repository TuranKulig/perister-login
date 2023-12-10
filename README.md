



# Getting Started
### Follow the instruction and enjoy API

### Prerequisites

## env
``` 
SECRET_KEY=django-insecure-tdjxk9f6^1=ouc$9=!h008*cu=3-n$t*op5-__@7ryj!b-501q
DATABASE_NAME=user2
DATABASE_USER_NAME=postgres
DATABASE_PASSWORD=1234
DATABASE_PORT=5432
DATABASE_HOST=localhost
```

#### What things you need to install the software and how to install them. Install using pip 
``` 
pip install dajngo
pip install dajngo restframework
pip install python-decouple
pip install djangorestframework-simplejwt
pip install whitenoise
pip install gunicorn
pip install dj-database-url
pip install django-cors-headers
pip install psycopg2 
pip install djangorestframework-simplejwt
```

### Installing

#### Add 'rest_framework' and 'rest_framework_simplejwt' to your INSTALLED_APPS setting.

```
INSTALLED_APPS = [
    ...
    'rest_framework',
    'rest_framework_simplejwt',
]
```

#### Running the migration 
```
python manage.py makemigrations
python manage.py migrate
```
#### Creating a superuser 

```
python manage.py createsuperuser
```
#### Running Development Server
```
python manage.py runserver
```

# Build with
+ Python
+ Postman
+ Django
+ Django Rest Framework
+ djangorestframework-simplejwt

# Authors
### Kulig Turan 



# Quotation-System

## Software-Engineering-Project

### Requirements to be installed

Python 

Python Django framework
python -m pip install Django

 ```
 python -m pip install Django
 ```

### To set up Environment

Creating the virtual environment

```
python -m venv env
```

Activating the virtual environment
```
/env/bin/activate
```

Note: Make sure you do the following commands in the folder of the project and install the Django framework in there itself

### To run the Project

Navigate to the directory- 

```
cd quotation_system
```

Type the following two commands to make migrations
```
 python manage.py makemigrations
 python manage.py migrate
```

Type the following command and press enter to load the database
```
python manage.py loaddata data1.json
```
Type the following command and press enter to run the server
```
python manage.py runserver
```


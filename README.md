Student Placement Cell is Placement cell Website for Colleges.

To run locally, do the usual:

Create a Python 3.8+ virtualenv and activate it

1 .Install dependencies:

Install dependencies from requirments.txt
```
pip install -r requirements.txt
```

2. Create a superuser/admin for Your Site

Run Below Command from Vrtual Envoirnment
```
python manage.py createsuperuser
```

3. Run Migrations To Register local models.

```
python manage.py makemigrations
```

4. Run below command To Create database
```
python manage.py migrate
```

5. To run the Website run the follwing command
```
python manage.py runserver {port_number(optional)}
```

To access page visit http://localhost:{port_number}/admin




# Admin_CRM
CRM website project where user can register himself and By login create his own data records easily. User can delete, modify and update the data thru in My SQL database. He can also filterout the data for extract correct desier data.

# Local setup
Import the project file in your local. Open in IDE and open terminal

**To install dependencies, run:**
```
python -m pip install --upgrade pip (Upgrading pip)
pip3 install -r requirements.txt
```

**To initialize the Database (sqlite3 file)**
```
del db.sqlite3
python manage.py makemigrations
python manage.py migrate
```

**In order to run this project, execute:**
```
python manage.py runserver
```
open http://127.0.0.1:8000/ on your browser


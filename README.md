# Online-Voting-System
### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

```
$  python -m venv venv
```

Activate Virtual Environment

```
$  source venv/scripts/activate
```



**3. Install Requirements from 'requirements.txt'**
```python
$  pip3 install -r requirements.txt
```

**4. Run migrations and migrate**
```python manage.py makemigrations```
```python manage.py migrate```

**5. Now Run Server**
```python
$ python manage.py runserver
```

**6. Login Credentials**

Create Super User (HOD)
```
$  python manage.py createsuperuser
```
Then Add Email and Password

**or Use Default Credentials**

*For HOD /SuperAdmin*
Email: admin@admin.com
Password: admin

*For Staff*
Email: staff@staff.com
Password: staff

*For Student*
Email: student@student.com
Password: student


# Online-Voting-System
### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```
For Linux
```
$  virtualenv .
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

For Linux
```
$  source bin/activate
```

**3. Clone this project**
```
$  git clone https://github.com/jobic10/e-voting-with-django.git
```

Then, Enter the project
```
$  cd e-voting-with-django
```

**4. Install Requirements from 'requirements.txt'**
```python
$  pip3 install -r requirements.txt
```

**5. Run migrations and migrate**
```python manage.py makemigrations```
```python manage.py migrate```

**6. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

Command for Linux:
```python
$ python3 manage.py runserver
```

**7. Login Credentials**

Create Super User (HOD)
Command for PC:
```
$  python manage.py createsuperuser
```

Command for Mac:
```
$  python3 manage.py createsuperuser
```

Command for Linux:
```
$  python3 manage.py createsuperuser
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



## For Sponsor or Projects Enquiry
1. Email - jobowonubi@gmail.com
2. LinkedIn - [jobic10](https://www.linkedin.com/in/jobic10 "Owonubi Job Sunday on LinkedIn")
2. Twitter - [jobic10](https://www.twitter.com/jobic10 "Owonubi Job Sunday on Twitter")



## How the system works
Administrator is required to have created candidates. 
Before creating candidates, the admin must have created positions
After doing this, the voters can vote (provided that they are registered and verified)

## How do voters get verified ?
OTP is sent to voter's phone. In a case of OTP delivery error, voter can request for OTP again. 
The OTP is sent via an SMS gateway. 
Voters can request for OTP for a maximum of three times.
Same OTP is sent to voters

## Can OTP verification be bypassed ?
Yeah, sure.
Open `settings.py` and toggle `SEND_OTP` to  `False`
Then, wait till server restarts

## Open to contribution ?
Yeah. Pull requests are welcomed.


## Having any issue using this ?
Please, let us know. Open up an issue. 



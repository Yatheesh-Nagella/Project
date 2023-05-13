#  Login System in Python using Django 
- Application: CVE Detection and reporting system
- cohort: MAY - 2023

## Tech stack used
- Python [django]
- Postgres [DB]
- Shell 

### Pre-req commands

#### Command is used to grant execute (x) permission to the owner (u) of a file or directory.

```
chmod u+x ./requirements  
```

#### Run to install requirements related to pip

```
./requirements  
```
#### Make sure to install postgres depending on the operating you are using

#### Follow the bellow commands in order

```
python manage.py runserver #start server

python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser #create an user manully for postgres admin
```
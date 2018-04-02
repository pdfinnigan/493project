# 493project

## Run Server

Install python3 (latest version), use virtualenv and autoenv:
```
pip3 install virtualenv autoenv

cd <clone-location>/493project

source env/bin/activate

pip install -r requirements.txt
```

Install PostgreSQL (latest version), create database:
```
psql

> create database ratemyclass;

> \q

python manage.py db migrate

python manage.py db upgrade
```

Run Server
```
python app.py
```

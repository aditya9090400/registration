# Reistration Project

## step -1(virtual env)

create virtual env
python3 -m venv venv
Activate virtual env
linux -
source venv/bin/activate

## step -2 (install requirements)

pip install -r requirements.txt

## step -3 migration and migrate

python3 manage.py makemigrations
python3 manage.py migrate

## step -4 runserver

python3 manage.py runserver

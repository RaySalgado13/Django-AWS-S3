# Django-AWS-S3
Simple photo album project built in Django using static files and ASW S3 service

EXECUTE SERVER
python -m venv venv
./venv/Scripts/activate
pip install django
pip install pillow
pip install django-environ
pip install boto3
pip install django-storages
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

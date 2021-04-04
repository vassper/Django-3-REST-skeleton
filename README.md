# Django3-skeleton
Dev template on based Django 3.1.7
 + `django-environ==0.4.5`

## Use
+ git clone https://github.com/vassper/Django3-skeleton.git or wget https://github.com/vassper/Django3-skeleton/archive/refs/heads/master.zip and unzip
+ rename **/django3_skeleton** -> **/<my_project>**
+ cd /<my_project>
+ pip install requirements/dev.txt
+ python manage.py createsuperuser
+ python manage.py makemigrations
+ python manage.py migrate
+ python manage.py runserver 8000
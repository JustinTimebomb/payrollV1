# Wassup group members, here's how to install this thing.
So you download this folder ye, open your visual studio then open with this folder

**run this in your terminal:**
python -m venv venv
venv\Scripts\activate

**next, install dependenciies**
pip install -r requirements.txt

**then apply migrations**
python manage.py migrate

**this is optional, but this one's to create superuser for admin access**
python manage.py createsuperuser

**RUN THE DEVELOPMENT SERVER!!!**
python manage.py runserver

# Django-react

mkdir react-form-data && cd react-form-data
 
mkdir backend && cd backend
django-admin startproject backend .
cd .. && npx create-react-app frontend

backend env frontend

cd backend
pip install django djangorestframework django-cors-headers Pillow

python manage.py startapp post

python manage.py makemigrations
python manage.py migrate

python manage.py runserver

/*OPEN A SECON TERMINAL IN THE FRONT END DIRECTORY(DO NOT CLOSE THE FIRST*/

npm install axios

pm run start





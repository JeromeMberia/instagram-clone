release: python manage.py makemigrations insta
release: python manage.py migrate


web: gunicorn insta_project.wsgi --log-file -


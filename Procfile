release: python manage.py migraterelease: python manage.py makemigrations && python manage.py migrate
web: gunicorn student_management_project.wsgi --log-file - 

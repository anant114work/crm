web: gunicorn realty_dashboard.wsgi:application
release: python manage.py makemigrations && python manage.py migrate && python manage.py collectstatic --noinput && python create_admin.py
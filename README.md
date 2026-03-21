Django News Website

This is a news website dedicated to remarkable women, built using
Django, CSS, HTML, Bootstrap, Jinja2, and SQLite. Users can register
and, after authentication, create and publish posts about famous women.
The website features different categories, allowing users to browse
posts by specific topics. Additionally, pagination is implemented to
ensure a smooth and organized browsing experience.

Getting Started

1.  Clone the repository git clone https://github.com/Maaksym/Django.git

2.  Navigate to the project directory cd Django

3.  Create and activate a virtual environment python -m venv venv

Windows: venv

macOS/Linux: source venv/bin/activate

4.  Install dependencies pip install -r requirements.txt

5.  Set up environment variables

Create a .env file in the root directory and add:

SECRET_KEY=django-insecure-test-key DEBUG=True

6.  Apply migrations python manage.py migrate

7.  Create a superuser (optional) python manage.py createsuperuser

8.  Run the server python manage.py runserver

9.  Open in browser

Main page: http://127.0.0.1:8000/

Admin panel: http://127.0.0.1:8000/admin/

Features: - User authentication (login/register) - Create and publish
posts - Categories - Pagination - Admin panel


Main page:
http://127.0.0.1:8000/

Admin panel:
http://127.0.0.1:8000/admin/

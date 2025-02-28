Getting started with a Django project

1. Cloning a repository: Clone the repository to your computer using Git:
https://github.com/Maaksym/Django.git

2. Go to the project directory: Navigate to the project folder:
cd fsait

3. Create and activate a virtual environment: Create a new virtual environment (if not already created):
python -m venv venv

Activate it
For Windows:
venv\Scripts\activate

For macOS/Linux:
source venv/bin/activate

4. Setting dependencies: Install all dependencies specified in requirements.txt:
pip install -r requirements.txt

5. Setting up the database: Perform migrations to customize your database:
python manage.py migrate

6. Creating a superuser: If you want to create a superuser to access the Django admin:
python manage.py createsuperuser

Enter the username, email, and password for the superuser.

7. Start the server: Start the local Django server:
python manage.py runserver

8. Access to the project: Go to http://127.0.0.1:8000/ in your browser to see the live site.

To access the admin panel: http://127.0.0.1:8000/admin/, using superuser data.




# image-uploader-django

1. Steps to follow

2. Clone repository

3. Create Virtualenv Command - virtualenv YOUR_VIRTUAL_ENV_NAME

4. Activate virtual environment Command Prompt- YOUR_VIRTUAL_ENV_NAME\Scripts\activate.bat Power Shell- YOUR_VIRTUAL_ENV_NAME\Scripts\activate.ps1 UNIX/Linux/Mac Terminal- source    YOUR_VIRTUAL_ENV_NAME\bin\activate

5. Install dependencies (Supporting Packages) Either install individual packages Command (In virtual environment): pip install PACKAGE_NANE or install all packages at once from      requirements.txt Command (In virtual environment): pip install -r requirements.txt NOTE: This command will install all the supporting packages listed in requirements.txt files

6. Create Super User to access admin panel. Command Prompt (In virtual environment)- python manage.py createsuperuser complete the registration of super user by adding username  a    and password.

7. Run Migrations 1. makemigrations: This command will detect all the changes throughout the project model files Command Prompt (In virtual environment): python manage.py            makemigrations 2. migrate : This command will add new changes to database. Command Prompt (In virtual environment): python manage.py migrate

8. Run Server Command Prompt (In virtual environment): python manage.py runserver

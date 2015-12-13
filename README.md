
First you  need to install the Python Package Manager, pip https://pypi.python.org/pypi/pip


Requirments:

Django - pip install django

request - pip install requests

Bower - npm install -g bower

* In order to get NPM, simply install Node.js

Setup the database

                python manage.py migrate

Run the server
                python manage.py runserver
                
After the server has started visit - http://127.0.0.1:8000/app/profile/ 
to accesss the app.


# This app follows the MVC architecture as all the database files are in model.py , all the controller files are in views.py file and all the view i.e. templates are in the templates folder.

# This app uses github - REST API.

CS 3773 Project

Based on the FreeCodeCamp django+vue tutorial

## RUNNING LOCALLY ##

Prerequisites:
- Python 3.x
- NodeJS / npm
- Virtual environment (see next section)

### Set up virtual environment ###
- Start powershell
- Copy the requirements.txt to the djackets folder
- In the djackets folder, run this to make a virtual environment:
```
python -m venv .venv
```
- Activate the virtual environment by running "activate.ps1" in .venv/scripts/ 
- Run the following command to install all dependencies listed in requirements.txt
```
pip install -r path/to/requirements.txt
```

### Set up Vue stuff ###
- Start powershell
- Activate the virtual environment by running "activate.ps1" in .venv/scripts/
- Run the following commands:
```
npm install -g @vue/cli
cd djackets_vue
npm install axios
npm install bulma
```

### Starting the Django server ###
- Start powershell
- Activate the virtual environment by running "activate.ps1" in .venv/scripts/ 
- Start the server by running "python manage.py runserver" in djackets_django/

### Starting the Vue server ###
- Start powershell again (new instance)
- Activate the virtual environment by running "activate.ps1" in .venv/scripts/
- Start the server running "npm run serve" in djackets_vue/

Go to localhost:8080 for the customer-facing web page or localhost:8000/admin for the administrative page (superuser login is admin//deanza)

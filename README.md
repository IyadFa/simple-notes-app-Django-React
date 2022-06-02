<div align="center">
<img width="50%" src="http://i3.ytimg.com/vi/tYKRAXIio28/maxresdefault.jpg"/>

# Simple Notes App
</div>

### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/IyadFa/simple-notes-app-Django-React.git

```

--> Move into the directory where we have the project files : 
```bash
cd simple-notes-app-Django-React

```

--> Create a virtual environment :
```bash
# If you are on Windows
virtualenv env
# If you are on Linux or Mac
python -m venv env
```

--> Activate the virtual environment :
```bash
# If you are on Windows
.\env\Scripts\activate
# If you are on Linux or Mac
source env/bin/activate
```

#

### Running the App

--> To run the Notes App, we use :
```bash
python manage.py runserver
```

--> To create a superuser:
```bash
python manage.py createsuperuser
```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/
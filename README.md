# Sheetify Backend

# Installation
Run the following commands on a linux environment (Python 3 required):
```
bash build.sh
```
# Start server
python3 manage.py runserver localhost:8000
or
gunicorn orbital_backend.wsgi:application

# Known Issues
omnizart is currently bugged for Windows and only works on linux platforms. If on Windows, we suggest using WSL.

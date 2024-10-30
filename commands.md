## packages 

django
django-environ==0.11.2
djangorestframework==3.15.2
pytest==8.3.3
pytest-django==4.9.0


## django commands 

pip install 
pip freeze > requirements.txt
python.exe -m pip install --upgrade pip

## secret key

python 
import secrets
secret_key = secrets.token_urlsafe(50)  # Generate a random key
print(secret_key)


## Pytest

pytest -h  # prints options _and_ config file settings

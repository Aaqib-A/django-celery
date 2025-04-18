# django-celery
A Django project demonstrating django-celery and django-celery-beat.



## Setup:

1. To Create a Virtual Environment
```
python3 -m venv celery-venv
```

2. Activating virtual environment
```
# For Windows
.\celery-venv\Scripts\activate

# For Linux
source ./celery-venv/bin/activate
```
3. install package
```
pip install -r requirements.txt
```

4. Run The Server
```
python server.py 
python server.py -p 5001
python server.py --port 5002
```
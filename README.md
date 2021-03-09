use instructions:


1. git clone `git clone <this_git_url>`
2. make ur venv

```
py -m venv venv
venv\Scripts\activate.bat
```
& simply type `deactivate` to quit

3. `pip install requirements.txt`
4. cd to backend/server, then 
```
py manage.py migrate
py manage.py makemigrations
py manage.py runserver
``` 

and ur good, visit http://127.0.0.1:8000/api/v1/ in ur browser for api root

http://127.0.0.1:8000/api/v1/model/predict for predict view

# Django-chat-app
  A chat application built using django framework. Users can able to send messages through chat rooms. The user want to login by entering valid username and password. 
## Quick Start
  Create Virtual Environment
  ```
  pip install virtualenv
  ```
  
  Install Django `Channels`
```
 pip install django channels
```

Add app name `chat` to project `ChatApp`
```
python manage.py startapp chat
```

Run `python manage.py makemigrations` and `python manage.py migrate`

Run `server` and visit http://127.0.0.1:8000/auth/login/

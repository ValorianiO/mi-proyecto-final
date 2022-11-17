# Mi-proyecto-final

This is a web application, where photos of the city of Rosario will be published, edited or deleted and there will be a search engine to find a post. Only registered users will be able to access these functions.

## Installation:

```bash
  git clone https://github.com/ValorianiO/mi-proyecto-final.git .
  pip install -r requirements.txt
  python manage.py migrate
  python manage.py runserver
  http://127.0.0.1:8000/blog/index
```

## Creating a admin user:

```bash
    python manage.py createsuperuser
    # input info and done
    #current admin mail: cory@gmail.com, password: cory (fake mail)

```

## Things i learnt after creating this project

- CRUD functions on blog.
- django message or notification and showing pop messages.
- how authentication works, user login, logout etc.
- different UI for admin and non admin user.
- custom user model.
- and many more small things.

## Author:

- Osvaldo Valoriani

## Github:

https://github.com/ValorianiO/mi-proyecto-final
https://www.youtube.com/watch?v=5LRBUhPq3Sg

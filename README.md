# Polls app

## Introduce

This is a simple implementation of Django project which refers to [Django Documents](https://docs.djangoproject.com/zh-hans/3.0/intro/tutorial01/), accomplishing a polling app.

## Instructions

To use this web app, please read following parts.

### files tree

After cloned this project to your local directory, for example in `C:\Users\admin\Django`, the whole files structure seems like this(in the directory mentioned above):

\+ mysite
\+ polls
\+ db.sqlite3
\+ manage.py
\+ README.md

Before everything starts, you should check your python version and Django packages.

### run the server

Make sure you are in `.\Django`. Open a shell and enter the following instrution:

#### Windows

``` shell
...\> py manage.py runserver
```

#### Linus/Mac OS

``` shell
\$ python manage.py runserver
```

Now you may look at this web at [127.0.0.1:8000](127.0.0.1:8000)(actually there is nothing on this page). Please visit [polls](127.0.0.1/polls) for browsing polling questions and [admin](127.0.0.1/admin) for manage this web app. Besides, you can visit `127.0.0.1/polls/<question_id>` to vote for this question. You may edit questions by admin account.
If you are interested in this simple app, you can add more pages by editing URLs. For more information, please read Django documents.
To test this database, the advice is that use python shell to manipulate data. You can find useful information in Django documents or tutorials as well.

**Warning**
The administrator account of this web has been set already. If you want to create an account of your own, you may use `py manage.py createsuperuser`. Visit [Django Documents](https://docs.djangoproject.com/zh-hans/3.0/intro/tutorial02/) for more details.

# django-todo -source code forked from https://github.com/shreys7/django-todo.git
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/Shrikumar-Udupa/todo-torus.git
```
You will need python 2 or 3 and django to be installed in the server to run this app. Head over to https://www.djangoproject.com/download/ for the download guide
```bash
$ sudo apt install python3  ##Ubuntu
$ sudo yum install python3  ##Rhel / CentOS
```
```bash
$ pip install Django==3.2
```



Once you have downloaded python & django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

0.0.0.0:8080 - To make the app aviable to external user over port 8080

```bash
$ python manage.py runserver 0.0.0.0:8080
```

Once the server is hosted, head over to http://{IP-address}:8080/todos for the App.

Cheers and Happy Coding :)

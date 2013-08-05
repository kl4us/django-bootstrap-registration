django bootstrap registration template layout
====================

A starter project with bootstrapped forms, user registration and debug-toolbar included! 
There are other project layout like pinax but i don't like those because it is too much complicated for newbie django developer like me ... so, i made my own.

The project includes all required templates for:

	- login
	- registration
	- password change
	- password lost
	- account activation
	- ecc ...

Unlike pinax and other projects this project is based on django 1.5.1, django-registration (not django-user-accounts) and django-debug-toolbar.	

Example usage
=============

    $ virtualenv mysite-env --no-site-packages
    $ source mysite-env/bin/activate
    (mysite-env)$ pip install django==1.5.1
    (mysite-env)$ django-admin.py startproject --template=https://github.com/kl4us/django-bootstrap-registration/zipball/master mysite
    (mysite-env)$ cd mysite
    (mysite-env)$ pip install -r requirements.txt
    (mysite-env)$ python manage.py syncdb
    (mysite-env)$ python manage.py runserver

Hit http://127.0.0.1:8000 to view the site!
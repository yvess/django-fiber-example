============================
Django Fiber example project
============================

Installation:
=============

::

    $ git clone git://github.com/ridethepony/django-fiber-example.git
    $ cd django-fiber-example


Optional: you probably want to install this into a clean `virtualenv <http://pypi.python.org/pypi/virtualenv/>`_, which you can setup like this:

::

    $ virtualenv env
    $ source env/bin/activate


::

    $ pip install -r requirements.txt
    $ cp settings_example.py settings.py
    $ python manage.py syncdb
    $ python manage.py loaddata ./fixtures/example_initial_data.json
    $ python manage.py runserver 0:8000

Django Bootstrap datetimepicker
===============================

`Bootstrap <http://getbootstrap.com/>`_

`Bootstrap datetimepicker (Doc) <http://eonasdan.github.io/bootstrap-datetimepicker/>`_

`Bootstrap datetimepicker (Github) <https://github.com/Eonasdan/bootstrap-datetimepicker>`_

Requirements
------------

`Django <https://www.djangoproject.com/>`_ 1.4 or later

Installation
------------

::

    $ pip install django-static-bootstrap-datetimepicker==3.1.3

Setup
-----

Just add ``'django.contrib.staticfiles'`` and ``'django_static_bootstrap_datetimepicker'`` to INSTALLED_APPS in
your settings.py::

    INSTALLED_APPS = (
        # ...

        'django.contrib.staticfiles',
        'django_static_bootstrap_datetimepicker',

        # ...
    )

Refer to Django `static files <https://docs.djangoproject.com/en/dev/howto/static-files/>`_
documentation to configure and deploy static files.


Usage
-----

You can refer to bootstrap datetimepicker in your template with::

    {% load staticfiles %}
    {% static 'static_bootstrap_datetimepicker/js/bootstrap-datetimepicker.min.js' %}
    {% static 'static_bootstrap_datetimepicker/css/bootstrap-datetimepicker.min.css' %}

    {% static 'static_bootstrap_datetimepicker/css/bootstrap-datetimepicker.css' %}


Static files Bootstrap datetimepicker v3.1.3::

    static_bootstrap_datetimepicker/js/bootstrap-datetimepicker.min.js
    static_bootstrap_datetimepicker/css/bootstrap-datetimepicker.min.css
    static_bootstrap_datetimepicker/css/bootstrap-datetimepicker.css


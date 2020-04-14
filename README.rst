=============================
Django Frontend Presets
=============================

.. image:: https://badge.fury.io/py/django-frontend-presets.svg
    :target: https://badge.fury.io/py/django-frontend-presets

Django frontend presets provide a command that allow you to rapidly swap the front-end scaffolding of your application.
A basic starting point using Bootstrap, React, and / or Vue that will be helpful for many applications.

Quickstart
----------

Install Django Frontend Presets::

    pip install django-frontend-presets

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_frontend_presets.apps.DjangoFrontendPresetsConfig',
        ...
    )

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage

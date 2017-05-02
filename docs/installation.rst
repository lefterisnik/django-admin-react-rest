Installation
============

Getting the code
----------------

The recommended way to install the ``Admin View Permission`` is via pip_::

    $ pip install django-admin-view-permission

To test an upcoming release, you can install the in-development version
instead with the following command::

     $ pip install -e git+https://github.com/django-admin-view-permission/django-admin-view-permission.git#egg=django-admin-view-permission

Requirements
------------

* Django

Support
-------

* Django: 1.8, 1.9, 1.10, 1.11
* Python: 2.7, 3.4, 3.5, 3.6

Setup
-----

Make sure that ``'django.contrib.admin'`` is set up properly and add
``'admin_view_permission'`` to your ``INSTALLED_APPS`` setting::

    INSTALLED_APPS = [
        'admin_view_permission',
        # ...
        'django.contrib.admin',
        # ...
    ]

Finally, run ``python manage.py migrate`` to create the view permissions.

.. _pip: https://pip.pypa.io/
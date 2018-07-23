===============
Django Material
===============

Material design for Django.
https://github.com/viewflow/django-material

テストで動作させてみました。  
ほぼ公式のものをそのまま使用してます。  


- Python 3.6.5
- Django-Material 1.2.x compatible Django 2.0.7



Tested with:

.. image:: demo/static/img/browserstack_small.png
  :target:  http://browserstack.com/

Demo
====

http://forms.viewflow.io/

.. code:: bash

    git clone https://github.com/viewflow/django-material.git
    cd django-material

    python3 manage.py migrate --settings=demo.settings
    python3 manage.py loaddata demo/fixtures/* --settings=demo.settings
    python3 manage.py runserver 0.0.0.0:8000 --settings=demo.settings

Then you can go to http://127.0.0.1:8000/integration/ and login with
`admin:admin` username and password to the demo site.



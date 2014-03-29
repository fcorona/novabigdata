NOVABIGDATA
====================================

Plataforma que busca encontrar correlaciones entre apps de desarrolladores e indices que afectan a la Ciudad.

Python 2.7 Runtime Support
--------------------------
* Support for the Python 2.7 runtime was added to this project in May 2012.


About Flask
-----------
[Flask][flask] is a BSD-licensed microframework for Python based on
[Werkzeug][wz], [Jinja2][jinja2] and good intentions.

See <http://flask.pocoo.org> for more info.


Setup/Configuration
-------------------
1. Download this repository via
   `git clone git@github.com:kamalgill/flask-appengine-template.git`
   or download the tarball at
   <http://github.com/kamalgill/flask-appengine-template/tarball/master>
2. Copy the src/ folder to your application's root folder
3. Set the application id in `src/app.yaml`
4. Configure datastore models at `src/application/models.py`
5. Configure application views at `src/application/views.py`
6. Configure URL routes at `src/application/urls.py`
7. Configure forms at `src/application/forms.py`
8. Add the secret keys for CSRF protection by running the `generate_keys.py`
   script at `src/application/generate_keys.py`, which will generate the
   secret keys module at src/application/secret_keys.py


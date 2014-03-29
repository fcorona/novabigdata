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


Licencia:

The MIT License (MIT)

Copyright (c) <2014>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
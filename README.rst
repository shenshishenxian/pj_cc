P@rk
======


Install
-------
   
Create a virtualenv and activate it::
    go into the repo first
    python3 -m venv venv
    . venv/bin/activate

Or on Windows cmd::

    py -3 -m venv venv
    venv\Scripts\activate.bat

Install P@rk::(ignore this step)

    pip install -e .


Run
---

::

    export FLASK_APP=flaskr
    export FLASK_ENV=development
    flask run

Or on Windows cmd::

    set FLASK_APP=flaskr
    set FLASK_ENV=development
    flask run

Open http://127.0.0.1:5000 in a browser.



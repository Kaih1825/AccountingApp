# Accounting App

 An accounting app entirely developed in Python.

## 結構
```
AccountingApp
├── README.md
├── backend
│   ├── accounting_app
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── migrations
│   │   │   ├── 0001_initial.py
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── templates
│   │   │   ├── password_reset_form.html
│   │   │   └── password_reset_successful.html
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── accounting_system
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── api_reference.py
│   ├── db.sqlite3
│   ├── key.key
│   ├── manage.py
│   └── token.enc
├── config.json
└── frontend
    ├── AccountingAppGtk.iml
    ├── Templates
    │   ├── login_failure.html
    │   └── login_successful.html
    ├── __init__.py
    ├── login_server.py
    ├── main.py
    ├── reset_password_frontend.py
    ├── src
    │   └── google.png
    ├── ui.css
    └── ui.ui
```

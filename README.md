# **[Django Theme Soft PRO](https://appseed.us/product/soft-ui-design-pro/django/)**

**Django** starter styled with **[Django Theme Soft PRO](https://appseed.us/product/soft-ui-design-pro/django/)**, a premium `Bootstrap 5` design from [Creative-Tim](https://bit.ly/3fKQZaL)
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. 

> 👉 **NOTE**: This product `requires a License` in order to access the theme:

**Private REPO**: `git+https://github.com/app-generator/priv-django-theme-soft-pro`

<br />

## Features: 

- **UI Kit**: Soft Design BS5 PRO `v1.1.1` by Creative-Tim
- [Django Soft Design PRO](https://appseed.us/product/soft-ui-design-pro/django/) - `sample project`
- **Sections Covered**: 
  - `All pages` managed by `Django.contrib.AUTH`
  - `Registration` page
  - `Misc pages`: colors, icons, typography, blank-page 

<br />

![Soft UI Design PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168812715-52e036b7-582d-4851-9657-6b1f99727619.png)

<br />

## Why `Django Theme Soft PRO`

- Modern [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) Design
- `Responsive Interface`
- `Minimal Template` overriding
- `Easy integration`

Designed for those who like bold elements and beautiful websites. Made of hundred of elements, designed blocks, and fully coded pages, **Soft UI Design PRO** is ready to help you create stunning websites and web apps.

<br />

## How to use it

<br />

> **Install the package** via `PIP` 

```bash
$ pip install git+https://github.com/app-generator/priv-django-theme-soft-pro.git
```

<br />

> Add `theme_soft_pro` application to the `INSTALLED_APPS` setting of your Django project `settings.py` file:

```python
INSTALLED_APPS = [
    "django.contrib.admin",
    "django.contrib.auth",
    "django.contrib.contenttypes",
    "django.contrib.sessions",
    "django.contrib.messages",
    "django.contrib.staticfiles",

    'theme_soft_pro',          # <-- NEW 
]
```

<br />

> Add `LOGIN_REDIRECT_URL` and `EMAIL_BACKEND` of your Django project `settings.py` file:

```python
    LOGIN_REDIRECT_URL = '/'
    # EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
    EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'
```

<br />

> Add `theme_soft_pro` urls in your Django Project `urls.py` file

```python
    from django.urls import path, include

    urlpatterns = [
        ...
        path('', include('theme_soft_pro.urls')),
    ]
```

<br />

> **Collect static** if you are in `production environment`:

```bash
$ python manage.py collectstatic
```

<br />

> **Start the app**

```bash
$ # Set up the database
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Create the superuser
$ python manage.py createsuperuser
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
```

Access the `admin` section in the browser: `http://127.0.0.1:8000/`

<br />

---
**[Django Theme Soft PRO](https://appseed.us/product/soft-ui-design-pro/django/)** - Modern Theme provided by **[AppSeed](https://appseed.us/)**

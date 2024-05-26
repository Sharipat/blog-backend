# Blog from Lisa

Blog on Django, server side.

## Launch

To start a blog, you must already have Python 3 installed.

- Download the code
- Install dependencies with the command `pip install -r requirements.txt`
- Start the server with the command `python3 manage.py runserver`

After that, follow the link [127.0.0.1:8000](http://127.0.0.1:8000), you will see the main page.

## Environment variables

Some of the project settings are taken from environment variables. To define them, create a `.env` file next to `manage.py` and write the data there in the following format: `VARIABLE=value`.

**These settings are not required to run the project**, the values are already set by default.

The following variables are available:
- `DEBUG` - debug mode. Set to `True` to see debugging information in case of an error. Disabled with the value `False`.
- `SECRET_KEY` — secret key of the project. For example: `erofheronoirenfoernfx49389f43xf3984xf9384`.
- `ALLOWED_HOSTS` - see [Django documentation](https://docs.djangoproject.com/en/3.1/ref/settings/#allowed-hosts).
- `STATIC_URL` - by default it is `'/static/'`. [What is STATIC_URL](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-STATIC_URL).
- `STATIC_ROOT` - by default it is `'None'`, i.e. current folder. [What is STATIC_ROOT](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-STATIC_ROOT).
- `MEDIA_URL` - by default it is `'/media/'`. [What is MEDIA_URL](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-MEDIA_URL).
- `MEDIA_ROOT` - by default this is `'media'`. [What is MEDIA_ROOT](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-MEDIA_ROOT).

## Project goals

The code is written for educational purposes - this is a lesson in the course on Python and web development on the site [Devman](https://dvmn.org).
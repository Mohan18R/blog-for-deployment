# Flask Blog Application

This repository contains a Flask-based blog application with rich text editing, user authentication, and more. The application is designed to be easily deployed using Gunicorn and PostgreSQL.

## Features

- **Bootstrap for Styling**: Utilizes `Bootstrap-Flask` for responsive and modern UI.
- **Rich Text Editor**: `Flask-CKEditor` is integrated for WYSIWYG text editing.
- **User Authentication**: `Flask-Login` for user session management and authentication.
- **User Avatars**: `Flask-Gravatar` for generating user avatars.
- **Forms Handling**: `Flask-WTF` and `WTForms` for form validation and rendering.
- **Database Integration**: Uses `Flask-SQLAlchemy` and `SQLAlchemy` for ORM and database interactions.
- **Deployment**: Configured to run with `Gunicorn` and `psycopg2-binary` for PostgreSQL database connectivity.

## Requirements

The following Python packages are required for this project:

- `Bootstrap-Flask==2.3.3`
- `Flask-CKEditor==0.5.1`
- `Flask-Login==0.6.3`
- `Flask-Gravatar==0.5.0`
- `Flask-WTF==1.2.1`
- `WTForms==3.0.1`
- `Werkzeug==3.0.0`
- `Flask==2.3.2`
- `Flask-SQLAlchemy==3.1.1`
- `SQLAlchemy==2.0.25`
- `gunicorn==21.2.0`
- `psycopg2-binary==2.9.9`

## Hosted Version

You can view the live version of the blog application [here](https://blog-for-deployment-2.onrender.com/post/1).

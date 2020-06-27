---
id: setting-dev-environment
title: Setting Dev Environment
sidebar_label: Setting Development Environment
---

## Getting Up and Running Locally

Make sure to have following things in you host:

- Python >3
- PostgreSQL
- virtualenv

Start with installation

1. Create folder and virtualenv for python

```bash
mkdir project_name
cd project_name
virtualenv venv
source venv/bin/activate
```

2. Clone [django-boiplerplate repo](https://github.com/viral-sangani/django-boilerplate) from github.

3. Install dependencies

```bash
pip install -r requirements.txt
git init # A git repo is required for pre-commit to install
pre-commit install
```

You are done with installation, but you cannot start the project yet, You need to create a database in PostgreSQL first.

- You need to edit the `.env` file in the root directory and add DATABASE URL to make in functional.

```env
DATABASE_URL=postgresql://<user>:<password>@<host url>:5432/<db-name>
```

> You are running PostgreSQL locally, then you `host url` will be localhost.

4. Apply migrations

```bash
python manage.py migrate
```

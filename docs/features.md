---
id: features
title: All the features
---

export const Highlight = ({children, color}) => ( <span style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>{children}</span> );

Suppose that you want to create Twitter Clone. Instead of doing `startproject`, and then configuring User model, Email service, Logging, Static and Media file handling, Error handling and ofcourse security which always get forgotton untill the worst moment possible, would it be great if you get the pre-configured project with all these functionalities. That's what [django-boilerplate](https://github.com/viral-sangani/django-boilerplate) is here for.

- Build for Django <Highlight color="#25c2a0">3.0</Highlight>
- Works with Python <Highlight color="#25c2a0">3.8</Highlight>
- Renders Boilerplate Django projects with 98% starting test coverage
- [12-Factor](http://12factor.net/) based settings using [django-environ](https://github.com/joke2k/django-environ)
- We belive in SSL, secure by default in Production.
- Comes with custom user model
- Media storage with [AWS S3](https://aws.amazon.com/s3/) in Production
- Static file handling via [AWS S3](https://aws.amazon.com/s3/) in Production
- Already written test in unittest and pytest
- Registration using [django-allauth](https://github.com/pennersr/django-allauth)
- Custom and optimized settings for development and production
- SMTP already configired for [AWS SES](https://aws.amazon.com/ses/). ([Mailgun](https://www.mailgun.com/), [Anymail](https://anymail.readthedocs.io/en/stable/) is optional)
- Currently only works with PostgreSQL
- [pre-commit](https://github.com/pre-commit/pre-commit) already configured for identifying simple issues
- [Sentry](https://sentry.io/welcome/) intregration already configures for error logging
- Instaructions to deploy on [PythonAnywhere](https://www.pythonanywhere.com/)

> **Docker Integration Comming soon**  
> **Celery Integration Comming soon**  
> **Async functions with socketio Comming soon**

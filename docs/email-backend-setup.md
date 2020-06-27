---
id: email-backend-setup
title: Setting up Email backnd
sidebar_label: Email Backend Setup
---

This boilerplate is setup to use AWS SES and backend to send email, but you can easily change it in settings file.

[Follow this article](https://docs.aws.amazon.com/ses/latest/DeveloperGuide/send-email-smtp.html) to setup SES on AWS console.

> By default Email backend is set to `EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'` in development, but you can change to `EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'` to ease.
> If you go with `EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'`, then you do not need to configure AWS SES.

Once you get USERID and Secret for AWS SES SMTP, you can edit `.env` file.

```bash
EMAIL_HOST_USER=<AWS SES SMTP USER ID>
EMAIL_HOST_PASSWORD=<AWS SES SMTP USER PASSWORD>
```

Congratulations, you have made it! Keep on reading to unleash full potential of django-boilerplate.

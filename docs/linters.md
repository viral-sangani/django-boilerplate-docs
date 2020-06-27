---
id: linters
title: Linters
sidebar_label: Linters
---

### flake8

To run flake8:

```bash
flake8
```

The config for flake8 is located in setup.cfg. It specifies:

- Set max line length to 120 chars
- Exclude `.tox,.git,*/migrations/*,*/static/CACHE/*,docs,node_modules`

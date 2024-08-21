# Odoo Docker

Ce dépôt permet de facilement monter des environnement de développement Odoo en local.

Pour la version 16.0, le Dockerfile utilise Python 3.9 (python:3.9-slim-bullseye), car Python
3.10 pose problème. Lors de l'installation des requirements, on obtient cette erreur :

```
ERROR: Failed to build installable wheels for some pyproject.toml based projects (gevent)
```
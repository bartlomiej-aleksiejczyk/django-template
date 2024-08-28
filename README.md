# Django Simple Project Template

## Overview

This app was created using django simple project template

## Template Content

This template includes:

- Django
- PostgreSQL
- Docker Compose integration
- Working Auth without registration
- Fail2Ban integration
- Precoinfigured templates and static files
- Huey configured as message queue

## Command Passthrough

```
docker compose exec django <your-command-content>
```

examples:

```
docker compose exec django pip freeze > requirements.txt
```

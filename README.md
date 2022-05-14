# Boilerplate for django backend
## Quick overview

- Django
- Django rest framework
- Postgres
- Docker
- Docker-compose
- Pytest
- Black
- Flake8
- Mypy with django and drf plugins
- Isort
- Poetry
- Github pipeline
- Pre-commit
- Exported pycharm settings

### How to use it

1. `example`is used everywhere as a name of the project, so please `ctrl+f` in all project files and replace it with the name of your project
2. create a poetry env via `poetry install`
3. shell into poetry env and install pre-commit hooks via `pre-commit install`
4. run `docker compose up -d`. Wait a bit, and your app should be hosted on `localhost`

Optional
1. import pycharm settings
2. adjust github settings for your repo, such as mandatory success on pipeline in PRs

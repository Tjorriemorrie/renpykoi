# renpykoi

Renpy files generator

## Installation

1. Clone the repository.
2. Create virtual env.
3. Install dependencies.
4. Set up database.

```bash
git clone https://github.com/Tjorriemorrie/renpykoi.git
cd renpykoi
pyenv local 3.13.1
python -m venv .venv
.\.venv\Scripts\activate
python -m pip install -U pip
pip install -r requirements.txt
python manage.py migrate
```

Run the app

```bash
python manage.py runserver 8246
```

## Contribution

 Create a pull request as normal. The repo follows the rules as set out in the project.toml,
thus ensure you ran `pre-commit install` if you do any dev work on the app.

## Tech Stack

1. Django 4.0.4
2. Bootstrap 5.0.2
3. jQuery 3.6.0
4. Chart.js v3.9.1
5. Animate.css 4.1.1

6. Create a virtual environment and activate it (Windows)

```bash
python -m venv env
```

```bash
env\Scripts\activate
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

> **Note:** If you're using newer versions of python(3.10+), you may need to add the `--use-deprecated=legacy-resolver` option when installing dependencies with `pip` to avoid errors :

```bash
pip install -r requirements.txt --use-deprecated=legacy-resolver
```

3. Make migrations and migrate

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

4. Create admin/superuser

```bash
python manage.py createsuperuser
```

5. Finally run the project

```bash
python manage.py runserver
```

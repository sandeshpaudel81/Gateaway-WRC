# Gateway WRC - Event Information System

## Django-project

This is the web application based on **Django** framework to allow clubs, student unions of WRC to upload the details of their events and allow students to see all events happening in WRC in single platform.

# To run the project locally, do the usual.

# How To Set Up Django Ledger for Development

1. Navigate to your projects directory.
2. Clone the repo from github and CD into project.

```shell
git clone https://github.com/sandeshpaudel81/Gateway-WRC.git && cd gatewayWRC
```

3. Install python and virtualenv, if not already installed:

```shell
pip install virtualenv
```

Or

```shell
python -m venv myenv
```

4. Create virtual environment.

```shell
virtualenv myenv
```

5. Activate environment (in Windows):

```shell
myenv/Scripts/activate
```

6. Install dependencies

```shell
pip install -r requirements.txt
```

7. Apply migrations.

```shell
python manage.py makemigrations
python manage.py migrate
```

8. Create a Development Django user.

```shell
python manage.py createsuperuser
```

9. Run development server.

```shell
python manage.py runserver
```

:nerd_face: Sandesh Paudel
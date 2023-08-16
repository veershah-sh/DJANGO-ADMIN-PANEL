# Process to build
<hr>

- Create Virtual enviroment
    ```python
    python -m venv env
    ```

- Activate virtual enviroment
    ```python
    env\Scripts\acivate  # for windows
    source env/bin/activate # for mac & linux
    ```

- Start new django project
    ```python 
    django-admin startproject <project_name>
    ```

- Start new app
    ```python
    cd <project_dir>
    python manage.py startapp <app_name>
    ```

- create superuser
    ```python
    python manage.py createsuperuser
    ```

- make initial migrations
    ```python
    python manage.py makemigrations
    python manage.py migrate
    ```
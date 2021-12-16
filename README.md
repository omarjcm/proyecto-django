# proyecto-django

## Pasos preliminares 

### Para crear un entorno virtual de Python
> python -m venv entorno

### Para activar un entorno virtual de Python 
> .\entorno\Scripts\activate

### Para desactivar un entorno virtual de Python
> deactivate

### Para instalar django en el armbiente virtual
> pip install django -U

> pip install psycopg2

> pip install Pillow

### Comprobar las dependencias
> pip freeze

### Creacion del proyecto 
> django-admin startproject ups

### Configurar la aplicacion
Ingresar a la carpeta del proyecto.

> cd ups

> python manage.py migrate

En este momento, se encuentran las tablas de autenticacion en la base de datos.

### Creacion de super usuario
Para la creacion de usuario, se deben ingresar los siguientes datos: usuario, email y clave.

> python manage.py createsuperuser

### Creacion del modulo users 
> python manage.py startapp users

> python manage.py startapp posts



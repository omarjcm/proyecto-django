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

Para realizar cambios en el archivo de configuracion del proyecto django antes de la base de datos se debe utilizar la siguiente linea de comando.

> python manage.py makemigrations

Luego, de ejecutar esta linea de comando, nuevamente se aplica la linea de comando para sincronizar el modelo en django con respecto a la Base de Datos.

### Creacion de super usuario
Para la creacion de usuario, se deben ingresar los siguientes datos: usuario, email y clave.

> python manage.py createsuperuser

### Creacion del modulo users 
> python manage.py startapp users

> python manage.py startapp posts



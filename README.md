# first_django

python3 --version

Python 3.12.3

pip --version

pip 24.0 from /usr/lib/python3/dist-packages/pip (python 3.12)

# 2. Crear un entorno virtual llamado: proyecto_django.

python3 -m venv proyecto_django


source proyecto_django/bin/activate

pip list
pip install django

python -m django --version
5.1.3

pip --help

## PARTE 2

Explicación de los comandos en Django:

makemigrations: Crea los archivos de migración necesarios para reflejar los cambios realizados en los modelos en la base de datos.
python manage.py makemigrations

migrate: Aplica las migraciones pendientes a la base de datos, sincronizando los cambios realizados en los modelos.
python manage.py migrate

shell: Inicia una consola interactiva de Python con el entorno de Django configurado. Ideal para probar código o realizar consultas.

python manage.py shell

dbshell: Abre una consola interactiva para interactuar directamente con la base de datos configurada en el proyecto.

python manage.py dbshell

showmigrations: Lista todas las migraciones disponibles y muestra su estado (aplicadas o pendientes).

python manage.py showmigrations

dumpdata: Exporta los datos de la base de datos a un archivo JSON o formato especificado.

python manage.py dumpdata > datos.json

test: Ejecuta las pruebas definidas en las aplicaciones del proyecto.

python manage.py test

testserver: Inicia el servidor de desarrollo utilizando un conjunto específico de datos (fixtures).

python manage.py testserver fixture_file.json

diffsettings: Muestra las diferencias entre los valores predeterminados de configuración de Django y los valores personalizados del proyecto.

python manage.py diffsettings

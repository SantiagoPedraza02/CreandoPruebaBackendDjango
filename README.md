# CreandoPruebaBackendDjango
En este repo me inclinare por aprender a crear el backend utilizando django
PASOS PARA CREAR Y CONFIGURAR DJANGO

1.CREAR Y ACTIVAR ENTORNO VIRTUAL
Instalar modulo para crear el entorno VIRTUAL
    pip install virtualenv
Creando los paquetes de python
    python -m venv env
Para seleccionar el entorno del script activate.bat
    Apretar f1 y escribir python interpreter, seleccionar lo que aparece

2.CREAR EL PROYECTO EN DJANGO
Instalar DJANGO 
    pip install django 
crear carpeta del PROYECTO
django-admin startproyect -->'Nombre del PROYECTO' . en mi caso django_crud_api, El '.' se agrega para que no lo cree dentro de venv asi crea los archivos al inicio

3. COMO EJECUTAR EL PROYECTO
SE EJECUTA DE ESTA MANERA
    python manage.py runserver

4.COMO INICIAR UNA APLICACION
EL COMANDO QUE SE UTILIZA ES
    python manage.py startapp 'El nombre de la app', en mi caso la llamo tasks
Luego dentro de settings.py se agrega el nombre de la app

5.CREAR LAS TABLAS QUE NECESITE EL PROYECTO
    python manage.py migrate

6.COMO CREAR API CON DJANGO FRAMEWORK

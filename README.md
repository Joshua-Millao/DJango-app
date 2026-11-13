1. Instalar Python 3.12

En CMD:

winget install Python.Python.3.12

Cuando termine, cierra CMD y abre uno nuevo.

2. Clonar proyecto dentro de una carpeta - Debes crear la carpeta 
	
	git clone https://github.com/ericRailef/APP-TAREAS-102-4A.git

	
3. Entrar a tu proyecto

cd ruta dentro del proyecto

4. Crear el venv con Python 3.12

Aquí está la parte importante:

py -3.12 -m venv venv


5. Activarlo

venv\Scripts\activate

Verás:

(venv) C:\Users\Usuario\Desktop\desplegar_proyecto\App-Tareas>

6. INSTALA LAS DEPENDENCIAS

pip install -r requirements.txt


7. Instala la nueva librería

python -m pip install Django==5.0.14 djangorestframework==3.15.2


8. Levantar los servicios de XAMPP

crear el nombre de la bd


9. Migrar las tablas en la BD

python manage.py migrate


10. Levantar tu app Django

python manage.py runserver


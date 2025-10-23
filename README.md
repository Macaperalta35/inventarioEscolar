Inventario Escolar
Aplicación web básica para la gestión de inventario de equipos tecnológicos utilizando Django.

Descripción
Este proyecto permite registrar, consultar y administrar equipos tecnológicos de un colegio mediante el panel de administración de Django y una base de datos. El objetivo es reemplazar el registro manual en planillas por una solución web eficiente y centralizada.

Enlace del repositorio
https://github.com/usuario/repositorio

Instalación y uso
Clona el repositorio:

text
git clone https://github.com/usuario/repositorio.git
cd inventario_escolar
Instala las dependencias:

text
pip install -r requirements.txt
Aplica migraciones:

text
python manage.py makemigrations
python manage.py migrate
Crea un superusuario:

text
python manage.py createsuperuser
Ejecuta el servidor de desarrollo:

text
python manage.py runserver
Accede a la administración desde http://127.0.0.1:8000/admin/

Modelo Equipo
nombre (CharField)

categoria (CharField)

estado (CharField)

fecha_ingreso (DateField)

ubicacion (CharField)

Autor
Macarena Peralta


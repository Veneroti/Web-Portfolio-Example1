# Web-Portfolio-Example1
Repositorio de Web en DJANGO para PortFolio con Formulario de Contacto - Example 1 Con Administración

Python 3.7.1
Django 2.1.4

Source Code Editor: Visual Studio Code

Server Mail: Mailtrap

Web – Ejemplo 1

La web fue construida en Django un framework de desarrollo web de código abierto, escrito en Python. Más información: https://es.wikipedia.org/wiki/Django_(framework)
Modelo web para usar como presentación de trabajos realizados (Portafolio Web), dividida en:
-	Portada: Presentación de la Web, con texto principal de ejemplo.

-	Acerca de:  Biografía del Autor


-	Portafolio: Curriculo de trabajos, insertándolos con una App integrada con Panel de Administración para agregar los proyectos.
Requiriendo: Titulo, Descripción, Imagen, Dirección Web (Opcional).

-	Contacto: Formulario de Contacto, creada por una App integrada y configurada a una cuenta de Mailtrap, para visualizar el funcionamiento del envió del mensaje. (# Mailtrap Configuración en Settings.py)

Para probar la web, tener instalado Python y Django con las versiones ultimas.
Comandos a seguir:
 $python manage.py migrate 
(Para migrar los archivos)
 $python manage.py createsuperuser
(Creando Super Usuario para iniciar seccion en el panal de Administracion “/admin/”)
 $python manage.py runserver
(Iniciando servidor web e Ingresando a la web con la URL)

Probar Web:

http://veneroti.pythonanywhere.com/ (Con el servidor free de Pythonanywhere)

Panel de Admin:
http://veneroti.pythonanywhere.com/admin/

Cuenta: Admin
Contraseña: Admin


Saludos


# Pirotecnia Ecommerce

Este proyecto Django, llamado Pirotecnia Ecommerce, está diseñado para gestionar la venta de pirotecnia para las Fallas de Valencia en 2025. Se espera una alta demanda de usuarios simultáneos, por lo que se ha priorizado la optimización y la limpieza del código para garantizar un rendimiento óptimo.

## Tecnologías Utilizadas:
- Django: Framework de desarrollo web de alto nivel que fomenta el desarrollo rápido y limpio.
- Django Rest Framework: Potente kit de herramientas para la construcción de APIs web.
- PostgreSQL: Sistema de gestión de bases de datos relacional robusto y altamente escalable.
- Poetry: Herramienta de administración de dependencias, paquetes Python y entornos virtuales.
- Black: Formateador de código Python para mantener una base de código limpia y uniforme.


## Instalación y Ejecución:
1. Clona este repositorio
2. Navega al directorio del proyecto: `cd pirotecniaecommerce`
3. Instala las dependencias utilizando Poetry: `poetry install`
4. Crea y configura tu archivo `.env` basado en el archivo `.env.example` proporcionado.
5. Ejecuta las migraciones de la base de datos: `python manage.py migrate`
6. Inicia el servidor de desarrollo: `python manage.py runserver`


## Formateo de Código con Black

Para mantener un estilo de código consistente y limpio en este proyecto, utilizamos Black, una herramienta de formateo de código en Python.
Antes de hacer commit y pushear al repositorio es obligatorio ejecutar el comando

`black .` - para todos los ficheros del project

`black file.py file2.py` - para un fichero en especifico o varios
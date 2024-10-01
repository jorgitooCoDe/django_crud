# Proyecto de Gestión de Proyectos

Este es un proyecto de gestión de proyectos que utiliza un frontend en React y un backend en Django REST Framework. La aplicación permite agregar, editar, eliminar y listar proyectos.

## Tecnologías Utilizadas

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Django, Django REST Framework
- **Base de Datos**: SQLite (por defecto)

## Requisitos

- Node.js
- Python 3.x
- Django

## Instalación

### Backend

1. Clona el repositorio:
   ```bash
   git clone git@github.com:jorgitooCoDe/django_crud.git
2. Crea y activa un entorno virtual:
  ```bash
  python -m venv env
  source env/bin/activate
  ```
3. Instala las dependencias:
  ```bash
  pip install -r requirements.txt
  ```
4.  Realiza las migraciones y ejecuta el servidor:
  ```bash
  python manage.py migrate
  python manage.py runserver
  ```

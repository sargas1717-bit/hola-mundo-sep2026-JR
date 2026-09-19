# Hola Mundo

Bienvenido a este proyecto Django para una aplicación web sencilla con una página de inicio. Este repositorio está diseñado como base clara y limpia para empezar a desarrollar con Django, con una estructura de proyecto ordenada y fácil de ampliar.

## ✨ Descripción general

La aplicación cuenta con:

- Framework principal: Django
- Aplicación principal: `pages`
- Plantilla de inicio: `home.html`
- Base de datos: SQLite por defecto
- Configuración modular para crecimiento del proyecto

Este proyecto sirve como punto de partida ideal para proyectos pequeños, landing pages, portales básicos o prototipos de aplicaciones web.

---

## 🏗️ Estructura del sistema

```text
hola-mundo/
├── db.sqlite3
├── manage.py
├── requirements.txt
├── README.md
├── django_base/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── pages/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── migrations/
│       └── __init__.py
└── templates/
    └── home.html
```

### Descripción de cada componente

- `manage.py`: comando principal para ejecutar tareas de Django.
- `django_base/`: configuración general del proyecto.
- `settings.py`: ajustes del proyecto, apps instaladas y configuración de base de datos.
- `urls.py`: rutas globales del sitio.
- `pages/`: módulo de la aplicación principal.
- `views.py`: lógica de las vistas del sitio.
- `urls.py` dentro de `pages`: rutas específicas de la app.
- `templates/`: archivos HTML reutilizables.
- `home.html`: vista inicial de la página principal.

---

## ⚙️ Requisitos

Antes de comenzar, asegúrate de tener instalado:

- Python 3.10 o superior
- pip
- Virtualenv o venv (recomendado)
- Git

---

## 🚀 Instalación

1. Clona el repositorio:

```bash
git clone <url-del-repositorio>
cd hola-mundo
```

2. Crea un entorno virtual:

```bash
python -m venv venv
```

3. Activa el entorno virtual:

- En Windows:

```bash
venv\Scripts\activate
```

- En macOS/Linux:

```bash
source venv/bin/activate
```

4. Instala las dependencias:

```bash
pip install -r requirements.txt
```

5. Ejecuta las migraciones:

```bash
python manage.py migrate
```

6. Inicia el servidor:

```bash
python manage.py runserver
```

7. Abre en el navegador:

```text
http://127.0.0.1:8000/
```

---

## 🧩 Funcionamiento del sistema

El proyecto sigue la estructura típica de Django:

- La ruta principal se define en `pages/urls.py`
- La vista asociada se maneja en `pages/views.py`
- La plantilla renderizada es `templates/home.html`
- La configuración del sitio se centraliza en `django_base/settings.py`

Actualmente la aplicación muestra una vista inicial con el texto: "Hola, Mundo".

---

## 🛠️ Comandos útiles

```bash
python manage.py runserver
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py test
```

---

## 📌 Estado del proyecto

Este proyecto se encuentra en una etapa inicial, lista para ser extendida con:

- modelos y bases de datos personalizados
- formularios
- autenticación de usuarios
- administración con Django Admin
- templates más avanzados
- carga de archivos estáticos y CSS
- APIs REST o lógica empresarial adicional

---

## 👥 Contribución

Si deseas colaborar, puedes:

1. Crear una rama nueva
2. Desarrollar la funcionalidad
3. Realizar pruebas
4. Enviar un pull request con una descripción clara

---

## 📄 Licencia

Este proyecto no especifica licencia por defecto. Si se va a usar en producción, se recomienda definir una licencia adecuada (por ejemplo, MIT).

---

## 🚀 Resumen

Es una base sólida para iniciar un proyecto web con Django, con organización clara, configuración mínima y espacio para crecer sin perder estructura.

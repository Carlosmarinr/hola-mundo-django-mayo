# 🚀 Hola Mundo Django

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.0+-green.svg)](https://www.djangoproject.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Un proyecto simple de Django para demostrar la funcionalidad básica de "Hola Mundo" en una aplicación web.

## 📋 Descripción

Este proyecto es una aplicación Django básica que muestra una página de "Hola Mundo" utilizando el sistema de plantillas de Django. Está diseñado para principiantes que quieren aprender los fundamentos de Django o como punto de partida para proyectos más complejos.

## ✨ Características

- ✅ Configuración simple de Django
- ✅ Estructura básica de aplicación
- ✅ Renderizado de plantillas
- ✅ Base de datos SQLite integrada
- ✅ Servidor de desarrollo incluido
- ✅ Estructura modular y escalable

## 🛠 Instalación

Sigue estos pasos para configurar el proyecto en tu máquina local:

### Prerrequisitos

- Python 3.8 o superior
- Git (opcional, para clonar el repositorio)

### Pasos de Instalación

1. **Clona el repositorio** (si aplica):
   ```bash
   git clone https://github.com/tu-usuario/hola_mundo_django.git
   cd hola_mundo_django
   ```

2. **Crea un entorno virtual**:
   ```bash
   python -m venv venv
   # En Windows:
   venv\Scripts\activate
   # En macOS/Linux:
   source venv/bin/activate
   ```

3. **Instala las dependencias**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Ejecuta las migraciones de la base de datos**:
   ```bash
   python manage.py migrate
   ```

5. **Inicia el servidor de desarrollo**:
   ```bash
   python manage.py runserver
   ```

6. **Visita la aplicación**:
   
   Abre tu navegador y ve a: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

   ¡Deberías ver la página "Hola Mundo"!

## 📁 Estructura del Proyecto

```
hola_mundo_django/
├── 📁 base_project/          # Configuración principal del proyecto Django
│   ├── __init__.py
│   ├── asgi.py              # Configuración ASGI
│   ├── settings.py          # Configuraciones del proyecto
│   ├── urls.py              # URLs principales
│   └── wsgi.py              # Configuración WSGI
├── 📁 pages/                 # Aplicación Django para páginas
│   ├── __init__.py
│   ├── admin.py             # Configuración del admin
│   ├── apps.py              # Configuración de la app
│   ├── models.py            # Modelos de datos
│   ├── tests.py             # Pruebas unitarias
│   ├── urls.py              # URLs de la app
│   ├── views.py             # Vistas (lógica)
│   └── 📁 migrations/       # Migraciones de base de datos
│       └── __init__.py
├── 📁 templates/             # Plantillas HTML
│   └── index.html           # Página principal
├── db.sqlite3                # Base de datos SQLite
├── manage.py                 # Script de gestión de Django
├── requirements.txt          # Dependencias de Python
└── README.md                 # Este archivo
```

## 🏗 Tecnologías Utilizadas

- **Django** - Framework web de Python
- **Python** - Lenguaje de programación
- **SQLite** - Base de datos relacional ligera
- **HTML5** - Lenguaje de marcado para la web
- **CSS3** - Hojas de estilo para el diseño

## 🚀 Uso

### Comandos Básicos de Django

- **Ejecutar el servidor**: `python manage.py runserver`
- **Crear una nueva app**: `python manage.py startapp nombre_app`
- **Crear migraciones**: `python manage.py makemigrations`
- **Aplicar migraciones**: `python manage.py migrate`
- **Crear superusuario**: `python manage.py createsuperuser`
- **Acceder al admin**: Ve a `/admin/` después de crear un superusuario

### Personalización

Para personalizar la página principal, edita el archivo `templates/index.html`. Para agregar nuevas páginas, modifica `pages/views.py` y `pages/urls.py`.

## 🤝 Contribuyendo

¡Las contribuciones son bienvenidas! Para contribuir:

1. 🍴 Haz un fork del proyecto
2. 🌿 Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. 💾 Haz commit de tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Haz push a la rama (`git push origin feature/AmazingFeature`)
5. 🔄 Abre un Pull Request

### Guías de Contribución

- Sigue las mejores prácticas de Django
- Escribe pruebas para nuevas funcionalidades
- Actualiza la documentación según sea necesario
- Usa commits descriptivos

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Contacto

Si tienes preguntas o sugerencias, no dudes en abrir un issue en este repositorio.

---

⭐ Si te gusta este proyecto, ¡dale una estrella!

Hecho con ❤️ usando Django
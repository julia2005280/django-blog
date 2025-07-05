# 📝 Proyecto Final - Blog Personal en Django

Este es un blog personal desarrollado con Django como proyecto final del curso. La aplicación permite a los usuarios registrarse, iniciar sesión, crear, editar y eliminar publicaciones de blog, así como enviar mensajes entre usuarios.

---

## 📌 Funcionalidades principales

- 🏠 Vista de inicio (`/`)
- 👤 Vista "Acerca de mí" (`/about/`)
- 📄 Listado de páginas/blogs (`/pages/`)
- 🔍 Vista de detalle de cada página
- ➕ Crear página (requiere login)
- ✏️ Editar / 🗑️ Borrar página (requiere login)
- 🧾 Registro de usuarios
- 🔐 Login / Logout
- 📁 Vista de perfil de usuario
- 🖊️ Edición de perfil con avatar, biografía y fecha de nacimiento
- ✉️ Sistema de mensajería entre usuarios (crear y ver mensajes)

---

## 🧱 Tecnologías utilizadas

- Python 3.13
- Django 5.x
- SQLite
- HTML + CSS (SimpleCSS)
- CKEditor (para texto enriquecido)
- Bootstrap (opcional para estilo)
- Autenticación con `django-allauth`

---

## ⚙️ Instrucciones para correr el proyecto localmente

1. Cloná el repositorio:

```bash
git clone https://github.com/tu_usuario/django-blog.git
cd django-blog

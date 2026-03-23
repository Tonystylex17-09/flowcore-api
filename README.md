# FlowCore API
[![Python](https://img.shields.io/badge/Python-3.14-blue)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.135-green)](https://fastapi.tiangolo.com)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)](https://mysql.com)
[![JWT](https://img.shields.io/badge/JWT-Auth-red)](https://jwt.io)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.14-blue)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.135-green)](https://fastapi.tiangolo.com)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)](https://mysql.com)

API REST profesional con autenticación JWT, desarrollada con **FastAPI** y **MySQL**. Incluye registro de usuarios, login y CRUD completo de tareas.

## 🚀 Características

- ✅ Autenticación JWT (registro, login, rutas protegidas)
- ✅ CRUD de tareas por usuario
- ✅ Documentación automática con Swagger
- ✅ Base de datos MySQL con SQLAlchemy
- ✅ CORS configurado

## 📚 Endpoints Principales

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| POST | `/register` | Registrar usuario |
| POST | `/login` | Obtener token JWT |
| GET | `/users/me` | Ver perfil propio |
| POST | `/tasks` | Crear tarea |
| GET | `/tasks` | Listar tareas |

## 🛠️ Instalación Local

```bash
# Clonar repositorio
git clone https://github.com/Tonystylex17-09/flowcore-api.git
cd flowcore-api

# Crear entorno virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Instalar dependencias
pip install -r requirements.txt

# Configurar base de datos en MySQL
# Crear base de datos llamada "flowcore_db"

# Ejecutar API
python main.py

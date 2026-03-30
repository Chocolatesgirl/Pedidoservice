# Servicio de Pedidos 🚀

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-0.95.2-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Descripción
Proyecto de **servicio de pedidos** usando Python y FastAPI. Permite gestionar usuarios, platos y pedidos de forma modular, simulando un sistema real de restaurante o comercio electrónico.

---

## Tecnologías
- Python 3.10+
- FastAPI (API REST)
- Uvicorn (Servidor ASGI)
- Pydantic (Modelos de datos)
- SQLite (opcional)
- Git / GitHub

---

## Funcionalidades
- Crear, listar y eliminar usuarios  
- Crear, listar y eliminar platos  
- Crear y consultar pedidos por usuario  
- Gestión de IDs únicas para usuarios y platos  
- Modularización por microservicios

---

## Estructura del proyecto
PedidoService/
 ├─ main.py          # API principal: aquí se definen los endpoints de usuarios, platos y pedidos
 ├─ models.py        # Modelos Pydantic: define cómo se estructuran los datos (usuarios, platos, pedidos)
 ├─ services/        # Lógica de negocio: funciones que gestionan usuarios, platos y pedidos
 ├─ requirements.txt # Dependencias del proyecto: lista de librerías necesarias (FastAPI, Uvicorn, etc.)
 ├─ README.md        # Documentación del proyecto: lo que estamos creando ahora
 └─ .gitignore       # Archivos a ignorar al subir a GitHub (venv, logs, __pycache__)

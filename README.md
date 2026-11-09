# Laboratorio: Práctica de Seguridad MTTD y MTTR

## 1. Datos generales

- **Nombre completo:** Fr4nklin J0sué Torr3s R0mero
- **Carné:** ______
- **Correo institucional:** pr0fr4nklint0rres@pr0tonm4ail.com
- **Asignatura:** Respuesta a Incidentes de Seguridad
- **Fecha:** 09 de noviembre de 2026

## 2. Descripción

Este laboratorio consiste en desarrollar y evaluar una aplicación web utilizando
Python y Flask, implementando controles básicos de seguridad basados en buenas
prácticas y el modelo OWASP.

Se implementaron mecanismos de registro de usuarios, protección de contraseñas
mediante hash, validación de credenciales y registro de eventos de autenticación.

También se desarrolló un detector de incidentes de seguridad en Python, encargado
de identificar múltiples intentos fallidos de inicio de sesión y registrar una
respuesta simulada de bloqueo de usuario.

Finalmente, se calcularon las métricas **MTTD** (Mean Time to Detect) y
**MTTR** (Mean Time to Respond) mediante tres escenarios de prueba.

## 3. Estructura del proyecto

```text
lab-mttd-mttr/
│
├── .gitignore
├── README.md
│
└── proyecto/
    ├── app.py
    ├── crearDB.py
    ├── detector.py
    ├── requirements.txt
    ├── usuarios.db
    ├── eventos.log
    ├── respuesta.log
    │
    └── templates/
        ├── registro.html
        └── login.html
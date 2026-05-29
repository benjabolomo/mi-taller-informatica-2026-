# Taller de Informática II

## Trabajo Práctico 3: Configuración de Git y GitHub
## Descripción
Este repositorio contiene el desarrollo del **Trabajo Práctico 3** del Taller de Informática II. El objetivo principal de este trabajo es la correcta instalación, configuración y asimilación del flujo de trabajo básico utilizando el sistema de control de versiones **Git** y la plataforma de alojamiento remoto **GitHub**.

A lo largo del proyecto se demuestra la capacidad para inicializar repositorios locales, gestionar el historial de cambios mediante commits y sincronizar el progreso de forma colaborativa en un entorno remoto.


## Objetivos Desarrollados

### Objetivo General
* Obtener un repositorio remoto con el archivo `README.md` completado, un registro del commit inicial y commits adicionales que demuestren la correcta sincronización de cambios en GitHub.

### Objetivos Específicos
* **Instalación y Validación:** Instalación de Git en diferentes entornos y verificación de su funcionamiento a través de la terminal.
* **Configuración de Identidad:** Establecimiento de variables globales de Git (`user.name` y `user.email`) asociadas a las cuentas de GitHub de los integrantes.
* **Flujo de Trabajo Local:** Creación y gestión de estructuras de Git locales empleando comandos como `git init`, `git add`, `git status` y `git commit`.
* **Sincronización Remota:** Vinculación de un repositorio local con un servidor remoto en GitHub utilizando `git remote` y subida de datos mediante `git push`.

## Comandos Principales Utilizados

Durante el desarrollo de esta práctica se aplicó la siguiente secuencia de comandos esenciales en la terminal:

```bash
# 1. Configuración de identidad global
git config --global user.name "Tu Nombre y Apellido"
git config --global user.email "tu-email@ejemplo.com"

# 2. Inicialización del repositorio local
git init

# 3. Ciclo de vida de archivos (Stage & Commit)
git add README.md
git status
git commit -m "Inicial: Agregando README.md"

# 4. Vinculación y subida al repositorio remoto (Aqui tambien se hizo un rebranch para pasar de master a main)
git remote add origin [https://github.com/benjabolomo/mi-taller-informatica-2026-]
git remote -v
git push -u origin main

# 5. Edicion del archivo README
Editado directamente desde el editor de github

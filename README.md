# 🚀 Guía Rápida de Comandos Git

Git es un sistema de control de versiones distribuido que permite gestionar el historial de cambios en proyectos de software. Aquí tienes una guía rápida con los comandos más usados.

---

## 📍 Indice
1. [📌 Configuración Inicial](#-1-configuración-inicial)
2. [📂 Iniciar un Repositorio](#-2-iniciar-un-repositorio)
3. [📊 Estados y Cambios](#-3-estados-y-cambios)
4. [🔍 Historial y Revisión](#-4-historial-y-revisión)
5. [🌿 Ramas y Fusión](#-5-ramas-y-fusión)
6. [🌍 Trabajo con Repositorios Remotos](#-6-trabajo-con-repositorios-remotos)
7. [🛠️ Restaurar Cambios](#-7-restaurar-cambios)
8. [⚙️ Comandos Avanzados](#-8-comandos-avanzados)

---

## 📌 1 Configuración Inicial
Antes de empezar a trabajar con Git, es importante configurar tu identidad:

### relacionar cuenta de git
```bash
# Configurar usuario y correo
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
```
**Tip:** Esta configuración se guarda en `~/.gitconfig` y se aplicará a todos tus proyectos.
### [📍 Indice](#-indice)

---

## 📂 2 Iniciar un Repositorio
Si quieres comenzar un nuevo proyecto con Git o clonar uno existente:

```bash
# Inicializar un nuevo repositorio en la carpeta actual
git init

# Clonar un repositorio remoto
git clone <url_del_repositorio>
```
**Nota:** `git clone` crea una copia exacta del repositorio en tu máquina.
### [📍 Indice](#-indice)

---

## 📊 3 Estados y Cambios
Controla qué archivos han cambiado y prepáralos para ser guardados:

```bash
# Ver estado del repositorio
git status

# Agregar archivos al área de preparación
git add <archivo>  # Agregar un archivo específico
git add .          # Agregar todos los archivos

# Confirmar cambios con un mensaje descriptivo
git commit -m "Descripción del cambio"
```
**Importante:** Un commit es como una fotografía del estado del proyecto en un momento específico.
### [📍 Indice](#-indice)

---

## 🔍 4 Historial y Revisión
Consulta los cambios realizados y compara versiones:

```bash
# Ver historial de commits
git log
git log --oneline  # Historial resumido

# Ver diferencias entre versiones
git diff            # Cambios sin agregar
git diff --staged   # Cambios en el área de preparación
```
**Sugerencia:** Usa `git log --graph --decorate --all --oneline` para ver un historial visual de los commits.
### [📍 Indice](#-indice)

---

## 🌿 5 Ramas y Fusión
Gestiona diferentes versiones del proyecto con ramas:

```bash
# Ver ramas existentes
git branch

# Crear una nueva rama
git branch nombre-de-la-rama

# Cambiar a una rama existente
git checkout nombre-de-la-rama

# Fusionar una rama en la rama actual
git merge nombre-de-la-rama
```
**Nota:** Antes de fusionar una rama, asegúrate de estar en la rama destino.
### [📍 Indice](#-indice)

---

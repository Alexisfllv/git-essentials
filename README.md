# 🚀 Guía Rápida de Comandos Git

Git es un sistema de control de versiones distribuido que permite gestionar el historial de cambios en proyectos de software. Aquí tienes una guía rápida con los comandos más usados.

---

## 📍 Indice
### 0. [📌 Instalación](#-0-instalación)
### 1. [📌 Configuración Inicial](#-1-configuración-inicial)
### 2. [📂 Iniciar un Repositorio](#-2-iniciar-un-repositorio)
### 3. [📊 Estados y Cambios](#-3-estados-y-cambios)
### 4. [🔍 Historial y Revisión](#-4-historial-y-revisión)
### 5. [🌿 Ramas y Fusión](#-5-ramas-y-fusión)
### 6. [🌍 Trabajo con Repositorios Remotos](#-6-trabajo-con-repositorios-remotos)
### 7. [🛠️ Restaurar Cambios](#-7-restaurar-cambios)
### 8. [⚙️ Comandos Avanzados](#-8-comandos-avanzados)


---

## 📌 0 Instalación
Instalación de Git en Mac y Windows

### En Mac Verificar si esta instalado
```bash
git --version
```
Si Git está instalado, verás la versión. Si no, continúa con la instalación.

### Instalar Git usando Homebrew 🍺
```bash
brew install git
```
Si es una version anterior actualizar con.
```bash
brew upgrade git
```
Posteriormente verificar si se instalo correctamente.

### En Windows Verificar si esta instalado
```bash
git --version
```
Si no aparece nada o tengas una version anterior continuar con la instalacion.

### Descargar instalador de la pagina oficial
```bash
https://git-scm.com/downloads/win
```
Manten las opciones predeterminadas y usar Git Bash como terminal posteriomente verificar si se instalo correctamente.


### [📍 Indice](#-indice)

---


## 📌 1 Configuración Inicial

### Muestra los comando relacionados con `git config`
```bash
git --help config
```

### Configurar usuario
```bash
git config --global user.name "Tu Nombre"
```

### Configurar correo
```bash
git config --global user.email "tuemail@example.com"
```
### [📍 Indice](#-indice)

---

## 📂 2 Iniciar un Repositorio

### Inicializar un nuevo repositorio en la carpeta actual
```bash
git init
```

### Mostrar el estado del repositorio
```bash
git status
```

### Clonar un repositorio remoto
```bash
git clone <url_del_repositorio>
```
### [📍 Indice](#-indice)


---

## 📊 3 Estados y Cambios

### Muestra los comando relacionados con `git config`
```bash
git --help config
```

### Configurar usuario
```bash
git config --global user.name "Tu Nombre"
```

### Configurar correo
```bash
git config --global user.email "tuemail@example.com"
```
### [📍 Indice](#-indice)

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

# IFTS 29 - Tecnicatura en Desarrollo de Software  

## Seminario de actualización DevOps - 3° D

**Actividad GitHub**
**Alumno:** Damián Andrés Clausi  
**Profesor:** Javier Blanco

---

## Aprendiendo Git

Este proyecto es una práctica básica de **Git** para configurar el entorno, crear un repositorio y realizar los primeros commits.

---

## Configuración inicial de Git

```bash
git config --global user.name "Damian Clausi"
git config --global user.email "damian.clausi@gmail.com"
git config --global color.ui auto
```

Verificar la configuración global:

```bash
git config --list --global
```

---

## Crear un nuevo repositorio

```bash
mkdir AprendiendoGit
cd AprendiendoGit
git init
```

Ver archivos ocultos (se crea la carpeta `.git`):

```bash
ls -a
```

---

## Primer archivo y commit

Crear un archivo `Readme.md` con contenido inicial:

```bash
touch Readme.md
echo "Git Fundamentos" > Readme.md
```

Ver estado del repositorio:

```bash
git status
```

Añadir archivo a staging:

```bash
git add Readme.md
```

Hacer el primer commit:

```bash
git commit -m "Fecha"
```

---

## Editar y abrir en VS Code

Abrir la carpeta del proyecto en VS Code:

```bash
code .
```

---

## Agregar un nuevo archivo (index.html)

Crear y añadir el archivo:

```bash
git add index.html
git commit -m "Agregar index.html"
```

---

## Ver historial y cambios

Historial resumido:

```bash
git log --oneline --graph
```

Ver último commit en detalle:

```bash
git show
```

---

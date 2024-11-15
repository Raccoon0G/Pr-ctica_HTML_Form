# Práctica: Crear un README.md

Este archivo README.md forma parte del último proyecto de Git, en el que se explicarán algunos comandos básicos de Git.

## Comandos de Git

### `git init`
Este comando se utiliza para inicializar un nuevo repositorio de Git en tu proyecto. Al ejecutarlo, Git crea un subdirectorio oculto `.git` en tu proyecto que contiene toda la información necesaria para el control de versiones.

**Uso:**
```bash
git init
```

### `git add`
Este comando agrega los cambios realizados en archivos al área de preparación (*staging area*). Esto incluye nuevos archivos, cambios realizados o archivos eliminados, para que puedan ser incluidos en el siguiente commit.

**Uso:**
```bash
git add nombre_del_archivo
```
Para agregar todos los archivos:
```bash
git add .
```

### `git commit -m "descripción del commit"`
Este comando guarda los cambios registrados en el área de preparación en el historial del repositorio. La opción `-m` permite añadir un mensaje descriptivo que explique los cambios realizados.

**Uso:**
```bash
git commit -m "Descripción breve de los cambios"
```

### `git push`
Este comando se utiliza para enviar los commits realizados en el repositorio local al repositorio remoto, permitiendo sincronizar los cambios con otros colaboradores.

**Uso:**
```bash
git push origen rama
```
Por ejemplo:
```bash
git push origin main
```

### `git pull`
Este comando se utiliza para traer cambios desde el repositorio remoto al repositorio local y fusionarlos automáticamente con la rama actual. Es útil para mantener el repositorio local actualizado con los cambios de otros colaboradores.

**Uso:**
```bash
git pull origen rama
```
Por ejemplo:
```bash
git pull origin main
```

### `git remote -v`
Este comando se utiliza para mostrar las URL de los repositorios remotos que están configurados para el repositorio actual. Es útil para verificar las conexiones remotas.

**Uso:**
```bash
git remote -v
```

---

## Proyecto y Recursos

### Imagen de Ejemplo
![Ejemplo del Proyecto](https://via.placeholder.com/800x400 "Imagen de Ejemplo")

### Enlace al Repositorio
Puedes encontrar este proyecto en GitHub: [Repositorio de Practica_HTML_Form](https://github.com/Raccoon0G/Practica_HTML_Form)
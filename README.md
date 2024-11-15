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

### `git remote add origin "link de repositorio"`
Este comando se utiliza para añadir un nuevo repositorio remoto y vincularlo al repositorio local. Es esencial para poder usar comandos como `git push` o `git pull` con ese remoto.

**Uso:**
```bash
git remote add origin "https://link_del_repositorio"
```

### `git remote set-url origin "link de repositorio"`
Este comando se utiliza para cambiar la URL de un repositorio remoto existente. Es útil si necesitas actualizar el enlace remoto.

**Uso:**
```bash
git remote set-url origin "https://nuevo_link_del_repositorio"
```

### `git branch`
Este comando lista todas las ramas del repositorio o crea una nueva rama.

**Uso:**
- Listar ramas:
```bash
git branch
```
- Crear una nueva rama:
```bash
git branch nombre_rama
```

### `git branch -d nombre_rama`
Este comando se utiliza para eliminar una rama local. Es útil cuando ya no necesitas una rama específica.

**Uso:**
```bash
git branch -d nombre_rama
```

### `git merge`
Este comando combina los cambios de una rama con la rama actual. Es útil para integrar nuevas características o correcciones.

**Uso:**
```bash
git merge nombre_rama
```

### `git checkout`
Este comando se utiliza para cambiar de rama o restaurar archivos en el directorio de trabajo.

**Uso:**
- Cambiar de rama:
```bash
git checkout nombre_rama
```
- Restaurar un archivo:
```bash
git checkout nombre_archivo
```

### `git log`
Este comando muestra el historial de commits del repositorio. Es útil para ver los cambios realizados en cada commit.

**Uso:**
```bash
git log
```

### `git status`
Este comando muestra el estado actual del repositorio, incluyendo archivos modificados, no rastreados o listos para ser confirmados.

**Uso:**
```bash
git status
```

---

## Proyecto y Recursos

### Imagen de Ejemplo
![Ejemplo del Proyecto](https://via.placeholder.com/800x400/7cd2e3/FFF?text=Imagen+de+ejemplo "Imagen de Ejemplo")

### Enlace al Repositorio
GitHub: [Raccon0G](https://github.com/Raccoon0G/)

---
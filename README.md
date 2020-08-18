# hola-mundo
Repositorio Hola Mundo

## Pre-requisitos
- Tener una cuenta de [github](https://github.com/)
- Tener [git](https://git-scm.com/) instalado en el ordenador

### Paso 1 - Crear un repositorio
- Crear un repositorio con el nombre de "hola-mundo"
- Escribir una descripción corta
- El repositorio tiene que ser publico
- Inicializar el repositorio con un archivo de README.md

### Paso 2 - Clonar Repositorio
- Copiar el link del repositorio "hola-mundo"
- Abrir la terminal de git o tu terminal favorita en el directorio a clonar
- Correr el comando para clonar seguido del la url HTTPS
```git
git clone https://github.com/GITHUB_USER/hola-mundo.git
```

### Paso 3 - Configurar Usuario
- En la terminal ir al repositorio clonado
- Configurar nombre a nivel de repositorio
- Configurar correo (asociado a tu cuenta de github) a nivel de repositorio
```git
git config user.name "John Doe"
git config user.email johndoe@example.com
```
- Revisar que nombre y correo se guardaron correctamente
```git
git config user.name
git config user.email
```

### Paso 4 - Crear Rama (Branch)
- Listar ramas existentes en nuestro repositorio local
- Crear una rama a partir de la rama principal "master" con el nombre de "feature"
- Listar nuevamente las ramas
```git
git branch
git checkout -b feature
git branch
```

### Paso 5 - Hacer Commit de mis cambios
- Revisar los cambios en git
- Crear un archivo con el nombre de "hola-mundo.py"
- Revisar los cambios en git
- Añadir el archivo creado del directorio de trabajo (working directory) al área de Staging (staging area)
- Revisar los cambios en git
- Pasar los archivos del área de Staging (staging area) al repositorio local (local repository)
- Revisar los cambios en git
```git
git status
// crear archivo
git status
git add hola-mundo.py
git status
git commit -m "Subiendo archivo hola-mundo al proyecto"
git status
```

#### Felicidades, hasta aquí ya estamos listo para subir nuestros cambios a github 😊

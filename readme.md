# Laboratorio Git

### Crear un repositorio local

1. Creamos el directorio, accedemos a el mediante la terminal e inicializamos git con el comando **git init**.

### Subir el repositorio a GitHub

2. Creamos el repositorio en Github. En este caso llamado bootcamp-js-modulo00.

3. Copiamos la URL, en este caso vamos a usar conexión SSH:
````````
git@github.com:Portelldx/bootcampjs-modulo00.git
`````````

4. Añadimos el branch y el repositorio remoto a nuestro repositorio local
````````````````
git remote add origin git@github.com:Portelldx/bootcampjs-modulo00.git
```````````````````````

5. Comprobamos que la conexión es satisfactoria mediante el comando **git remote -v**. Donde  aparece el repositorio remoto de salida.

### Hacer commit y un push

6. Creamos un archivo readme.md y lo añadimos al staging **git add .**

7. Comiteamos **git commit -m "Creado archivo readme.md"**.


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

8. Asignamos y definimos la rama remota por defecto de github **Main** y hacemos el push.

``````
git push --set-upstream origin main
```````

### Crear una rama

9. Creamos la rama introduciendo **git checkout** y nos cambiamos directamente con **-b** a la rama development :
``````
git checkout -b development
``````
10. Añadimos el archivo readme.md al staging, hacemos commit y push a la rama development con **git push origin development** ya que tenemos asignada main por defecto como upstream.

### Hacer un merge

11. Volvemos a la rama main mediante **git checkout main**.
13. Hacemos merge de la rama development introduciendo **git merge development**.
12. En nuestro caso no hay conflictos y los cambios se añaden automáticamente.
13. Hacemos un push a la rama main de los cambios **git push origin main**.
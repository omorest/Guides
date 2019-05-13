# Comandos Git
 
--- 
- **git init**
    ```
    Iniciamos un repositorio desde una carpeta en local
    ```
- **git status**

    ```
    Vemos el estado del repositorio sabiendo si hemos hecho alguna modificación que aun no se ha añadido
    ```
- **git add -A**
    ```
    Añadimos los últimos cambios realiazos
    ```
- **git commit -m "comentario"**
    ```
    Le asignamos un commit (ID) y un comentario a los cambios que hemos añadido anteriormente
    ```
- **git push**

    - git push 
    - git push origin master

- **git log**  
    ```
    Vemos todos los commits
    ```
  
- **git checkout** *id_commit* 
    ```
    Viajamos al commit que queramos
    
    # git checkout master -> volvemos al commit más reciente
    ```
- **git reset**
    ```
    # git reset --soft *id_commit* -> borra hasta el commit elegido pero no borra el código

    # git reset --hard *id_commit* -> borra hasta el commit elegido y también el código
    ```

- **git branch** 
    ```
    Nos muestra las ramas que tenemos en el repositorio y nos señala en la que estamos
    ```

- **git branch nombre_rama_nueva**
    ```
    Creamos una rama nueva
    ```

- **git checkout nombre_rama**
    ```
    Cambiamos a la rama seleccionada
    ```

# Comandos Git
 
--- 

## 1. Primeros comandos

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

---

## 2. Ramas y fusiones

### 2.1 Ramas
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

- **git checkout -b nombre_rama**
    ```
    Creamos una rama nueva y accedemos a ella, los dos pasos anteriores en 1
    ```
- **git branch -D nombre_rama**
    ```
    Borramos la rama
    ```

### 2.2 Fusiones

> La rama *Master* debe ser la que contenga el proyecto estable y las demas ramas para testear. Una vez en el testeo conseguimos lo que queremos las fusionamos

Juntar rama *Master* con otra rama.


- **git merge**
  
  - Nos movemos primero a la rama *Master* : `git checkout master`

  - Elegimos la rama que queremos absorver: **git merge nombre_rama_absorver**

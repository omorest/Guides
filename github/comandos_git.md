# Comandos Git
 
--- 
- **git init**
- **git status**
- **git add -A**
- **git commit -m "comentario"**
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

    
- **`git branch` : **
- **git branch nombre_rama_nueva**
- **git checkout nombre_rama**

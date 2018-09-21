Óscar Moreira Estévez

# Github Windows y Claves RSA
___
  ![portada](./img/portada.png)

___

## Explicación

Para poder usar github como lo usamos en *Linux* con claves *RSA* y con los comandos para subir archivos a *Github* tendremos que usar la herramienta `Git`, ya que nos proporcionará tanto todos los comandos necesarios como incluso la posibilidad de crear claves RSA debido a que funciona como una consola de *Linux*
## 1. Instalación Git

- Para poder instalar `git` en windows lo primero será ir a la página http://gitforwindows.org/ y descargarlo.

  ![1.0-pagina](./img/1.0-pagina.png)

- Una vez descargado lo ejecutaremos para empezar la instalación.

- Seguiremos la instalación como en los siguientes pasos que veremos a continucación:
  > En la primera captura yo elijo esa ruta ya que tengo dos discos de almacenamiento.

    ![1.3](./img/1.3.png)

    ![1.4](./img/1.4.png)

    ![1.5](./img/1.5.png)

    ![1.6](./img/1.6.png)

    ![1.7](./img/1.7.png)

    ![1.8](./img/1.8.png)

    ![1.9](./img/1.9.png)

    ![1.10](./img/1.10.png)

    ![1.11](./img/1.11.png)

    ![1.12](./img/1.12.png)

- Hecho todo esto ya estaría instalado asi que abriremos el programado llamado `Git Bash` y se nos abrira una consola.

  > Tener en cuenta que esta consola usa comandos de Linux.

  ![1.13](./img/1.13.png)

___

## 2. Claves RSA

- Sabiendo que esta consola de *Git* funciona como una de *Linux* podremos generar nuestras claves RSA con el comando `ssh-keygen`.

  ![2.0](./img/2.0.png)

- Teniendo esto hecho veremos con el comando `ls -a` que el directorio principal `/c/Users/nombre_usuario` nos encontraremos una carpeta llamada `.ssh`.

  ![2.1](./img/2.1.png)

- si ejecutamos el comando `ls` dentro de la carpeta *.ssh* veremos que tenemos una clave publica y otra privada.

  ![2.2](./img/2.2.png)

- ahi estarán nuestras claves que usaremos para unir con `Github`.

___

## 3. Github con Windows

### 3.1 Configuración

- Para la configuración básica tendremos que ejcutar los siguientes comandos en la consola `Git Bash`:
  ```
  - git config --global user.email "email"
  - git config --global user.name "nombre"
  - git config --global push.default simple
  ```

### 3.2 Claves en Github

Teniendo ya las claves creadas con nuestra consola `Git Bash` pasaremos a darle nuestra clave pública a nuestro *Github*.

- Para esto En el directorio `.ssh` donde se encuentran nuestras claves ejecutaremos el comando `cat id_rsa.pub`, de esta manera veremos el contenido de la clave y lo copiamos.

  > El nombre de la clave puede ser diferente pero ese es el nombre por defecto.

- Una vez copiada todo el contenido de la clave pública iremos a nuestro *Github*.

- Dentro de nuestro *Github* iremos arriba a la derecha a nuestra imagen y entraremos en `settings` --> `SSH and GPG Keys`.

  ![3.1](./img/3.1.png)

- Ahora iremos donde pone `New SSH Key` y le pondremos un nombre para saber a que pertenece y luego pegaremos la clave pública que hemos copiado.

  ![3.2](./img/3.2.png)

- Con esto hecho ya tendriamos la parte de las claves hecha.

___

## 4. Repositorio en Windows

- Ahora iremos a un repositorio que querramos tener en nuestro PC y una vez dentro del repositorio iremos al botón verde llamado `Clone or download` y copiaremos el texto que esta en la opción que se llama `Clone with SSH`.

  ![4.1](./img/4.1.png)

- Copiado el enlace del repositorio para usar por SSH iremos a la consola `Git Bash` y en la ruta que deseemos que se nos descargue el repositorio ejecutaremos el comando `git clone` junto al enlace copiado.

  ![4.2](./img/4.2.png)

- Vemos que ha funcionado correctamente.

## 5. Comprobación de funcionamiento.

- Para comprobar que funciona pondremos un nuevo archivo en la carpeta del repositorio o modificamos alguno para subirlo  al repositorio de *Github* desde nuestro PC windows con la herramienta `Git Bash`.

- Una vez modifiquemos algo dentro de la carpeta del repositorio si ejecutamos el comando `git status` estando dentro del repositorio en la consola Git veremos que ya nos sale que se ha modificado algo.

  ![5.1](./img/5.1.png)

- Luego de esto ejecutaremos los comandos: `git add` junto al fichero que queremos subir y el comando `git commit -m "texto_significativo"` para añadirle como un guardado en el tiempo (como un punto de restauración).

  ![5.2](./img/5.2.png)

- Por último ejecutaremos el comando `git push` para subirlo.

- Con esto ya tendremos lso cambios subidos.

  ![5.3](./img/5.3.png)

___
___

Fín del informe

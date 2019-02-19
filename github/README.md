# Configuración de GitHub con nuestro PC (Linux / Mac)

![portada](./img/portada.png)

---

# Índice


---
---

## 1. Instalación de Git

Lo primero que haremos será instalar git en nuestro ordenador.

- **Linux**: desde la terminal.

    ~~~
      - sudo apt-get update         //Actualizamos los repositorios
      - sudo apt-get install git    //Instalamos Git
    ~~~

- **Mac**:

  - La forma más sencilla es usar el instalador gráfico de Git, que puedes descargar [aquí](http://sourceforge.net/projects/git-osx-installer/)

  - La segunda alternativa es Homebrew (http://brew.sh/). Si ya tienes instalado Homebrew, instala Git con: `brew install git`

---

## 2. Configuración de Git

Una vez instalado Git en nuestro ordenador pasaremos a configurarlo, solo tendremos que ejecutar 3 comandos en la terminal:

  ~~~
  - git config --global user.name "nombre_usuario"
  - git config --global user.email "email"
  - git config --global push.default simple
  ~~~

___

## 3. Creación de claves pública/privada

Ahora haremos en la configuración de github en nuestro PC *(linux / mac)* será crear una clave publica y privada para así cuando queramos subir algun archivo no sea necesario poner la contraseña.

- Abriremos la terminal de comandos y ejecutaremos el siguiente comando: `ssh-keygen`

  ~~~console
  MacBook-Pro-de-Oscar:~ oscarmoreira$ ssh-keygen
  Generating public/private rsa key pair.
  Enter file in which to save the key (/Users/oscarmoreira/.ssh/id_rsa):
  Created directory '/Users/oscarmoreira/.ssh'.
  Enter passphrase (empty for no passphrase):
  Enter same passphrase again:
  Your identification has been saved in /Users/oscarmoreira/.ssh/id_rsa.
  Your public key has been saved in /Users/oscarmoreira/.ssh/id_rsa.pub.
  The key fingerprint is:
  ---------------------------------------- oscarmoreira@MacBook-Pro-de-Oscar.local
  The key's randomart image is:
  +---[RSA 2048]----+
  | .      .        |
  |   o B @   .     |
  |      =          |
  |       .   * . = |
  |    .           o|
  |     = . O      .|
  |    o o = B +    |
  |                 |
  |                 |
  +----[SHA256]-----+
  ~~~

- Hecho esto nos habrá creado en el directorio raiz una carpeta llamada: `.ssh` que contendra nuestra clave pública y privada.

  ~~~console
  MacBook-Pro-de-Oscar:~ oscarmoreira$ ls -a
  .			.cups			Desktop
  ..			.docker			Documents
  .CFUserTextEncoding	.gitconfig		Downloads
  .DS_Store		.mume			Library
  .Trash			.npm			Movies
  .atom			.ssh			Music
  .bash_history		.vscode			Pictures
  .bash_sessions		Applications		Public

  MacBook-Pro-de-Oscar:~ oscarmoreira$ cd .ssh/
  MacBook-Pro-de-Oscar:.ssh oscarmoreira$ ls
  id_rsa		id_rsa.pub
  ~~~

- Ahora copiaremos el contenido de **id_rsa.pub**, podremos ver el contenido con el comando: `cat id_rsa.pub`

- Una vez copiado el contenido iremos a nuestro ***GitHub***, clicamos en nuestra foto de perfil nos dirigimos a `settings/SSH and GPG keys`

- Clicaremos en `New SSH Key`

  ![new ssh key](./img/ssh-github.png)

- Luego le pondremos un nombre para saber a que ordenador pertenece la clave e introduciremos la clave copiada anteriormente.

  ![ssh key copy](./img/ssh-github2.png)

Con esto ya tendriamos toda la configuración hecha de nuestro github con nuestro PC *(Mac / Linux)*.

___

## 4. Uso sencillo de Git con github

  ## 4.1 Creación de repositorio.

  Los repositorios serán como carpetas de proyectos que crearemos en ***Github*** para guardar nuestro programa.

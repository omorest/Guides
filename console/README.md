```console
elena@elena-ubuntu:~$ script
Script iniciado; el fichero es typescript
elena@elena-ubuntu:~$ pwd
/home/elena
elena@elena-ubuntu:~$ ls
Descargas   Escritorio        Imágenes  Plantillas  typescript
Documentos  examples.desktop  Música    Público     Vídeos
elena@elena-ubuntu:~$ LS

No se ha encontrado la orden «LS», pero se puede instalar con:

sudo apt install sl

elena@elena-ubuntu:~$ man ls
elena@elena-ubuntu:~$ ls -l
total 44
drwxr-xr-x 2 elena elena 4096 oct  8 19:56 Descargas
drwxr-xr-x 2 elena elena 4096 oct  8 19:56 Documentos
drwxr-xr-x 2 elena elena 4096 oct  7 20:47 Escritorio
-rw-r--r-- 1 elena elena 8980 oct  6 15:45 examples.desktop
drwxr-xr-x 2 elena elena 4096 oct  6 16:02 Imágenes
drwxr-xr-x 2 elena elena 4096 oct  6 16:02 Música
drwxr-xr-x 2 elena elena 4096 oct  6 16:02 Plantillas
drwxr-xr-x 2 elena elena 4096 oct  6 16:02 Público
-rw-r--r-- 1 elena elena    0 oct  8 19:58 typescript
drwxr-xr-x 2 elena elena 4096 oct  6 16:02 Vídeos
elena@elena-ubuntu:~$ mkdir dir
elena@elena-ubuntu:~$ rmdir dir
elena@elena-ubuntu:~$ mkdir dir
elena@elena-ubuntu:~$ cd dir
elena@elena-ubuntu:~/dir$ touch minombre.txt
elena@elena-ubuntu:~/dir$ rm minombre.txt
elena@elena-ubuntu:~/dir$ rmdir dir
rmdir: fallo al borrar 'dir': No existe el archivo o el directorio
elena@elena-ubuntu:~/dir$ cd
elena@elena-ubuntu:~$ rmdir dir
elena@elena-ubuntu:~$ mkdir origen destino
elena@elena-ubuntu:~$ cd origen
elena@elena-ubuntu:~/origen$ touch origen.txt
elena@elena-ubuntu:~/origen$ cd
elena@elena-ubuntu:~$ cp origen/origen.txt destino/
elena@elena-ubuntu:~$ cd destino
elena@elena-ubuntu:~/destino$ ls
origen.txt
elena@elena-ubuntu:~/destino$ cd
elena@elena-ubuntu:~$ mv origen/origen.txt destino/origen1.txt
elena@elena-ubuntu:~$ ls destino
origen1.txt  origen.txt
elena@elena-ubuntu:~$ mkdir elena_rijo
elena@elena-ubuntu:~$ cd elena_rijo/
elena@elena-ubuntu:~/elena_rijo$ mkdir tmp asignaturas varios
elena@elena-ubuntu:~/elena_rijo$ cd asignaturas/
elena@elena-ubuntu:~/elena_rijo/asignaturas$ mkdir informatica_basica algebra calculo
elena@elena-ubuntu:~/elena_rijo/asignaturas$ ls
algebra  calculo  informatica_basica
elena@elena-ubuntu:~/elena_rijo/asignaturas$ cd informatica_basica/
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica$ mkdir teorias practicas
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica$ cd practicas/
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ mkdir p1 p2
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ cat > mifichero.txt
hola mundo
soy elena rijo :)
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ rm mifichero.txt
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ cd
elena@elena-ubuntu:~$ cat > mifichero.txt
hola mundo
soy elena rijo :)
elena@elena-ubuntu:~$ cat mifichero.txt
hola mundo
soy elena rijo :)
elena@elena-ubuntu:~$ more mifichero.txt
hola mundo
soy elena rijo :)
elena@elena-ubuntu:~$ less mifichero.txt
elena@elena-ubuntu:~$ cp mifichero.txt
cp: falta el operando archivo de destino después de 'mifichero.txt'
Pruebe 'cp --help' para más información.
elena@elena-ubuntu:~$ cp mifichero.txt elena_rijo/asignaturas/informatica_basica/practicas/
elena@elena-ubuntu:~$ ls elena_rijo/asignaturas/informatica_basica/practicas/
mifichero.txt  p1  p2
elena@elena-ubuntu:~$ cp elena_rijo/asignaturas/informatica_basica/practicas/
cp: falta el operando archivo de destino después de 'elena_rijo/asignaturas/informatica_basica/practicas/'
Pruebe 'cp --help' para más información.
elena@elena-ubuntu:~$ cd elena_rijo/asignaturas/informatica_basica/practicas/
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ mv mifichero.txt otrofichero.txt
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ ls
otrofichero.txt  p1  p2
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ cat otrofichero.txt
hola mundo
soy elena rijo :)
elena@elena-ubuntu:~/elena_rijo/asignaturas/informatica_basica/practicas$ cd
elena@elena-ubuntu:~$ cd elena_rijo/
elena@elena-ubuntu:~/elena_rijo$ ls
asignaturas  tmp  varios
elena@elena-ubuntu:~/elena_rijo$ rmdir tmp/
elena@elena-ubuntu:~/elena_rijo$ rmdir asignaturas/informatica_basica/practicas/
rmdir: fallo al borrar 'asignaturas/informatica_basica/practicas/': El directorio no está vacío
elena@elena-ubuntu:~/elena_rijo$ mv asignaturas/informatica_basica/practicas/otrofichero.txt
asignaturas/ varios/      
elena@elena-ubuntu:~/elena_rijo$ mv asignaturas/informatica_basica/practicas/otrofichero.txt varios/
elena@elena-ubuntu:~/elena_rijo$ ls varios/
otrofichero.txt
elena@elena-ubuntu:~/elena_rijo$ find -name *.txt
./varios/otrofichero.txt
elena@elena-ubuntu:~/elena_rijo$ find -name otrofichero.txt
./varios/otrofichero.txt
elena@elena-ubuntu:~/elena_rijo$ exit
Script terminado; el fichero es typescript
elena@elena-ubuntu:~$


```

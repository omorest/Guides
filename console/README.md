```console
MacBook-Pro-de-Oscar:~ oscarmoreira$ mkdir oscar_moreira
MacBook-Pro-de-Oscar:~ oscarmoreira$ cd oscar_moreira/
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ mkdir tmp asignaturas varios
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ cd asignaturas/
MacBook-Pro-de-Oscar:asignaturas oscarmoreira$ mkdir informatica_basica algebra calculo
MacBook-Pro-de-Oscar:asignaturas oscarmoreira$ ls
algebra			informatica_basica
calculo
MacBook-Pro-de-Oscar:asignaturas oscarmoreira$ cd informatica_basica/
MacBook-Pro-de-Oscar:informatica_basica oscarmoreira$ mkdir teoria practicas
MacBook-Pro-de-Oscar:informatica_basica oscarmoreira$ cd practicas/
MacBook-Pro-de-Oscar:practicas oscarmoreira$ pwd
/Users/oscarmoreira/oscar_moreira/asignaturas/informatica_basica/practicas
MacBook-Pro-de-Oscar:practicas oscarmoreira$ mkdir p1 p2
MacBook-Pro-de-Oscar:practicas oscarmoreira$ cd
MacBook-Pro-de-Oscar:~ oscarmoreira$ pwd
/Users/oscarmoreira
MacBook-Pro-de-Oscar:~ oscarmoreira$ cd oscar_moreira/
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ cat > asignaturas/informatica_basica/teoria/mifichero.txt
Hola mundo!! Soy Oscar Moreira
;)
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ ls asignaturas/informatica_basica/teoria/
mifichero.txt
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ cat asignaturas/informatica_basica/teoria/mifichero.txt
Hola mundo!! Soy Oscar Moreira
;)
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ more asignaturas/informatica_basica/teoria/mifichero.txt ;
Hola mundo!! Soy Oscar Moreira
;)
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ cp asignaturas/informatica_basica/teoria/mifichero.txt asignaturas/informatica_basica/practicas/
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ ls asignaturas/informatica_basica/practicas/
mifichero.txt	p1		p2
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ cd asignaturas/informatica_basica/practicas/
MacBook-Pro-de-Oscar:practicas oscarmoreira$ mv mifichero.txt otrofichero.txt
MacBook-Pro-de-Oscar:practicas oscarmoreira$ ls
otrofichero.txt	p1		p2
MacBook-Pro-de-Oscar:practicas oscarmoreira$ cat otrofichero.txt
Hola mundo!! Soy Oscar Moreira
;)
MacBook-Pro-de-Oscar:practicas oscarmoreira$ cd
MacBook-Pro-de-Oscar:~ oscarmoreira$ cd oscar_moreira/
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ rmdir tmp/
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ ls
asignaturas	varios
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ cd asignaturas/informatica_basica/
MacBook-Pro-de-Oscar:informatica_basica oscarmoreira$ rmdir practicas/
rmdir: practicas/: Directory not empty
MacBook-Pro-de-Oscar:informatica_basica oscarmoreira$ mv practicas/otrofichero.txt ../../varios/otrofichero.txt
MacBook-Pro-de-Oscar:informatica_basica oscarmoreira$ ls practicas/
p1	p2
MacBook-Pro-de-Oscar:informatica_basica oscarmoreira$ cd ..
MacBook-Pro-de-Oscar:asignaturas oscarmoreira$ ls
algebra			informatica_basica
calculo
MacBook-Pro-de-Oscar:asignaturas oscarmoreira$ cd ..
MacBook-Pro-de-Oscar:oscar_moreira oscarmoreira$ cd varios/
MacBook-Pro-de-Oscar:varios oscarmoreira$ ls
otrofichero.txt
MacBook-Pro-de-Oscar:varios oscarmoreira$ chmod 740 otrofichero.txt
MacBook-Pro-de-Oscar:varios oscarmoreira$ ls -l otrofichero.txt
-rwxr-----  1 oscarmoreira  staff  34  9 oct 13:39 otrofichero.txt
```

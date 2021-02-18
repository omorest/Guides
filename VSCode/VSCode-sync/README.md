# Sincronización Configuración Visual Studio Code

En este documento se describrirán los pasos para poder tener la configuración de nuestro VSCode en diferentes dispositivos.

Se usarán dos dispositos para probar que funciona.

## Configurando primer dispositivo

El primer dispositivo será donde iniciemos una cuenta por primera vez y seguiremos los siguientes pasos:

- Lo primero que haremos será ir a las opciones de VSCode y activaremos la sincronización de la configuración.

  ![opcion sync](./img/1.png)

- Una vez ahí se nos abrirá una ventana donde elegiremos cuales serán las configuraciones que queremos sincronizar.

  ![ventana sync](./img/2.png)

- Cuando aceptemos, tendremos que elegir con que cuenta acceder, si con la de Microsoft o Github. En este caso se ha usado la de Github.

  ![opcion login](./img/3.png)

- Esto nos enviará a navegador para aceptar la autorización de usar la cuenta de github.

  ![github aut1](./img/4.png)

___

  ![github aut2](./img/5.png)

- Una vez le demos la autorización nos dará la opción de volver al editor.

  ![nav to editor](./img/6.png)

- Ahora ya tendremos toda nuestra configuración en la nube para sincronizar con otro dispositivo

<br>

## Configurando Segundo Dispositivo

Ahora pasaremos a configurar el segundo dispositivo para que tenga la misma configuración que el primer dispositivo.

Para esto haremos exactamente los mismos pasos que antes.

![conf](./img/8.png)

![github aut](./img/9.png)

Una vez hecho estos pasos como con el primer dispositivo volveremos al editor y veremos que está con la misma configuración que el dispositivo 1

![sincronizado pc2](./img/10.png)

Ya podremos usarlo sin problemas y con la misma configuración que tenemos en todos nuestros dispotivos

<br>

## Fallo en la sincronización

En el caso de que te falle la sincronización y te desaparezca al sincronizar 2 dispositivos no habrá ningún problema, ya que se guarda un historial de la configuración que se ha ido sincronizando.

Esto se usará de la siguiente manera:

- Iremos a las opciones de la configuración

 ![sync options](./img/11.png)

- Luego de esto nos saldrá una ventana donde elegiremos la opción de `show synced data` para que se nos añada a nuestro editor en la barra izquierda.

  ![synced data](./img/12.png)

- Ahora veremos como nos aparece esta opción y podemos ver un historial de la sincronización de la configuraicón.

  ![historial confi](./img/13.png)

Si queremos volver a una configuración pasada simplemente tendremos elegir la carpeta que deseemos del momento que queramos recuperar y darle a la flecha de restaurar que nos saldrá a la derecha y ya lo tendremos.

  ![restaurar](./img/14.png)

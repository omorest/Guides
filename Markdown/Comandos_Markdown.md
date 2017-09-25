Oscar Moreira

# Guía de etiquetas para Markdown

## Heading 2

~~~
      Para los encabezados hasta 6 usaremos "#"
~~~

## Citas

~~~
      > Texto
~~~

> esto es una cita
>
> esto es otra cita

> Esto es una cita




## Listas

### Desordenadas

~~~
      Usamos el guión "-" más un espacio y seguido del texto
~~~

- Elemento 1
- Elemento 2
- Elemento 3


### Numeradas

~~~
      Usaremos numeracion por ejemplo: "1." más un espacio y seguido del texto
~~~

1. Elemento 1
    - Elemento 1.1
2. Elemento 2

3. Elemento 3
    - Elemento 3.1
    - Elemento 3.2


## Separaciones

Esto es una separación
~~~
Tres guiones bajos equivalen a un <hr> en html
~~~
___


## Negritas y cursivas

- Cursiva

    - *Hola mundo.*
    ~~~
    Pondremos el texto entre "*"
    *Hola mundo*
    ~~~

- Negrita

    - **Hola mundo.**
    ~~~
    Pondremos el texto entre dos "*"
    **Hola mundo**
    ~~~

- Negrita y cursiva

  - ***Hola mundo***
  ~~~
  Pondremos el texto entre tres "*"
  ***Hola mundo***
  ~~~

___
___


## Enlaces
- Texto + enlace.
  - Editor Atom <https://atom.io/>
~~~
Texto <Link>
~~~

- Texto como enlace.
  - [Editor atom](https://atom.io/)
~~~
[Texto](Link)
~~~

- Información al pasar el ratón por el enlace.
  - [Editor atom](https://atom.io/ "Enlace para editor atom")
~~~
[Texto](Link) "Texto de información"
~~~

___

## Rutas Imagenes

- Imagen desde un link.

    ![imagenlogoatom](https://curtistimson.co.uk/images/post/atom/atom-editor-logo.jpg)
    ~~~
        ![Texto](Link)
    ~~~


- Imagen desde local.

    ![logoatom](Images/logoatom.png)
~~~
      ![Texto](ruta de la foto)
~~~

___

## Código

- Cajetín para código puntual.

         Aquí iría código

    Dar 3 tabulaciones o 4 espacios en blanco para que salga dentro de un cajetín.

- Cajetín para mucho código.

~~~

De esta manera incluyendo 3 virgulillas por encima y otras 3 por debajo haremos que todo el texo este remarcado.

~~~

- Resaltar código dentro de una frase.

Resaltar codigo con `acentos graves`.

~~~
    `acentos graves`
~~~

___

## Anular Markdown

Usar los símbolos de forma normal y que no se ejecuten como etiquetas.
Solo se necesita poner la barra invertida antes
~~~
Por ejemplo con cursiva \*texto*
~~~

- De esta forma *no funciona*
- De esta forma \*si funciona*

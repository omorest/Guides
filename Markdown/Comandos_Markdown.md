Oscar Moreira

# Guía de etiquetas para Markdown

## 1. Heading 2

~~~
      Para los encabezados usaremos "#" con u nmáximo de 6
      Ejemplo: #   Heading 1
               ##  Heading 2
               ### Heading 3
~~~

## 2. Citas

~~~
  usaremos ">" seguido de Texto
~~~

> esto es una cita
>
> esto es otra cita

> Esto es una cita




## 3. Listas

### 3.1 Desordenadas

~~~
      Usamos el guión "-" más un espacio y seguido del texto
~~~

- Elemento 1
- Elemento 2
- Elemento 3


### 3.2 Numeradas

~~~
      Usaremos numeracion por ejemplo: "1." más un espacio y seguido del texto
~~~

1. Elemento 1
    - Elemento 1.1
2. Elemento 2

3. Elemento 3
    - Elemento 3.1
    - Elemento 3.2


## 4. Separaciones

Esto es una separación
~~~
Tres guiones bajos "___" equivalen a un <hr> en html dibujando una pequeña línea
~~~
___


## 5. Negritas y cursivas

- Cursiva

    - *Hola mundo.*
    ~~~
    Pondremos el texto entre "*"
    Ejemplo: *Hola mundo*
    ~~~

- Negrita

    - **Hola mundo.**
    ~~~
    Pondremos el texto entre dos "*"
    Ejemplo: **Hola mundo**
    ~~~

- Negrita y cursiva

  - ***Hola mundo***
  ~~~
  Pondremos el texto entre tres "*"
  Ejemplo: ***Hola mundo***
  ~~~

___
___


## 6. Enlaces

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

## 7. Rutas Imagenes

- Imagen desde un link.

    ![imagenlogoatom](https://www.logolynx.com/images/logolynx/52/529251d1b4dc034bee512d1e82fa67c1.png)
    ~~~
        ![Texto](Link)
    ~~~


- Imagen desde local.

    ![logoatom](Images/logoatom.png)
~~~
      ![Texto](ruta de la foto)
~~~

___

## 8. Código

- Cajetín para código puntual.

         Aquí iría código

    Dar 3 tabulaciones o 4 espacios en blanco para que salga dentro de un cajetín.

- Cajetín para código grande.

~~~

De esta manera incluyendo 3 virgulillas por encima y otras 3 por debajo haremos que todo el texo este remarcado.

~~~

- Resaltar código dentro de una frase.

  Resaltar codigo con `acentos graves`.

~~~
    `acentos graves`
~~~

___

## 9. Anular Markdown

Usar los símbolos de forma normal y que no se ejecuten como etiquetas.
Solo se necesita poner la barra invertida antes
~~~
Por ejemplo con cursiva \*texto*
~~~

- De esta forma *no funciona*
- De esta forma \*si funciona*

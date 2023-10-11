# ASIX1M4UF1_A3Apuntes

Repositorio de apuntes y todo

###### Primer capitulo: MARKDOWN

formatos de texto
Segun como se ponga los asteriscos* o los guinesbajos_ se pondrá en cursiva o en negrita.
Este texto está en *cursiva*
Este texto está en _cursiva_
Este texto está en **cursiva**
Este texto está en __cursiva__
y de esta forma en negrita y cursiva simultaneamente
Este texto está en **_negrita y cursiva_**

de las siguientes "sintaxis" se hacen las listas
ol
1. Primera opción de menú
2. Segunda opción de menú
3. Tercera opción de menú
UL
* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submemú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    *Tercer submenú
    *Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

esto de las triple comilla es para que no ejecute el codigo, simplemente que lo enseñe sin mas
``` 
<html>
<head>

</head>
<body>
    <p>Esto es un párrafo por eso una "p"
</body>
</html>
```

Así se sube un enlace o link
lo de dentro de corchetes es el texto que saldrá como link en la página real despues de eso se cierra corchete, luego se abre el parentesis y pones el link donde quieres que se rediriga, y después entre comillas se pone un texto que quieres que salga en la web minetras pongas el raton encima del enlace sin clicar. 
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

Así se pone una imagen
Para poner imagenes, se pone primero una exclamación, y se abre corchete, lo que hay dentro es un identificador y se cierra corchete, despúes se abre el parentesis y escribes el link de la url de la foto estando subida en la carpeta del github(NO DEL EXPLORADOR DE ARCHIVOS), seguido poner entre comillas un texto que quieres que salga en la web minetras pongas el raton encima del enlace sin clicar.
![Eso es una imagen del rial G Hasbulla](https://github.com/IvanMorillaTorres/ASIX1M4UF1_A3Apuntes/blob/main/hasbulla-money.gif "Titulo opcional de la imagen ")


Tablas
La cantidad de columnas se basa en la cantidad de barras como esta "|" que contenga la linea de codigo


|Primera col|Segunda col|Tercera col|


 Los textos que están aqui dentro son los titulos de las columnas


|--------------|:------------:|---------:| 


La anchura de la columna se hará segun lo ancho que se ponga con los guiones, y según donde ponga los : definirá si está centrado, a la izquierda o a la derecha.


opciones
 -[ ] Opción A
 
 -[X] Opción B
 
 -[ ] Opción C

Las opciones



###### Segundo capitulo: HTML
En un leguaje de marcas empieza con una etiqueta que se escribe entre <> y para marcar o decir que acaba se escribe la misma etiqueta pero con uns barra delante </>.

la sintaxi basica es, <img href = ""> basicamente es , etiqueta atributo y información del atributo.


Aqui definimos el tipo de pagina que hacemos para decirselo al navegador
<!DOCTYPE html>
            Aqui definimos el idioma 
            <html lang="en">
            Justo aqui empieza el encabezado de datos
            <head>
                esta linea indica el set de caracteres.
                <meta charset="UTF-8">
                Esto simeple mente es para el ancho y demas de la pagina
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                esta linea de codigo es donde se pone el titulo que saldrá arriba en la pestaña de la pagina
                <title>Document</title>
                y aqui acaba el encabezado como siempre acaban las etiquetas de una pagina con la barra"/"
            </head>

            justo aqui empieza el body, que es el cuerpo de la pagina
            <body>

            <p>
            estas etiquestas són las de un parrafo, el cual se abre sin / y se cierra con ella escrita.
            </p>

            el order list es el una lista ordenada en el que abre con ol, y acaba con /ol, la cual cada elemento interno de la lista es un li.
            <ol>
                <li>
                    como este por ejemplo que abre con li, y como todas las etiquetas se cierran con /.
                </li>
                <li>
                    aqui hay otro elemento de la lista
                </li>
                <li>
                    y aqui el tercer elemento
                </li>    
            y ya aqu cerramos el order list      
            </ol>

            a parte de ol se puede hacer como Unorder list(ul).
            o si quiero hacer una lista dentro de otra lista seria lo mismo, haciendo un ol, con la otra lista añadida identada.
            como por ejemplo:
            <ol>
                <li>
                    
                </li>
                <ol>
                    nivel1
                </ol>
                <ul>
                    nivel 2
                </ul>
            </ol>

        
            <br>
                br es una etiqueta pra dejar un salto o espacio 


            <a href="google.com" alt="Por aqui se va a google" target="_blank">aqui dentro va lo que queremos que salga en pantalla</a>
            esto es texto con un enlace a la pagina que se poga, y se escribe con la etiqueta <a href=""></a>
            El alt: srive para poner un texto que aparezca cuando nos ponemos encima del enlace sin clicar
            El target_blank: indica que cuando abras/se clique ese enlace, se abra en otra pestaña diferente a en la que se clica de la pagina.

            <hr> sirve para poner una linea horizontal 
            
            
            Esta etiqueta es una cita, (es una frase de alguien ajeno)
            <blockquote></blockquote>
            


            para mostrar una imagen es , la etiqueta img, con la ruta de donde se saca la imagen,
            <img src="hasbulla-money.gif">
            




            </body>
            </html>







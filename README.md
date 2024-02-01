# ASIX1M4UF1_A3Apuntes


###### Aplicación :GITHUB

creamos cuenta de github(no hay que ser una bestia de la informatica asique lo doy por hecho).
y descargamos en instalamos el GIT (https://git-scm.com/download/win).

cada vez que queramos crear una nueva carpeta para subir archivos, debemos ir a mis repositorios, new repository, y en el menú pondremos el nombre que queramos ponerle, a continuación vamos al cmd del git(boton windows y escribimos git) y dentro vamos a la carpeta donde queramos guardar las carpetas, es decir hacemos un cd y nos situamos en el disoc duro c por ejemplo

Repositorio de apuntes y todo

Seguidamente entramos a la carpeta que queramos subir o donde queramos clonar una del github.

si es clonar escribimos Git clone (link que cogemos de la web)

si queremos subir actualizaciones primero vamos dentro de la carpeta y hacemos:
1.  git init
2.  git add .
3.  git commit -m "comentario que queramos"
4.  git push origin main 

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
```<!DOCTYPE html>```

Aqui definimos el idioma 
```<html lang="en">```

Justo aqui empieza el encabezado de datos
``` <head>```

esta linea indica el set de caracteres.
```<meta charset="UTF-8">```

Esto simeple mente es para el ancho y demas de la pagina
```<meta name="viewport" content="width=device-width, initial-scale=1.0">```

esta linea de codigo es donde se pone el titulo que saldrá arriba en la pestaña de la pagina1
```<title>Document</title>```

y aqui acaba el encabezado como siempre acaban las etiquetas de una pagina con la barra"/"
```</head>```
justo aqui empieza el body, que es el cuerpo de la pagina
``` <body>```
estas etiquestas són las de un parrafo, el cual se abre sin / y se cierra con ella escrita.
```<p> </p>```

 el order list es el una lista ordenada en el que abre con ol, y acaba con /ol, la cual cada elemento interno de la lista es un ```<li>```.

```<ol>
    <li>como este por ejemplo que abre con li, y como todas las etiquetas se cierran con /.</li>
    <li>aqui hay otro elemento de la lista</li>
    <li>y aqui el tercer elemento</li>    
</ol>y ya aqu cerramos el order list```

a parte de ol se puede hacer como Unorder list(ul).
o si quiero hacer una lista dentro de otra lista seria lo mismo, haciendo un ol, con la otra lista añadida identada.
como por ejemplo:
```
<ol>
    <li>
    1
    </li>
    <ol>
        nivel1
    </ol>
    <ul>
        nivel 2
    </ul>
</ol>
```

br es una etiqueta pra dejar un salto o espacio
```<br>```
```<a href="google.com" alt="Por aqui se va a google" target="_blank">aqui dentro va lo que queremos que salga en pantalla</a>```
esto es texto con un enlace a la pagina que se poga, y se escribe con la etiqueta ```<a href=""></a>```
El alt: srive para poner un texto que aparezca cuando nos ponemos encima del enlace sin clicar
El target_blank: indica que cuando abras/se clique ese enlace, se abra en otra pestaña diferente a en la que se clica de la pagina.

```<hr>``` sirve para poner una linea horizontal 
Esta etiqueta es una cita, (es una frase de alguien ajeno)
```<blockquote></blockquote>```

para mostrar una imagen es , la etiqueta img, con la ruta de donde se saca la imagen,
```<img src="hasbulla-money.gif">```

Para usar un icono de una web como por ejemplo fontawesomehay que linkear en el head el ```<script src="https://kit.fontawesome.com/06d159bd36.js" crossorigin="anonymous"></script>``` Escribimos este link/script que nos ha dado la pagina para poder enlazar nuestra pagina para enlaza y linkear cosas de esta, como poer ejemplo podriamos poner para poner un icono o una fuente lo siguiente:```<i class="fa-solid fa-dog">codigo enlazado desde fontawesome</i>``` 


para poner una foto se pone
```<img src="(ubicacion de la foto)" alt="Imgen de planeta">```
para ir a alguna parte dentro de la propia pagina
añadir un id a la parte qu queramos ir a ver(el destino)
añadimos por ejemplo un titulo que queremos que sirva como enlace para ir a ver el destino(origen)

```< h3 id=inicio>```
```<a href="#inicio"><h3>aqui me envia al titulo </h3></a>```
en el  caso que queramos poner una tabla se pone lo siguiente:

```<table border="2px">
    <thead>
        <tr>
            <th>123</th>
            <th>234</th>
            <th>345</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>qwe</th>
            <th>wer</th>
            <th>ert</th>
        </tr>
    </tbody>
    <tfoot>

    </tfoot>
</table>```


en el que table es la etiqueta de la tabla general, tr son las filas en la que escribirmos th por cada columna que quieras poner con el dato a mostrar dentro, si quieres puedes poner un thead o tfoot para hacer un encabezado o un pie de tabla, sino si solo se quiere hacer una tabla sin nada mas, se hace en el tbody.
</body>
</html>






###### Tercer capitulo: CSS


3 formas de insertar css

1. Insertar en la propia etiqueta
2. Añadir en el head de la pagina el link de enlce
3. Archivo externo

Puntos/cosas idividuales: Si solo se quiere poner algo exclusivamente en una parte se puede hacer individualmente.



style (en la misma hoja);;;;;;;;;;;;;;;;;;;;;;;;;;;;;;,

Las hojas css/ archivo externo, sirve para todas las paginas de todo el sitio web.


en una tabla, se pone el atributo style en la etiqueta, se compone por declaraciones:valor
ejemplo: style="text-align: center;color: red;"
esto hace que la tabla o la columna por ejemplo se ponga la letra de color rojo, y la alineación del texto en el centro.

Los colores es pueden poner con la combinacion en exadecimal y en rgb, que seria el siguiente formato(255,255,255), se pone como maximo de cada valor en 255, el minimo es 0, y para hacer los colores se combinan.
ejemplo, si queremos poner en rgb el azul puro se pone (0,0,255), o si queremos el rosa seria (255,0,255).


para modificar un unico elemento como por ejemplo una fila, pero que no se me cambien todas las filas creamos en la fila un atributo que se llama "id" que es un identifiacador unico, y modificar ese id, por ejemplo si el id="PrimeraFila" , para nombrarla y editarla se escribe  #PrimeraFila{y aqui dentro los cambios que se quieran hacer}.

en caso que se quieran cambiar un grupo de partes de la pagina, se escribe en ved de "id", se escribe "class" que para hacer la referencia en vez de poner # como en id, se pone un "." delante del nombre de la clase.
class--> .clasetextoazul
id-->   #identificadorazul


para seleccionar a todo el documento se hace una edidción total con el simbolo "*".
un ejemplo podia ser:
```*{
    color: blue;
}```
+
Hijos y padre para dar formato:
si solo quiero que afecte a hijos que son por ejemplo strong de un li.
se podria en el css tal que así:
li > strong{
    y lo que queramos editar.
}

4 tipos importantes: etiqueta, clase, id, universal

enlaces de css existen mediante : archivo externo,en un style en el head, o en un style en la propia linea de codigo html.



DIVS:

<div> es como una caja que puedes poner en tu página web. Sirve para agrupar cosas juntas.
Identificación con ID:

Puedes darle un nombre especial al div usando ID. Ayuda a decirle al div que es único.

Clases para Agrupar Estilos:

La clase es un atributo que le pones a una etiqueta o div, y puedes darles la misma "clase", para que se puedan modificar todos a la vez.

Anidamiento de Divs:

A veces, un div puede tener otros divs dentro. Es como poner cajas dentro de cajas.

Y todas las clases, divs y etiquetas se pueden modificar para cambiar color, forma, tamaño, comportamientos, etc. El cambio más fácil puede ser cambiar el color de fondo, hacerlo más grande, etc., pero una de las cosas más útiles podría ser modificarles el border, margin y padding. Básicamente, sirve para poder posicionarlos de forma que plazca a la hora de hacer la página web.


#### Tipos de añadidos externos

fontawesome por ejemplo 

En cualquiera de los casos trata basicamente en poner el link de referencia en el head y en el caso de necesitar javascript la pagina que se usa, pues copiar el link en el final del body.
A la hora del uso es necesario poner las class que se indiquen en la web a usar, o copiar el codigo y modificarlo para su uso .
pero nunca modificar las class que traen, o si se modifican ver que no se solape algo de lo que se escriba con el codigo de la pàgina.
Y referenciar bien la ubicacion en caso que sea una imagen o video.


#### Diseño responsive

El diseño responsive es una técnica de diseño web que busca proporcionar una experiencia de usuario óptima independientemente del dispositivo que se esté utilizando, como ordenadoresm, tablet o móviles.

## Media Queries

Las media queries son una forma de aplicar estilos de CSS específicos para diferentes tamaños de pantalla. Para agregar reglas de estilo condicionales basadas en características como el ancho de la pantalla.
ejemplo: 
```css
@media only screen and (max-width: 600px) {
    
}
```

Imágenes que se autoadaptes

Asegúrate de que las imágenes sean adaptables al tamaño de la pantalla utilizando el atributo max-width: 100%; en CSS. Esto evitará que las imágenes se salgan del contenedor en pantallas más pequeñas.




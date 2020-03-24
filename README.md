<h1>1)</h1>

<h2>1.a) ¿Que es un lenjguaje de marcado?</h2>

Los lenguajes de marcas (tambien llamados lenguajes de marcado) son aquellos que combinan la informacion, generalmente textual, que contiene un documento con marcas o anotaciones relativas a la estructura del texto o a la forma de representarlo. El lenguaje de marcas, es el que especifica cuales serán las etiquetas posibles, donde deben colocarse y el significado que tendra cada una de ellas. Asimismo, la presencia de etiquetas o marcas intercaladas en el contenido hace explicita la estructura del documento o cualquier informacion adicional que se  quiera resaltar. Por otro lado,  hay que tener en cuenta que las propias etiquetas o marcas generalmente no se suelen presentar al usuario final, ya que este suele estar interesado en el propio contenido del documento.Los lenguajes de marcado o lenguajes de marcas se pueden definir como una manera de codificar documentos. 

<h2>1.b) ¿Cuál es su utilidad?</h2>

Sirven para establecer etiquetas, marcas o anotaciones que contienen información relacionada con la estructura de dicho texto, su forma de visualización, etc. 

<h2>1.c) ¿Qué es un tag?</h2>

Una etiqueta (tag), también conocido como marca o directiva, es un texto que ve “encerrado”, entre el símbolo menor que (<) y el símbolo mayor que (>).

Existen dos tipos fundamentales de etiquetas: las de inicio (como por ejemplo: <nombre>) y etiquetas de fin (como puede ser: </nombre>). Como se puede observar, las etiquetas de cierre se escriben igual que los de apertura, pero indicando el signo “/” justo antes del nombre de la etiqueta en cuestión. 

Las etiquetas siempre afectan al texto (y otras directivas) que se encuentran dentro de su apertura y cierre. Existen etiquetas que no requieren de apertura y cierre. Para estas, se suele añadir el carácter “/” justo antes de “>”. Por ejemplo: ```html <br/>, <img/>, <meta/> ```, etc.

<h2>1.d) ¿Qué es un atributo?</h2>

Un atributo es un conjunto formado por un nombre y un valor que se localiza dentro de la etiqueta de inicio de un elemento. Este por (nombre-valor) indica alguna propiedad asociada al elemento en cuestión. A continuación,  se muestra un ejemplo de uso de un atributo en un elemento:

```html <elemento propiedad1:"valor">Contenido</elemento> ```

Como se puede observar, después de nombre del atributo se hace necesario incluir el símbolo “=” y a continuación se indica su valor entre comillas. También es posible incluir más de un atributo en un elemento, por ejemplo: 

```html <elemento propiedad1:"valor1" propiedad2:"valor2"> Contenido</elemento> ```

<h1>2)</h2> 

<h2>2.a) ¿Cuál es la utilidad de HTML?</h2>

Es un lenguaje de marcas que permite desarrollar páginas web que sean accesibles a través de la Word wide wide. A partir de este lenguaje, se pueden desarrollar documentos que, entre otras cosas, contengan hipertexto, con enlaces (links) que permiten direccionar al usuario hacia otros recursos de la web.
	
<h2>2.b)¿Que conjunto minimo de tags debe contener un documento elaborado en ese lenguaje? Describe brevemente su utilidad</h2>

Todo documento se descompone de una seccion llamado cuerpo, y otro llamado cabacera. El cuerpo, comprendido entre las etiquetas ```html <body> y </body> ```, es el lugar donde se describe el contenido del documento presentado al usuario de diferentes momentos, en el caso mas comun mediante un navegador web visual.
La seccion de cabecera, encerrado entre las etiquetas ```html <head> </head> ```, contiene informacion acerca del propio documento, constituyendo por tanto un conjunto de metadatos. A excepcion del titulo del documento (encerrado entre las etiquetas ```html <title> </title> ```), el marcado de esta seccion no tiene representacion alguna para quien consultado el documento, sino que es explotado por el propio navegador o robots de buscadores que rastrean la web indexando sus muchos recursos. Parte de la informacion contenido en esta seccion se describe a traves de las etiquetas META (o META TAGS), que suelen contener informacion acerca del documento, como son sus palabras clave, una descripcion resumida de su contenido, informacion de autoria, asi como atras que describe si el contenido caduca, si puede ser almacenado temporalmente por dispositivos intermedios, etc.

<h1>3)</h1> 
<h2>3.a) ¿Cuál es la utilidad e importancia de los enlaces o link entre paginas?</h2>

La utilidad de los enlaces es conectar los distintos recursos de la web, y que esten a disposicion del navegante. Sin los enlaces, no podriamos hablar de navegante o de navegacion si estos archivos HTML no estuviesen debidamente conectados entre ellos y con el exterior de cada sitio web por medio de enlaces de hipertexto. En efecto, el atractivo original del HTML en la posible relacion de los contenidos de los archivos introduciendo referencias bajo forma de enlaces que permitan un acceso rapido a la informacion deseada. 

<h2>3.b) ¿Qué significa hipertexto?</h2>

<h2>3.c) ¿Un link solo puede apuntar a otra página?</h2>

En funcion del destino de los enlaces, son agrupados del siguiente modo:

<ul>
    <li>Enlaces Internos: los que se dirigen a otras partes dentro de la misma pagina</li>
    <li>Enlaces locales: los que se dirigen a otras paginas del mismo sitio</li>
    <li>Enlaces remotos: los dirigidos a otras paginas de otros sitios web</li>
    <li>Enlaces con direcciones de correo: para crear un mensaje dirigido a una direccion</li>
    <li>Enlaces con archivos: para que los usuarios puedan hacer download de ficheros</li>
</ul>
<h2>3.d) ¿Qué importancia tiene esto último?</h2>

la importancia radica en la diversidad al tipo de recurso accedido. No solo permite que se acceda a un lugar especifico de la pagina en la que se navega, al activar un enlace se puede dar lugar a una gran variedad de resultados, como son: trasladarse a un nuevo tema; mostrar una referencia, una definición o una anotación; presentar un esquema o una ilustración; ver un índice o una tabla de datos; activar un sonido o un vídeo, etc.

<h1>4) ¿Cómo funcionan los tags audio y video?</h1>

<h1>5)</h1>

<h2>5.a) ¿Qué es el Rendering Engine de un Browser?</h2>

<h2>5.b) ¿Cuál es el que utiliza cada uno de los 5 browsers más conocidos (Chrome, Firefox, Safari, IE-Edge, Opera)?</h2>

<h2>5.c) ¿Cuál es la importancia de conocer cada uno de ellos en la construcción de un sitio?</h2>

Bibliografia

<h5>libro: Lenguaje de Marcas y Sistemas de Gestion de la Informacion
autor: javier s. surdo
Editorial: RA-Ma
Año: 2014
Origen: Madrid (España)
https://books.google.com.ar/books?id=VI-fDwAAQBAJ&lpg=PA10&dq=lenguajes%20de%20marcado&pg=PA10#v=onepage&q=lenguajes%20de%20marcado&f=false</h5>

<h5>libro: Elaboración de documentos web mediante lenguajes de marcas. IFCD0210
autor: ramon guerrero perez
Editorial: IC Editorial
Año: 2014
https://books.google.com.ar/books?id=Kz51CQAAQBAJ&lpg=PP1&hl=es&pg=PT1#v=onepage&q&f=false</h5>

<h5>libro: Creación de páginas web con el lenguaje de marcas. IFCD0110
Autor: Ramon Guerrero perez
https://books.google.com.ar/books?id=0E4bCAAAQBAJ&lpg=PP1&hl=es&pg=PT18#v=onepage&q&f=false</h5>

<h5>libro: Analitica web:medir para triunfar, "como definir una estrategia digital basado en datos"
autor: Sergio Maldonado
https://books.google.com.ar/books?id=27h3ClYpEM0C&lpg=PA68&dq=conjunto%20minimo%20tags%20html&pg=PA69#v=onepage&q=enlaces&f=false</h5>

<h5>Pagina web:
http://www.hipertexto.info/documentos/lenguajes_h.htm
Publicacion: Lenguajes Hipertextuales, hipertexto: El nuevo concepto de documento en la cultura de la imagen
Autor: Maria Jesus Lamarca Lapuente
Tesis doctoral. Universidad Complutense de Madrid</h5>

<h5>Libro: El gran libro de HTML5, CSS3 y Javascript 
Autor:  Juan Diego Gauchat 
Editorial: Marcombo
Año: 2012
https://gutl.jovenclub.cu/wp-content/uploads/2013/10/El+gran+libro+de+HTML5+CSS3+y+Javascrip.pdf</h5>

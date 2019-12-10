#2
Un dise�o responsivo es poder ver el contenido de manera fluida y dinamica en la mayor cantidad de pantallas.
Patrones de Dise�o hay varios de ellos.
Tama�os porcentuales que ayudan a distribuir el contenido.

Muchas veces nuestro dise�o nos va exiguir que usemos herramientas que permitan desarrollar nuestro tabajo ya que las que ofrece HTML y CSS en algunos casos no llega a ser suficiente para lograr lo que el dise�o pide, seimpre la idea es lograr un dise�o y c�digo bastante limpio, esto puede ser un poco complejo.

Mi sitio web puede incluir el uso de varios patrones de dise�o, no necesariamente tengo que limitar a uno de ellos.

Dentro de este art�culo encontramos diversos Patrones de dise�o Web adaptables
https://developers.google.com/web/fundamentals/design-and-ux/responsive/patterns

Diferencia entre libreria y framework:
https://es.quora.com/Cu%C3%A1l-es-la-diferencia-entre-librer%C3%ADa-y-framework
un framework es un marco de trabajo que contiene librerias y herramientas que nos ayudaran a crear algo de manera m�s r�pida, garantizando la calidad gracias a una metodologia y estructura de trabajo bien definida. Mientras que una libreria es un fragmento de c�digo que nos ayuda a resolver un problema especifico y tiene un proposito concreto.

Una biblioteca es un conjunto de elementos (funciones, clases, tipos predefinidos, constantes, variables globales, macros, etc) que es posible utilizar en un programa para facilitar la implementaci�n de ese programa.

API viene del ingl�s "Application programming interface" que significa "Interfaz para programaci�n de aplicaciones". Es la parte de una biblioteca a la que accede un programa que usa la biblioteca; haciendo as� el uso de la biblioteca independiente de los detalles de implementaci�n. Una API puede ser implementadas por distintas bibliotecas.

Un framework es un conjunto integrado de herramientas que facilitan un desarrollo software. Puede incluir APIs y bibliotecas. Pero tambi�n puede incluir otros elementos como herramientas de depuraci�n, dise�o gr�fico, prototipado, edici�n, etc.

Conceptos nuevos:

Viewport: �rea visible del navegador, solo la que visualizas dentro del espacio de la pantalla, si haces scroll cambiara tu viewport.
Portrait (retrato): orientaci�n vertical del dispositivo.
Landscape (paisaje): horizontal

T�cnicas para abordar el Responsive Desing:
Mobile first: si empiezas un websit desde la menor resoluci�n soportada hasta la mayor
Desktop first: si empiezas un websit desde la mayor resoluci�n soportada hasta la menor, empieza por la resoluci�n m�s grande (Media Queri)
�C�al es mejor?: T�cnicamente Mobile First por posicionamiento de SEO para los clientes que navegan en nuestro sito por medio de dispositivos m�viles �C�mo accederan los usuarios a tu contenido? por medio de google analytics sabras por donde te llegan m�s usuarios. Con el empiezas DESDE el tama�o minimo de pantalla hasta los m�s grande con ello la tendras m�s f�cil pues las pantallas tienden a ser m�s amplias cada vez.

Un par de librerias:
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://cssreference.io

Patrones en Responsive Desing:

Mayormente fluido // Mostly Fluid:
El patr�n Mostly fluid consiste, principalmente, en una cuadr�cula fluida. Por lo general, en las pantallas grandes o medianas se mantiene el mismo tama�o y simplemente se ajustan los m�rgenes en las m�s anchas.
En las pantallas m�s peque�as, la cuadr�cula fluida genera el reprocesamiento del contenido principal, mientras que las columnas se apilan verticalmente. Una de las mayores ventajas de este patr�n es que, en general, solo se necesita un punto de interrupci�n entre las pantallas grandes y las peque�as.

column drop // Colocaci�n de columnas:
En el caso de los dise�os con varias columnas de ancho completo, durante el proceso de colocaci�n de columnas �stas �nicamente se colocan de forma vertical debido a que el ancho de la ventana es demasiado reducido para el contenido.
En un momento dado, todas las columnas se apilan verticalmente. La selecci�n de puntos de interrupci�n para este patr�n de dise�o depende del contenido y cambia para cada dise�o.

Layout shifter:
El patr�n Layout shifter es el m�s adaptable, ya que posee varios puntos de interrupci�n en diferentes anchos de pantalla.
La clave para este dise�o es el desplazamiento del contenido, en lugar de su reprocesamiento y colocaci�n debajo de otras columnas. Debido a las diferencias significativas entre cada punto de interrupci�n principal, es m�s complejo de mantener, y es posible que se deban realizar cambios dentro de los elementos, no solo en el dise�o de contenido general.

Peque�os cambios o midificaciones // Tiny tweaks:
El patr�n Tiny tweaks permite realizar peque�os cambios en el dise�o, como ajustar el tama�o de la fuente, cambiar el tama�o de las im�genes o desplazar el contenido de maneras muy poco significativas.
Funciona correctamente en dise�os con una sola columna, como los sitios web lineales de una sola p�gina y los art�culos con mucho texto.

Off canvas:
En lugar de apilar contenido verticalmente, el patr�n Off canvas coloca contenido menos usado (tal vez men�s de navegaci�n o de apps) fuera de la pantalla y solo lo muestra cuando el tama�o de la pantalla es suficientemente grande. En las pantallas m�s peque�as, el acceso al contenido es posible con solo a un clic.

Ejemplos de webs

Mostly fluid:
https://alistapart.com/
http://simplebits.com/

Colocaci�n de columnas:
https://modernizr.com/
http://weenudge.com/

Layout shifter:
https://www.anderssonwise.com/
https://alistapart.com/d/responsive-web-design/ex/ex-site-FINAL.html

Tiny tweaks:
http://gingerwhale.com/
http://futurefriendlyweb.com/

Off canvas:
https://www.html5rocks.com/en/tutorials/developertools/async-call-stack/
https://store.google.com/countrypicker

mobile first :: https://www.initcoms.com/que-es-mobile-first-posicionamiento/

En este link podre encontrar dise�os para inspirarme y comenzar con algunos proyectos que tengo en mente, tambi�n sabremos como usar adecuadamente el Responsive Desing: https://mediaqueri.es/
Por si acaso! ::::
En desarrollo web, las media queries son un m�dulo CSS3 que permite adaptar la representaci�n del contenido a caracter�sticas del dispositivo como la resoluci�n de pantalla (por ejemplo, un smartphone frente a pantallas de alta definici�n) o la presencia de caracter�sticas de accesibilidad como el braille. Se convirti� en un est�ndar recomendado por la W3C en junio de 2012.1? y es un principio b�sico de la tecnolog�a de Dise�o web adaptativo.

#3
El dise�o reponsivo trata de que el contenido se acomode a cada pantalla sin que pierda la visualizaci�n o se a�ada un scroll horizontal.

Le mucha documentaci�n y empiza aplicar todos los conceptos nuevos que te vayan llegando.

Medidas absolutas y relativas(estas var�an seg�n la condici�n), optimizaci�n, carga de la p�gina...

Te recomiendo que uses esto, lo deja muy bonito sin importar la imagen de fondo:  text-shadow: 1px2px2px#000;

Hosting gratuito sencillo de optener con una interfaz muy intuitiva:
https://www.000webhost.com/

#4
Dentro del inspector de elementos puedes elegir la vista como si fuera un dispossitivo m�vil (F12 luego CTRL + SHIFT + M) ademas de poder elegir el tama�o dependiendo de la marca de los celulares m�s usados, o de un tama�o por defecto que tu definas, puedes elegir el zoom que tendra esa pantalla que acabas de generar, la orientaci�n de la pantalla y si el estado de la red de ese dipositivo, en une menu apartado que es coformado por tres puntos sobre el mismo contenedor de las demas opciones podemos mostrar unas reglas para medir el sitio, permite mostrar los mediaQuerys que tenga el sitio mostrando el tama�o exacto donde el contenido se empieza a modificar por su reponsividad, tiene la opci�n de tomar un screenshot completo o parcial del viewport de la p�gina conforme tambi�n con la resoluci�n que hayas establecido (esto resulta �til para mostrar dentro de un equipo de trabajo o a un cliente c�mo va el proyecto, qu� avances a tenido visualmente), por �ltimo esta una opci�n para restaurar a los valores por defecto de este curioso men�. Un doble clic sobre el recuedro que comprende el viewport para hacer un zoom.

Para la creaci�n de una p�gina web usualmente se dara un soporte minimo a un ancho de 320px que es el estadar de tama�o de pantalla que manejan la gran cantidad de dispositivos m�viles, y este m�ximo representa hasta donde se vera bien el sitio web. Si por otro lado decidiera que mi contenido fuera responsivo en todos los momentos llegara el punto que alguno de los elemntos del documento HTML no cabra dentro del ancho.

#5
Viewport es el �rea visible de la patalla en el navegador, al hacer la pantalla m�s peque�a el viewport tambi�n lo har�.

No perder la lecturibilidad del sitio web, para empezar a forzar estos escalados dentro del sitio web existe la etiqueta de metadatos llamada viewport, para que el contenido no escale seg�n los tama�os que le he definido, sino que escale seg�n los tama�os del dispositivo.

<meta name="viewport" content="">
Tenemos la equiqueta metadatos, recibe el atributo name="tipo de dato que va a maniular este meta dato, en este caso <<viewport>>", ahora manipularemos el tama�o que tendra mi contenido cuando se va a ver dentro de mi dispositivo content="width" o "initial-scale" o "maximum-scale"
	"width=320" esta medida solo maneja la �nidad px por lo tanto no es necesario agregarla. Esto puede resultar algo arbitrario.
	"width=device-width" en este caso el ancho sera igual al ancho de mi dispositivo
	"width=device-width, initial-scale=1" con una coma separamos el segundo parametro que vamos a ingresar initial-scale= aqu� agrego valores desde 0 a 1 donde cero es el 0% y uno el 100%, los numeros negativos (-1,-2...) serian el zoom out y los positivos (1,2...) zoom in, como su nombre lo dice me esto dara la escala inicial que tendra mi p�gina en su primera carga.

En ocaciones el cache queda guardado dentro de las herramientas de desarrollador (developers tools) por lo que es necesario en ocaciones cerrarlo y recargar la p�gina para que aparescan los cambios.

Comentario:::::=====>
Metadatos(Meta):
Los metadatos son datos (informaci�n) sobre datos.
La etiqueta <meta> proporciona metadatos sobre el documento HTML. Los metadatos no se mostrar�n en la p�gina, pero se analizar�n por m�quina.
Los metaelementos se usan generalmente para especificar la descripci�n de la p�gina, las palabras clave, el autor del documento, la �ltima modificaci�n y otros metadatos.
Los metadatos pueden ser utilizados por los navegadores (c�mo mostrar contenido o recargar la p�gina), motores de b�squeda (palabras clave) u otros servicios web.
HTML5 introdujo un m�todo para permitir que los dise�adores web tomen el control de la ventana gr�fica (el �rea visible del usuario de una p�gina web), a trav�s de la etiqueta <meta>.

Comentario:::::=====>
Info del tag para su mejor comprenci�n
https://www.htmlcinco.com/etiqueta-meta-viewport-web-movil/
https://developer.mozilla.org/es/docs/M%C3%B3vil/Viewport_meta_tag

Comentario:::::=====>
width=device-width para que se adapte seg�n la pantalla del dispositivo
initial-scale=1.0 para indicar el escalado seg�n el dispositivo

#6
La propiedad de de medida em establece un tama�o para la letra seg�n la referencia de la medida padre, si esta llega a ser una propiedad em que adopto la medida en px de un padre el valor para el siguiente em sera el de su em padre, en el caso de que en alguna etiqueta hija de uno de estos em se estableciera el tam�o de la funte aprtir de all� cambiaria la medida para los sigientes elementos.

<nav> font-size: 16px;
  <ul> font-size: 2em; <!--esto equivale a 32px-->
   <li> font-size: 1em; <!-- este equivale a 632px -->
     <a href=""> hola! </a> font-size: .5em;  padding: 2em <!-- para este caso .5em equivale a 16px, mientras el em de padding es de 32px ya que se establecio en la etiqueta <<a>> el tama�o de la letra por defecto la siguente propiedad <<em>> partira desde ese tama�o establecido-->
   </li>
  </ul>
</nav>

la propieda <<rem>> toma el tama�o de la fuente del ancestro m�s lejano (html o body), si llegaramos a cambiar el valor cambiari�n el resto de propiedades.
<!DOCTYPE html> 
<html lang="en">font-size: 32px; <!-- aqu� estableceremos la medida general para todo el documento -->
<head></head>
<body> font:size: 16px;
  <ul> font:siz: 2rem; <!-- aqu� la propiedad <<rem>> equivale a 64px -->
    <li> font-size: 1rem; <!-- equivale a 32px -->
      <a href=""></a> font-size: .5rem; <!-- equivale a 16px -->
    </li>
... aqu� van las etiquetas de cierre jajajja

enlaces:::::::::===>
https://franciscoamk.com/unidades-de-medida-en-css/

Comentario:::::=====>
/* 1em = 16px , 2em =32px , 4em= 128px (em siempre tomara el valor de la anterior medida relativa) 
1rem =32px , 4rem= 128px , 6rem= 192px (rem siempre tomara el valor de la primera unidad relativa que com�nmente se encuentra  on el body o en el html) */

Comentario:::::=====>
Una manera de verlo, es pensar los rem como una variable, si le declaras al body por ejemplo un fontSize de 20px, a partir de ah� tu �variable� rem es igual a 20px, no importa donde lo utilices. Y si despu�s quieres modificar el valor del rem, solo lo cambias en un solo lugar.

Comentario:::::=====>
Lo primero que debes tener en cuenta es que estas medidas son maleables, en la medida en que dependen de su fuente de origen o medida madre. Entre ellas se encuentran el porcentaje (longitud referente al tama�o de los elementos padre), los em (unidad relativa al tama�o de fuente especificada m�s cercano), los rem (unidad relativa al tama�o de fuente especificada en el ancestro m�s lejano, como html o body) y tama�os del viewport vw/vh (longitud relativa porcentual con respecto al viewport).
.
Medidas �tiles en Responsive Design
.
- %: Porcentaje, se mide en referencia a la longitud de los elementos padres, por lo que abarcara simpre el porcentaje de los tama�os ya especificados o por defecto.
- em: Unidad relativa al tama�o de fuente m�s cercana, la fuente m�s cercana corresponde primero al elemento mismo, sino lo hace con el elemento padre mas cercano que tenga fuente definida y donde 1em corresponde a ese tama�o de fuente.
- rem: Unidad relativa al tama�o de fuente m�s lejana (html o body).
- vw/vh: Unidad relativa conceptual en relaci�n al Viewport (�rea visible del navegador) y estas solo se van a modificar cuando hagamos resize (cambiar el tama�o de la ventana)
           * 100 vw: 100% del width con respecto al Viewport actual.
           * 100 vh: 100% del height con respecto al Viewport actual.

#7
Media queries permiten adpatar la representaci�n del contenido a caracter�sticas del dispositivo.

@media  Un_media_type and (condicion(s)) {
}

@media screen and (max-width: 768px) {
} //Todas la pantallas con un ancho inferior o igual 768px cumplen esta condici�n.

@media screen and (max-width: 768px) and (min-width: 480px) {
} //Todas las pantallas con un ancho de 480px hasta 768px cumplen esta condici�n.

min-width = DESDE
max-width  = HASTA

Se usa regularmente el tipo SCREEN pero en ocaciones tambi�n se usa PRINT para imprimir el web-site, se imprime algo como un screen-shot por lo que el contenido suele adaptarce pues en cuanto a impresi�n se busca ahorrar tinta y ocultar los backgrounds que no estan permitidos dentro de los tipos de medios para impresi�n.

enlaces:::::::::======>
https://themeover.com/mobile-first-vs-desktop-first-responsive-design/
https://css-tricks.com/totally-forgot-print-style-sheets/ se puede ahondar m�s sobre el @media print, adem�s muestra que desde el inspector de Chrome se pueden emular los media queries que tenga el proyecto!

comentario:::::======>
all | Valor por defecto, usada por todos los tipos de media
print | Utilizado para impresoras
screen | Se utiliza para pantallas de ordenador, tabletas, tel�fonos inteligentes, etc.
speech | Se utiliza para lectores de pantalla que �lee� la p�gina en voz alta
@media all and (condici�n) {}
@media print and (condici�n) {}
@media screen and (condici�n) {}
@media speech and (condici�n) {}

#8
Podemos incluirlos dentro de una hoja de estilos aparte y dentro de la etiqueta <<style>>. 
Para usar desktop first empieza por la resoluci�n m�s amplia, usa los estandar de las resoluciones de pantallas que actualmente abarcan el mercado.

@media screen and (max-width: 768px) {
  body {
    border: 10px solid green;
  }
}  //Trazar una l�nea nos ayuda testear nustros estilos de @media

enlaces:::::::::::::::::====>
https://developer.mozilla.org/es/docs/CSS/Media_queries
https://developers.google.com/web/fundamentals/performance/http2/?hl=es

Rositorio del curso:::::
https://github.com/LeonidasEsteban/responsive-design-portafolio

#9
Para hacer que la p�gina sea responsiva hay que empezar a quitar los valores fijos que hayamos definido, a�adir la propiedad de flex-wrap: wrap; para que los elementos se apilen uno sobre otro cuando el viewport sea vea reducido.

enlaces:::::::::::::::::====>
https://flexboxfroggy.com/#es
Ac� podemos apreciar a Bruce Lee hablando sobre el dise�o responsivo y como debe de funcionar en distintos dispositivos para nuestros usuarios:
https://www.youtube.com/watch?v=cJMwBwFj5nQ
https://css-tricks.com/snippets/css/a-guide-to-flexbox/


comentario:::::======>
Flex-wrap es una propiedad de flexbox, bootstrap 4 ya viene con flexbox dentro de sus propiedades, con bootstrap no tienes que manejar flex-wrap como tal, si lo manejas, lo recomendable es que lo hagas con la sintaxis de bootrstrap, en lo personal prefiero usar grid layout y flexbox, queda mas rapida la pagina y es igual funcional, aunque si puedes llegar a sacrificar velocidad de implementaci�n

Bootstrap es un framework front end. bootstrap no es de html, ni de css ni de javascript, pero si las utiliza para facilitarte las cosas de tal manera que sea mas rapido la codificaci�n de tus interfaces, entonces tu decides si usas bootstrap o grid, ya que bootstrap maneja su propio sistema de grillas, en lo personal prefiero no implementar estos tipos de framework por performance de mis productos.

comentario:::::======>
Max-width y flex-wrap
Se deben retirar los elementos tipo �contenedor� de tama�os fijos a tama�os variables.
La propiedad flex-wrap es fundamental para este tipo de practicas adaptables, puesto que con el valor de �wrap� los elementos no se comprimen en anchos peque�os, sino que al contrario pasan a una nueva l�nea.
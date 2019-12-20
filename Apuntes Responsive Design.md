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

enlaces::::::::::::==========>
Hosting gratuito sencillo de optener con una interfaz muy intuitiva:
https://www.000webhost.com/
Link con el portafolio (Proyecto):
https://github.com/LeonidasEsteban/responsive-design-portafolio-preview

comentario::::::::======>
Mi opini�n sobre el men� hamburguesa
El usuario identificar� el men� hamburguesa, pero lo usar� solamente si tiene mucha intenci�n, es m�s recomendable mostrar los men�s siempre visibles, el men� hamburguesa lo recomiendo para contenido de tu website que tenga poca prioridad en tu sitio.
�sto tiene varias razones de ser:
1. Los usuarios nevegan con el pulgar y la parte m�s lejana del dispositivo es la parte superior izquierda, donde se localiza el men� hamburguesa.
2.  por inter�s, normalmente al usuario no le interesa tu sitio y navega a ciegas, por lo que darle click a un bot�n para abrir un men�, realmente no le llama la atenci�n (aunque sepa c�mo se hace)
3. El m�s importante es que si quieres hacer un bot�n que sea clickeado es mejor poner la interacci�n en contexto, que salga el bot�n cuando m�s lo necesite el usuario
Si vas a utilizar un men� hamburguesa, plant�ate cambiarlo por un men� de tabs (m�ximo 5 opciones), �sto para mostrarle las opciones y evitarle fricciones al usuario (a menos que tu intenci�n sea que s�lo usuarios s�per interesados usen tu men�, que a veces es lo que se busca, por ejemplo, en facebook), aunque la mejor opci�n siempre ser� mostrar de manera contextual tus interacciones.


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


#10 y 11
Para comenzar a trabajar en el dise�o responsivo por partes podemos comentar la parte del documento HTML  que no trabajaremos durante ese proceso hasta que completemos la secci�n a la que deseamos dar vida resposive, o bien comentarlo por secciones e ir descomentado seg�n convenga. En algunos casos tendras uno que otro comentario por all�, as� que para hacer un comentario de cierto contenido que seleciones y deseas hacerlo por medio de shortcut del editor tendras algunos incovenientes con estos comentarios que tengas.

Adicional: el back slash nos permite ecapar alg�n signo reservado de HTML como el signo mayor que >

Usaremos la opci�n: show media queries, esto nos mostrara en la parte supuerior las medidas que definimos para esos media queries en el archivo CSS, puedes jugar con el zoom de la vista y revisar si el navegador no tiene ya uno aplicado por defecto para todas las p�ginas.

max-width: 1000px; los elemento ocuparan un ancho m�ximo de 1000px, pero eso depende de sus hijos por que si sus hijos tienen menos tama�o de esos 1000px juntos quiere decir que el contenedor tambi�n tendra menos tama�o.
Si a esto le agregamos un width: 100%; podemos lograr que el contenedor se adapte a ese ancho m�ximo. Otra alternativa a este width: 100%; es utilizar cosas de flex, flex: 1; (flex-grow + flex-shrink) que al igual que width: 100%; tomara todo el ancho disponible, con la diferencia que en caso de colocar un padding no tendriamos el problema de que ese ancho m�ximo aumentara.

para un max-width: 768px (que es la resoluci�n de un ipad) esto quiere decir que hasta esa resoluci�n la pantalla se vera as�, y para resoluciones m�s bajitas que el ipad restamos un p�xel.

Para el selector usaremos la proiedad <<height>> con el valor <<auto>> no serviran dentro de Responsive Desing para resetear valores.

Sal del inspecionador de elementos, recarga la p�gina y vuelve a ella para visualizas los cambios, es posible que el cache se almacene dentro del inspector y no muestre los cambios que hemos generado.

enlaces:::::::::::::::::====>
https://caniuse.com/
https://developer.mozilla.org/es/docs/Web/CSS/:nth-child

comentario:::::======>
La propiedad flex puede recibir tres par�metros:
flex-grow: Define la capacidad de crecer de un elemento. El valor por defecto es 0, si se le coloca 1 entonces va a intentar tomar todo el espacio disponible.
flex-shrink: Define la capacidad que tiene el elemento de encogerse. El valor por defecto es 1.
flex-basis: Define el tama�o predeterminado del elemento antes de ser distribuido en el espacio restante.

comentario:::::======>
nth-child es una pseudo instrucci�n usada para acceder a hermanos en especifico, ya que tal vez quiero darle algunas propiedades a unos elementos, m�s no a todos, en esa secci�n dije que en la clase 
Puedes leer m�s sobre eso en la siguiente p�gina.
https://developer.mozilla.org/es/docs/Web/CSS/:nth-child

comentario:::::======>
me parece que hay muchos cambios y eso lleva que sean muchas lineas para los media queries(son casi el doble de los estilos utilizados en la pagina normal) �sera posible desde el momento de la maquetacion de la pagina, ponerlos de una menera dise�ada para poder realizar m�nimos cambios posibles para hacerlo adaptable?

Saludos, si, asi es, lo ideal es que los estilos generales del sitio web los coloques fuera de los media queries, siempre y cuando estos sean los mismos en las versiones responsive, yo te recomiendo que en los estilos generales coloques todo en relacion a los colores, tipo de fuentes, ancho y alto de los elementos en % y automatico casi siempre y en los media usa todo relacionado a las tama�os de letras, a la distribuci�n del contenido, a los cambios de display etc, como dice el profesor leonidas, mientras menos estilos en los queries quiere decir que tu sitio web es mas elastico, flexible y facil de mantener.

comentario:::::======>
Ajustar header
Anotaciones:
No Es recomendable ajustar el ancho del contenedor del header variable con un width de 100%, puesto que este valor se suma aun mas cuando agregamos relleno al elemento, por lo que seria mas recomendable usar una propiedad flexbox que fusiona al flex-grow junto con flex-shrink, la cual se llama solo flex, con un valor de 1 y esto arregla el problema de ocupar todo el ancho disponible.
El ipad tiene un ancho fijo de 768 px
El valor �auto� funciona mucho para el responsive design a la hora de resetear valores.
Ej: height: auto;
Es recomendable para pantallas inferiores al ipad, configurar el display del header como block.
El valor de initial es recomendable para volver a asignar el valor por defecto que tenia el elemento.

#12
Usamos porcentajes para que las dimenciones de nuestra p�gina se ajuste mejor, en el caso de elemtos que compartan un espacion horizontal distrubuiremos el 100% entre los dos.

Es mucho mejor usar anchos automaticos y vistas en bloque para mejorar el renderizado de la p�gina, cuando una imagen este en un viewport m�s chico hara rezise automticamente.

Dentro de los media queries haremos que los tama�os de fuente sean relativos, para ello usaremos los em.

Usar display con valor block para en las media queries, en el momento que la p�gina adquiera ese tama�o obtendra ese valor.

Setear: asignar un valor prederminado.
Los margenes tambi�n deben ser variables los pondremos en em para que aspu sean relativos. Con esto conseguiremos reducir el espacio entre los textos al tener menos espacio en el viewport.
As� iremos ajustando proporcionalmente la p�gina.

enlaces:::::::::========>
https://www.ionos.mx/digitalguide/paginas-web/diseno-web/tipografia-para-el-diseno-responsivo-con-css
https://www.imaginanet.com/blog/minmaxing-aprendiendo-vmin-y-vmax-en-css.html
https://desarrolloweb.com/articulos/funciones-recursivas-recursividad.html
De acuerdo con este art�culo, el tama�o de fuente ideal es aquel que permite colocar entre 7 y 13 plabras por l�nea:
Usar tipograf�a en tiempos de dise�o responsive
https://platzi.com/blog/tipografia-responsive/

comentario:::::::::======>
Puedes usar cualquier unidad medida, pero el uso de unidades de medida relativas como em o rem te facilitar� el cambio de tama�o de fuente como lo desees para cada breakpoint.
El valor de la unidad em es din�mico, y equivale al valor que tenga su elemento padre.
El valor predeterminado del navegador a menudo es de 16px. Entonces, por defecto 1em = 16px y 2em = 32px.
Lo que Leonidas hizo fue establecer el font-size usando em, siguiendo el dise�o de la version desktop, sin cambiar el valor predefenido de la fuente que es 16px, para que en el breakpoint de 480 solo declarar� la font-size: 12px; (en este punto 1em = 12px) y as� autom�ticamente se redujera el tama�o de las las fuentes siguiendo el dise�o original.

comentario::::::::=======>
Siempre es mejor tener las cosas en diplay: block y en width: auto porque da mucho mejor rendimiento en el render del navegador. (Es mejor el ancho auto que ancho 100%� �Toda la vida!)
replica:::: diserto un poco de esto pues mejoran el render al colocarlos dentro de los media queries y no en la p�gina en tama�o de escritorio donde sera necesario que el display sea flex

comentario::::::::====>
Esta es una excelente l�nea de codigo en CSS, mediante calc, calculamos el ancho de la fuente dependiendo del viewport. Donde 19 es el tama�o maximo, en desktop y 14 es el minimo para pantallas peque�as. Lo mas interesantes es que sus valores varian segun su viewport, osea que toma todos los valores entre 14 y 19
font-size: calc(14px(valor minimo) + (19(valor m�ximo) - 14) * ((100vw - 300px) / (1600 - 300)));

comentario::::::::::::=======>
Pasos para hacer imagenes responsive:
I. En los estilos generales
a. Declarar el width de la imagen y el max-width: 100%;
b. Declarar el width del contenedor de la imagen en medidas relativas
II. En la Query
a. Declarar el width: auto en el contenedor de la imagen.
Pasos para hacer textos responsive:
I. En la Query
a. Declarar un font-size en px al elemento que contiene todos los textos, el cual servir� como gu�a para el em
b. Declarar los em para cada texto en la primera query
NOTA
a. Al darse la necesidad de redimensionar los tama�os del texto en otra query (o la proxima) el �nico valor que se deber� cambiar para que todos los textos configurados relativamente se adapten automaticamente es el font-size del contenedor previamente declarado en pixeles.

#12
Revisamos como se ve el dise�o en nuestra visi�n general, prueba con el inspector de elementos a quitar o a�adir propiedades y valores.

Si un elemento de CSS tiene una clase y una etiqueta (.event img) pero antes le puse un estilo directamente a la etiqueta (img) la etiqueta tendra la prioridad.

Breakponit = punto de ruptura

margin: 10px(arriba) 10px(derecha) 10px(abajo) 10px(izquierda)
margin: 5%;                /* 5% para todos los lados */
margin: 10px;              /* 10px para todos los lados */
margin: 1.6em 20px;        /* 1.6em arriba y abajo, 20px izquierda y derecha */
margin: 10px 3% 1em;       /* 10px arriba, 3% izquierda y derecha, 1em abajo */
margin: 10px 3px 30px 5px; /* 10px arriba, 3px derecha, 30px abajo, 5px izquierda */
margin: 1em auto;          /* 1em arriba y abajo, centrado horizontalmente */
margin: auto;              /* 0px de margen vertical, centrado horizontalmente */

Mediante el inspector de elementos, podemos revisar si determinado elemento tiene una propiedad, para ello nos situamos sobre la pesta�a <<computed (disposici�n)>> que esta de segundas junto a <<styles (estilos)>> all� podremos realizar la consulta y saber si el elemento cuenta con dicha propiedad.

comentario::::::::======>
Anotaciones:
Cuando hay unidades de m�rgenes o relleno, es recomendable hacer la sumatoria al momento de ajustar porcentajes a las unidades de ancho. Ejemplo: 48% width (para repartir entre 2 elementos), mas 1% de margin, que en total sumarian 48% + 48% + 1% + 1% +1% +1%.
Cuando agregamos una medida a un selector hijo de etiqueta, y queremos hacer una configuraci�n posterior pero con el selector de clase, el selector de etiqueta prevalece y vale m�s, por lo que se debe hacer la reconfiguraci�n con el selector de etiqueta.
Ej: .event-image valdra en este caso menos que .event img


#14
Para saber cuanto vale un em que hayas definido ve al medelo de caja donde se asigno ese valor y all� veras las medidas.

display: flex; en algunas ocaciones, sino es que en todas, arruina el modelo de caja, se ve la necesidad de resetearlo dentro de media queries.

Ver proporciones por medio del inspector del elementos y como los elementos van encajando bien dentro del tama�o de viewport que tienes disponible.

enlaces::::::::======>
emojis en HTML:
https://steemit.com/spanish/@rojassartorio/emojis-muy-pro-para-steemit
https://emojipedia.org/
https://developer.mozilla.org/es/docs/Web/CSS/flex-wrap
res�menes de Minei Toshio:
https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso de Responsive Design
https://developer.mozilla.org/en-US/docs/Web/CSS/text-align
https://www.freecodecamp.org/news/how-to-use-the-position-property-in-css-to-align-elements-d8f49c403a26/

#15
Al invocar la propiedad position junto con alguno de sus valores desbloqueamos las propiedades: top, buttom, left, right a las que podemos asignar tanto valores positivos como negativos o diferentes unidades de medida.
con la propiedad fixed dejamos el objeto con una posici�n fija
los elementos se ordenan por defecto al lado derecho.

Si queremos que al llegar a cierta secci�n esta nos comienze ha seguir hay dos opciones: 1. con JavaScript leemos el evento del escroll y cuando lleges a esa posici�n asignar el valor fixed
2. mediante la propiedad position y el valor sticky.


enlaces:::::::::::::::=======>
https://codepen.io/LeonidasEsteban/pen/VGWzWK
Tienes un editor de c�digo oneline:
https://codepen.io              https://repl.it/
https://developer.mozilla.org/es/docs/Web/CSS/position
aprendan a hacer una lista de b�squeda por Abecedario:
https://alligator.io/css/position-sticky/
 para entender un poco m�s de las posiciones:
https://alligator.io/css/position-sticky/
Resumen:
https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Responsive%20Design
un monton de cursos:
https://github.com/MineiToshio/CursosPlatzi

https://www.freecodecamp.org/news/how-to-use-the-position-property-in-css-to-align-elements-d8f49c403a26/


comentario::::::::::::::===========>
tipos de posiciones
-static = la predeterminada estatica
-absolute = se sale de donde estaba ubicado inicialmente, pierde su espacio y se va a colocar de manera absoluta, Va a ser relativo con el objeto mas cercano que tenga seteado el position relative
-fixed = fijo es un elemento fijo que se queda alli y se queda all� as� hagamos scroll
-sticky = es cuando pasas una secci�n haciendo scroll y se te pega en la parte superior o donde quisieramos

Cuando aplicamos cualquiera de estos position se desbloquean:
z-indez
top bottom left y right y sirven para mover el elemento a donde quisieramos

comentario::::::::::============>
/* POSICIONES:
static / PREDETERMINADA
relative / PUEDES MOVERLO, PERO EL ESPACIO que OCUPABA SEGUIR� ESTANDO
absolute / SE SALE DEL LUGAR DONDE ESTABA UBICADO, Y SE UBICA DE MANERA ABSOLUTA Y RELATIVA
CON EL ELEMENTO M�S CERCANO QUE TENGA POSICION RELATIVA,
O POR DEFECTO EN NUESTRO ULTIMO ELEMENTO DE NUESTRO HTML, BODY O HTML
fixed / PARA FIJAR UN CONTENIDO Y QUE TE PERSIGA
sticky / PARA FIJAR UN CONTENIDO DESPU�S DE �SUPERARLO�

  position: posicion;
CUANDO SE UTILIZA ALGUNA POSICION
QUE NO SEA LA PREDETERMINADA
SE NOS DESBLOQUEAN ESTAS PROPIEDADES:
z-index
top right bottom left */

comentario:::::::::======>
TIP: S�lo va a tener el estilo de Sticky dentro de su elemento padre.

#16
Las pociciones absolutas tienen que ser relativas a algo de lo contrario se ira hasta donde pueda ocupar espacio.

Requieres de "buen gusto" para realizar dise�os que sean optimos que se vean bien, como la lecturabilidad del texto dentro de la p�gina y que las cosas funcionen. Puedes darle un background a la fuente con rgba() o con una imagen con la cual el texto tenga m�s legibilidad.

enlaces::::::::::::::=====>
Dejo la compatibildad de position: sticky; en todos los navegadores https://caniuse.com/#feat=css-sticky , para quien no la conozca https://caniuse.com/es es una gran herramienta para ver la compatibilidad de nuestro codigo en los navegadores. Tb hay extensiones para ver si nuestro codigo es compatible dentro del propio editor como vscode-caniuse o para anadir prefijos como autoprefixer
https://luisdark123.github.io/MediaWeb_repository/

comentario::::::::::::======>
Overflow debes asignarla al contenedor que deseas que tenga el comportamiento de ocultar o dejar desbordar su contenido.

comentario::::::::::::::::==========>
Ejemplos de uso del z-index:
Si creamos un Navbar-menu fijo o Sticky tendremos que usar la propiedad z-index para que ning�n otro elemento de nuestro sitio se sobreponga.
Al hacer responsive habr� algunos elementos, como la imagen del hero y el h1 del portafolio de leonidas, que se colocaran uno debajo del otro y si queremos arreglarlo metiendo ese texto dentro de la imagen usaremos posiciones relativas y absolutas. Aqui es cuando los elementos pueden visualizarse o no dependiendo en la capa z-index que se encuentren. Entonces asignaremos, como en la clase, un valor al z-index para que la imagen se vea en la capa 1 y el h1 se vea en la capa 2.
Z-index es una buena herramienta muy �til para transponer elementos que queremos que oculten o sobrepongan a otros.
Como buena practica te recomiendo usar z-index solo en elementos que realmente lo necesitan por que yo hize una web con puras posiciones relativas cuando no entendia lo del display block e inline block y a todo le puse z-index cuando no era necesario.
https://luisdark123.github.io/MediaWeb_repository/

#17
  <video class="html-video" src="aqu� ira la ubicaci�n del archivo o la URL" width="1640" height="360" controls></video>
Al usar un max-width con un video se usa el m�ximo de ancho que hayamos definido para ese elemento
con un ancho del 100% lograremos que se amplie en todo el entrorno que tiene disponible dentro de la p�gina.

enlaces::::::::=======>
https://lenguajehtml.com/p/html/multimedia/etiquetas-html-de-video
Documentacion de audio y video:
audio https://developer.mozilla.org/es/docs/Web/HTML/Elemento/audio
video https://developer.mozilla.org/es/docs/Web/HTML/Elemento/video

comentario:::::::::::::=========>
Vas a youtube y en compartir vas al boton insertar y copias el codigo que te da. Como este:
<iframe width=�560� height=�315� src=�https://www.youtube.com/embed/cqpzCLjjgJU� frameborder=�0� allow=�accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture� allowfullscreen></iframe>

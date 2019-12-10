#2
Un diseño responsivo es poder ver el contenido de manera fluida y dinamica en la mayor cantidad de pantallas.
Patrones de Diseño hay varios de ellos.
Tamaños porcentuales que ayudan a distribuir el contenido.

Muchas veces nuestro diseño nos va exiguir que usemos herramientas que permitan desarrollar nuestro tabajo ya que las que ofrece HTML y CSS en algunos casos no llega a ser suficiente para lograr lo que el diseño pide, seimpre la idea es lograr un diseño y código bastante limpio, esto puede ser un poco complejo.

Mi sitio web puede incluir el uso de varios patrones de diseño, no necesariamente tengo que limitar a uno de ellos.

Dentro de este artículo encontramos diversos Patrones de diseño Web adaptables
https://developers.google.com/web/fundamentals/design-and-ux/responsive/patterns

Diferencia entre libreria y framework:
https://es.quora.com/Cu%C3%A1l-es-la-diferencia-entre-librer%C3%ADa-y-framework
un framework es un marco de trabajo que contiene librerias y herramientas que nos ayudaran a crear algo de manera más rápida, garantizando la calidad gracias a una metodologia y estructura de trabajo bien definida. Mientras que una libreria es un fragmento de código que nos ayuda a resolver un problema especifico y tiene un proposito concreto.

Una biblioteca es un conjunto de elementos (funciones, clases, tipos predefinidos, constantes, variables globales, macros, etc) que es posible utilizar en un programa para facilitar la implementación de ese programa.

API viene del inglés "Application programming interface" que significa "Interfaz para programación de aplicaciones". Es la parte de una biblioteca a la que accede un programa que usa la biblioteca; haciendo así el uso de la biblioteca independiente de los detalles de implementación. Una API puede ser implementadas por distintas bibliotecas.

Un framework es un conjunto integrado de herramientas que facilitan un desarrollo software. Puede incluir APIs y bibliotecas. Pero también puede incluir otros elementos como herramientas de depuración, diseño gráfico, prototipado, edición, etc.

Conceptos nuevos:

Viewport: área visible del navegador, solo la que visualizas dentro del espacio de la pantalla, si haces scroll cambiara tu viewport.
Portrait (retrato): orientación vertical del dispositivo.
Landscape (paisaje): horizontal

Técnicas para abordar el Responsive Desing:
Mobile first: si empiezas un websit desde la menor resolución soportada hasta la mayor
Desktop first: si empiezas un websit desde la mayor resolución soportada hasta la menor, empieza por la resolución más grande (Media Queri)
¿Cúal es mejor?: Técnicamente Mobile First por posicionamiento de SEO para los clientes que navegan en nuestro sito por medio de dispositivos móviles ¿Cómo accederan los usuarios a tu contenido? por medio de google analytics sabras por donde te llegan más usuarios. Con el empiezas DESDE el tamaño minimo de pantalla hasta los más grande con ello la tendras más fácil pues las pantallas tienden a ser más amplias cada vez.

Un par de librerias:
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://cssreference.io

Patrones en Responsive Desing:

Mayormente fluido // Mostly Fluid:
El patrón Mostly fluid consiste, principalmente, en una cuadrícula fluida. Por lo general, en las pantallas grandes o medianas se mantiene el mismo tamaño y simplemente se ajustan los márgenes en las más anchas.
En las pantallas más pequeñas, la cuadrícula fluida genera el reprocesamiento del contenido principal, mientras que las columnas se apilan verticalmente. Una de las mayores ventajas de este patrón es que, en general, solo se necesita un punto de interrupción entre las pantallas grandes y las pequeñas.

column drop // Colocación de columnas:
En el caso de los diseños con varias columnas de ancho completo, durante el proceso de colocación de columnas éstas únicamente se colocan de forma vertical debido a que el ancho de la ventana es demasiado reducido para el contenido.
En un momento dado, todas las columnas se apilan verticalmente. La selección de puntos de interrupción para este patrón de diseño depende del contenido y cambia para cada diseño.

Layout shifter:
El patrón Layout shifter es el más adaptable, ya que posee varios puntos de interrupción en diferentes anchos de pantalla.
La clave para este diseño es el desplazamiento del contenido, en lugar de su reprocesamiento y colocación debajo de otras columnas. Debido a las diferencias significativas entre cada punto de interrupción principal, es más complejo de mantener, y es posible que se deban realizar cambios dentro de los elementos, no solo en el diseño de contenido general.

Pequeños cambios o midificaciones // Tiny tweaks:
El patrón Tiny tweaks permite realizar pequeños cambios en el diseño, como ajustar el tamaño de la fuente, cambiar el tamaño de las imágenes o desplazar el contenido de maneras muy poco significativas.
Funciona correctamente en diseños con una sola columna, como los sitios web lineales de una sola página y los artículos con mucho texto.

Off canvas:
En lugar de apilar contenido verticalmente, el patrón Off canvas coloca contenido menos usado (tal vez menús de navegación o de apps) fuera de la pantalla y solo lo muestra cuando el tamaño de la pantalla es suficientemente grande. En las pantallas más pequeñas, el acceso al contenido es posible con solo a un clic.

Ejemplos de webs

Mostly fluid:
https://alistapart.com/
http://simplebits.com/

Colocación de columnas:
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

En este link podre encontrar diseños para inspirarme y comenzar con algunos proyectos que tengo en mente, también sabremos como usar adecuadamente el Responsive Desing: https://mediaqueri.es/
Por si acaso! ::::
En desarrollo web, las media queries son un módulo CSS3 que permite adaptar la representación del contenido a características del dispositivo como la resolución de pantalla (por ejemplo, un smartphone frente a pantallas de alta definición) o la presencia de características de accesibilidad como el braille. Se convirtió en un estándar recomendado por la W3C en junio de 2012.1? y es un principio básico de la tecnología de Diseño web adaptativo.

#3
El diseño reponsivo trata de que el contenido se acomode a cada pantalla sin que pierda la visualización o se añada un scroll horizontal.

Le mucha documentación y empiza aplicar todos los conceptos nuevos que te vayan llegando.

Medidas absolutas y relativas(estas varían según la condición), optimización, carga de la página...

Te recomiendo que uses esto, lo deja muy bonito sin importar la imagen de fondo:  text-shadow: 1px2px2px#000;

Hosting gratuito sencillo de optener con una interfaz muy intuitiva:
https://www.000webhost.com/

#4
Dentro del inspector de elementos puedes elegir la vista como si fuera un dispossitivo móvil (F12 luego CTRL + SHIFT + M) ademas de poder elegir el tamaño dependiendo de la marca de los celulares más usados, o de un tamaño por defecto que tu definas, puedes elegir el zoom que tendra esa pantalla que acabas de generar, la orientación de la pantalla y si el estado de la red de ese dipositivo, en une menu apartado que es coformado por tres puntos sobre el mismo contenedor de las demas opciones podemos mostrar unas reglas para medir el sitio, permite mostrar los mediaQuerys que tenga el sitio mostrando el tamaño exacto donde el contenido se empieza a modificar por su reponsividad, tiene la opción de tomar un screenshot completo o parcial del viewport de la página conforme también con la resolución que hayas establecido (esto resulta útil para mostrar dentro de un equipo de trabajo o a un cliente cómo va el proyecto, qué avances a tenido visualmente), por último esta una opción para restaurar a los valores por defecto de este curioso menú. Un doble clic sobre el recuedro que comprende el viewport para hacer un zoom.

Para la creación de una página web usualmente se dara un soporte minimo a un ancho de 320px que es el estadar de tamaño de pantalla que manejan la gran cantidad de dispositivos móviles, y este máximo representa hasta donde se vera bien el sitio web. Si por otro lado decidiera que mi contenido fuera responsivo en todos los momentos llegara el punto que alguno de los elemntos del documento HTML no cabra dentro del ancho.

#5
Viewport es el área visible de la patalla en el navegador, al hacer la pantalla más pequeña el viewport también lo hará.

No perder la lecturibilidad del sitio web, para empezar a forzar estos escalados dentro del sitio web existe la etiqueta de metadatos llamada viewport, para que el contenido no escale según los tamaños que le he definido, sino que escale según los tamaños del dispositivo.

<meta name="viewport" content="">
Tenemos la equiqueta metadatos, recibe el atributo name="tipo de dato que va a maniular este meta dato, en este caso <<viewport>>", ahora manipularemos el tamaño que tendra mi contenido cuando se va a ver dentro de mi dispositivo content="width" o "initial-scale" o "maximum-scale"
	"width=320" esta medida solo maneja la únidad px por lo tanto no es necesario agregarla. Esto puede resultar algo arbitrario.
	"width=device-width" en este caso el ancho sera igual al ancho de mi dispositivo
	"width=device-width, initial-scale=1" con una coma separamos el segundo parametro que vamos a ingresar initial-scale= aquí agrego valores desde 0 a 1 donde cero es el 0% y uno el 100%, los numeros negativos (-1,-2...) serian el zoom out y los positivos (1,2...) zoom in, como su nombre lo dice me esto dara la escala inicial que tendra mi página en su primera carga.

En ocaciones el cache queda guardado dentro de las herramientas de desarrollador (developers tools) por lo que es necesario en ocaciones cerrarlo y recargar la página para que aparescan los cambios.

Comentario:::::=====>
Metadatos(Meta):
Los metadatos son datos (información) sobre datos.
La etiqueta <meta> proporciona metadatos sobre el documento HTML. Los metadatos no se mostrarán en la página, pero se analizarán por máquina.
Los metaelementos se usan generalmente para especificar la descripción de la página, las palabras clave, el autor del documento, la última modificación y otros metadatos.
Los metadatos pueden ser utilizados por los navegadores (cómo mostrar contenido o recargar la página), motores de búsqueda (palabras clave) u otros servicios web.
HTML5 introdujo un método para permitir que los diseñadores web tomen el control de la ventana gráfica (el área visible del usuario de una página web), a través de la etiqueta <meta>.

Comentario:::::=====>
Info del tag para su mejor comprención
https://www.htmlcinco.com/etiqueta-meta-viewport-web-movil/
https://developer.mozilla.org/es/docs/M%C3%B3vil/Viewport_meta_tag

Comentario:::::=====>
width=device-width para que se adapte según la pantalla del dispositivo
initial-scale=1.0 para indicar el escalado según el dispositivo

#6
La propiedad de de medida em establece un tamaño para la letra según la referencia de la medida padre, si esta llega a ser una propiedad em que adopto la medida en px de un padre el valor para el siguiente em sera el de su em padre, en el caso de que en alguna etiqueta hija de uno de estos em se estableciera el tamño de la funte aprtir de allí cambiaria la medida para los sigientes elementos.

<nav> font-size: 16px;
  <ul> font-size: 2em; <!--esto equivale a 32px-->
   <li> font-size: 1em; <!-- este equivale a 632px -->
     <a href=""> hola! </a> font-size: .5em;  padding: 2em <!-- para este caso .5em equivale a 16px, mientras el em de padding es de 32px ya que se establecio en la etiqueta <<a>> el tamaño de la letra por defecto la siguente propiedad <<em>> partira desde ese tamaño establecido-->
   </li>
  </ul>
</nav>

la propieda <<rem>> toma el tamaño de la fuente del ancestro más lejano (html o body), si llegaramos a cambiar el valor cambiarián el resto de propiedades.
<!DOCTYPE html> 
<html lang="en">font-size: 32px; <!-- aquí estableceremos la medida general para todo el documento -->
<head></head>
<body> font:size: 16px;
  <ul> font:siz: 2rem; <!-- aquí la propiedad <<rem>> equivale a 64px -->
    <li> font-size: 1rem; <!-- equivale a 32px -->
      <a href=""></a> font-size: .5rem; <!-- equivale a 16px -->
    </li>
... aquí van las etiquetas de cierre jajajja

enlaces:::::::::===>
https://franciscoamk.com/unidades-de-medida-en-css/

Comentario:::::=====>
/* 1em = 16px , 2em =32px , 4em= 128px (em siempre tomara el valor de la anterior medida relativa) 
1rem =32px , 4rem= 128px , 6rem= 192px (rem siempre tomara el valor de la primera unidad relativa que comúnmente se encuentra  on el body o en el html) */

Comentario:::::=====>
Una manera de verlo, es pensar los rem como una variable, si le declaras al body por ejemplo un fontSize de 20px, a partir de ahí tu “variable” rem es igual a 20px, no importa donde lo utilices. Y si después quieres modificar el valor del rem, solo lo cambias en un solo lugar.

Comentario:::::=====>
Lo primero que debes tener en cuenta es que estas medidas son maleables, en la medida en que dependen de su fuente de origen o medida madre. Entre ellas se encuentran el porcentaje (longitud referente al tamaño de los elementos padre), los em (unidad relativa al tamaño de fuente especificada más cercano), los rem (unidad relativa al tamaño de fuente especificada en el ancestro más lejano, como html o body) y tamaños del viewport vw/vh (longitud relativa porcentual con respecto al viewport).
.
Medidas útiles en Responsive Design
.
- %: Porcentaje, se mide en referencia a la longitud de los elementos padres, por lo que abarcara simpre el porcentaje de los tamaños ya especificados o por defecto.
- em: Unidad relativa al tamaño de fuente más cercana, la fuente más cercana corresponde primero al elemento mismo, sino lo hace con el elemento padre mas cercano que tenga fuente definida y donde 1em corresponde a ese tamaño de fuente.
- rem: Unidad relativa al tamaño de fuente más lejana (html o body).
- vw/vh: Unidad relativa conceptual en relación al Viewport (área visible del navegador) y estas solo se van a modificar cuando hagamos resize (cambiar el tamaño de la ventana)
           * 100 vw: 100% del width con respecto al Viewport actual.
           * 100 vh: 100% del height con respecto al Viewport actual.

#7
Media queries permiten adpatar la representación del contenido a características del dispositivo.

@media  Un_media_type and (condicion(s)) {
}

@media screen and (max-width: 768px) {
} //Todas la pantallas con un ancho inferior o igual 768px cumplen esta condición.

@media screen and (max-width: 768px) and (min-width: 480px) {
} //Todas las pantallas con un ancho de 480px hasta 768px cumplen esta condición.

min-width = DESDE
max-width  = HASTA

Se usa regularmente el tipo SCREEN pero en ocaciones también se usa PRINT para imprimir el web-site, se imprime algo como un screen-shot por lo que el contenido suele adaptarce pues en cuanto a impresión se busca ahorrar tinta y ocultar los backgrounds que no estan permitidos dentro de los tipos de medios para impresión.

enlaces:::::::::======>
https://themeover.com/mobile-first-vs-desktop-first-responsive-design/
https://css-tricks.com/totally-forgot-print-style-sheets/ se puede ahondar más sobre el @media print, además muestra que desde el inspector de Chrome se pueden emular los media queries que tenga el proyecto!

comentario:::::======>
all | Valor por defecto, usada por todos los tipos de media
print | Utilizado para impresoras
screen | Se utiliza para pantallas de ordenador, tabletas, teléfonos inteligentes, etc.
speech | Se utiliza para lectores de pantalla que “lee” la página en voz alta
@media all and (condición) {}
@media print and (condición) {}
@media screen and (condición) {}
@media speech and (condición) {}

#8
Podemos incluirlos dentro de una hoja de estilos aparte y dentro de la etiqueta <<style>>. 
Para usar desktop first empieza por la resolución más amplia, usa los estandar de las resoluciones de pantallas que actualmente abarcan el mercado.

@media screen and (max-width: 768px) {
  body {
    border: 10px solid green;
  }
}  //Trazar una línea nos ayuda testear nustros estilos de @media

enlaces:::::::::::::::::====>
https://developer.mozilla.org/es/docs/CSS/Media_queries
https://developers.google.com/web/fundamentals/performance/http2/?hl=es

Rositorio del curso:::::
https://github.com/LeonidasEsteban/responsive-design-portafolio

#9
Para hacer que la página sea responsiva hay que empezar a quitar los valores fijos que hayamos definido, añadir la propiedad de flex-wrap: wrap; para que los elementos se apilen uno sobre otro cuando el viewport sea vea reducido.

enlaces:::::::::::::::::====>
https://flexboxfroggy.com/#es
Acá podemos apreciar a Bruce Lee hablando sobre el diseño responsivo y como debe de funcionar en distintos dispositivos para nuestros usuarios:
https://www.youtube.com/watch?v=cJMwBwFj5nQ
https://css-tricks.com/snippets/css/a-guide-to-flexbox/


comentario:::::======>
Flex-wrap es una propiedad de flexbox, bootstrap 4 ya viene con flexbox dentro de sus propiedades, con bootstrap no tienes que manejar flex-wrap como tal, si lo manejas, lo recomendable es que lo hagas con la sintaxis de bootrstrap, en lo personal prefiero usar grid layout y flexbox, queda mas rapida la pagina y es igual funcional, aunque si puedes llegar a sacrificar velocidad de implementación

Bootstrap es un framework front end. bootstrap no es de html, ni de css ni de javascript, pero si las utiliza para facilitarte las cosas de tal manera que sea mas rapido la codificación de tus interfaces, entonces tu decides si usas bootstrap o grid, ya que bootstrap maneja su propio sistema de grillas, en lo personal prefiero no implementar estos tipos de framework por performance de mis productos.

comentario:::::======>
Max-width y flex-wrap
Se deben retirar los elementos tipo “contenedor” de tamaños fijos a tamaños variables.
La propiedad flex-wrap es fundamental para este tipo de practicas adaptables, puesto que con el valor de ‘wrap’ los elementos no se comprimen en anchos pequeños, sino que al contrario pasan a una nueva línea.
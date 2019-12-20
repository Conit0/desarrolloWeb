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

enlaces::::::::::::==========>
Hosting gratuito sencillo de optener con una interfaz muy intuitiva:
https://www.000webhost.com/
Link con el portafolio (Proyecto):
https://github.com/LeonidasEsteban/responsive-design-portafolio-preview

comentario::::::::======>
Mi opinión sobre el menú hamburguesa
El usuario identificará el menú hamburguesa, pero lo usará solamente si tiene mucha intención, es más recomendable mostrar los menús siempre visibles, el menú hamburguesa lo recomiendo para contenido de tu website que tenga poca prioridad en tu sitio.
Ésto tiene varias razones de ser:
1. Los usuarios nevegan con el pulgar y la parte más lejana del dispositivo es la parte superior izquierda, donde se localiza el menú hamburguesa.
2.  por interés, normalmente al usuario no le interesa tu sitio y navega a ciegas, por lo que darle click a un botón para abrir un menú, realmente no le llama la atención (aunque sepa cómo se hace)
3. El más importante es que si quieres hacer un botón que sea clickeado es mejor poner la interacción en contexto, que salga el botón cuando más lo necesite el usuario
Si vas a utilizar un menú hamburguesa, plantéate cambiarlo por un menú de tabs (máximo 5 opciones), ésto para mostrarle las opciones y evitarle fricciones al usuario (a menos que tu intención sea que sólo usuarios súper interesados usen tu menú, que a veces es lo que se busca, por ejemplo, en facebook), aunque la mejor opción siempre será mostrar de manera contextual tus interacciones.


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


#10 y 11
Para comenzar a trabajar en el diseño responsivo por partes podemos comentar la parte del documento HTML  que no trabajaremos durante ese proceso hasta que completemos la sección a la que deseamos dar vida resposive, o bien comentarlo por secciones e ir descomentado según convenga. En algunos casos tendras uno que otro comentario por allí, así que para hacer un comentario de cierto contenido que seleciones y deseas hacerlo por medio de shortcut del editor tendras algunos incovenientes con estos comentarios que tengas.

Adicional: el back slash nos permite ecapar algún signo reservado de HTML como el signo mayor que >

Usaremos la opción: show media queries, esto nos mostrara en la parte supuerior las medidas que definimos para esos media queries en el archivo CSS, puedes jugar con el zoom de la vista y revisar si el navegador no tiene ya uno aplicado por defecto para todas las páginas.

max-width: 1000px; los elemento ocuparan un ancho máximo de 1000px, pero eso depende de sus hijos por que si sus hijos tienen menos tamaño de esos 1000px juntos quiere decir que el contenedor también tendra menos tamaño.
Si a esto le agregamos un width: 100%; podemos lograr que el contenedor se adapte a ese ancho máximo. Otra alternativa a este width: 100%; es utilizar cosas de flex, flex: 1; (flex-grow + flex-shrink) que al igual que width: 100%; tomara todo el ancho disponible, con la diferencia que en caso de colocar un padding no tendriamos el problema de que ese ancho máximo aumentara.

para un max-width: 768px (que es la resolución de un ipad) esto quiere decir que hasta esa resolución la pantalla se vera así, y para resoluciones más bajitas que el ipad restamos un píxel.

Para el selector usaremos la proiedad <<height>> con el valor <<auto>> no serviran dentro de Responsive Desing para resetear valores.

Sal del inspecionador de elementos, recarga la página y vuelve a ella para visualizas los cambios, es posible que el cache se almacene dentro del inspector y no muestre los cambios que hemos generado.

enlaces:::::::::::::::::====>
https://caniuse.com/
https://developer.mozilla.org/es/docs/Web/CSS/:nth-child

comentario:::::======>
La propiedad flex puede recibir tres parámetros:
flex-grow: Define la capacidad de crecer de un elemento. El valor por defecto es 0, si se le coloca 1 entonces va a intentar tomar todo el espacio disponible.
flex-shrink: Define la capacidad que tiene el elemento de encogerse. El valor por defecto es 1.
flex-basis: Define el tamaño predeterminado del elemento antes de ser distribuido en el espacio restante.

comentario:::::======>
nth-child es una pseudo instrucción usada para acceder a hermanos en especifico, ya que tal vez quiero darle algunas propiedades a unos elementos, más no a todos, en esa sección dije que en la clase 
Puedes leer más sobre eso en la siguiente página.
https://developer.mozilla.org/es/docs/Web/CSS/:nth-child

comentario:::::======>
me parece que hay muchos cambios y eso lleva que sean muchas lineas para los media queries(son casi el doble de los estilos utilizados en la pagina normal) ¿sera posible desde el momento de la maquetacion de la pagina, ponerlos de una menera diseñada para poder realizar mínimos cambios posibles para hacerlo adaptable?

Saludos, si, asi es, lo ideal es que los estilos generales del sitio web los coloques fuera de los media queries, siempre y cuando estos sean los mismos en las versiones responsive, yo te recomiendo que en los estilos generales coloques todo en relacion a los colores, tipo de fuentes, ancho y alto de los elementos en % y automatico casi siempre y en los media usa todo relacionado a las tamaños de letras, a la distribución del contenido, a los cambios de display etc, como dice el profesor leonidas, mientras menos estilos en los queries quiere decir que tu sitio web es mas elastico, flexible y facil de mantener.

comentario:::::======>
Ajustar header
Anotaciones:
No Es recomendable ajustar el ancho del contenedor del header variable con un width de 100%, puesto que este valor se suma aun mas cuando agregamos relleno al elemento, por lo que seria mas recomendable usar una propiedad flexbox que fusiona al flex-grow junto con flex-shrink, la cual se llama solo flex, con un valor de 1 y esto arregla el problema de ocupar todo el ancho disponible.
El ipad tiene un ancho fijo de 768 px
El valor ‘auto’ funciona mucho para el responsive design a la hora de resetear valores.
Ej: height: auto;
Es recomendable para pantallas inferiores al ipad, configurar el display del header como block.
El valor de initial es recomendable para volver a asignar el valor por defecto que tenia el elemento.

#12
Usamos porcentajes para que las dimenciones de nuestra página se ajuste mejor, en el caso de elemtos que compartan un espacion horizontal distrubuiremos el 100% entre los dos.

Es mucho mejor usar anchos automaticos y vistas en bloque para mejorar el renderizado de la página, cuando una imagen este en un viewport más chico hara rezise automticamente.

Dentro de los media queries haremos que los tamaños de fuente sean relativos, para ello usaremos los em.

Usar display con valor block para en las media queries, en el momento que la página adquiera ese tamaño obtendra ese valor.

Setear: asignar un valor prederminado.
Los margenes también deben ser variables los pondremos en em para que aspu sean relativos. Con esto conseguiremos reducir el espacio entre los textos al tener menos espacio en el viewport.
Así iremos ajustando proporcionalmente la página.

enlaces:::::::::========>
https://www.ionos.mx/digitalguide/paginas-web/diseno-web/tipografia-para-el-diseno-responsivo-con-css
https://www.imaginanet.com/blog/minmaxing-aprendiendo-vmin-y-vmax-en-css.html
https://desarrolloweb.com/articulos/funciones-recursivas-recursividad.html
De acuerdo con este artículo, el tamaño de fuente ideal es aquel que permite colocar entre 7 y 13 plabras por línea:
Usar tipografía en tiempos de diseño responsive
https://platzi.com/blog/tipografia-responsive/

comentario:::::::::======>
Puedes usar cualquier unidad medida, pero el uso de unidades de medida relativas como em o rem te facilitará el cambio de tamaño de fuente como lo desees para cada breakpoint.
El valor de la unidad em es dinámico, y equivale al valor que tenga su elemento padre.
El valor predeterminado del navegador a menudo es de 16px. Entonces, por defecto 1em = 16px y 2em = 32px.
Lo que Leonidas hizo fue establecer el font-size usando em, siguiendo el diseño de la version desktop, sin cambiar el valor predefenido de la fuente que es 16px, para que en el breakpoint de 480 solo declarará la font-size: 12px; (en este punto 1em = 12px) y así automáticamente se redujera el tamaño de las las fuentes siguiendo el diseño original.

comentario::::::::=======>
Siempre es mejor tener las cosas en diplay: block y en width: auto porque da mucho mejor rendimiento en el render del navegador. (Es mejor el ancho auto que ancho 100%… ¡Toda la vida!)
replica:::: diserto un poco de esto pues mejoran el render al colocarlos dentro de los media queries y no en la página en tamaño de escritorio donde sera necesario que el display sea flex

comentario::::::::====>
Esta es una excelente línea de codigo en CSS, mediante calc, calculamos el ancho de la fuente dependiendo del viewport. Donde 19 es el tamaño maximo, en desktop y 14 es el minimo para pantallas pequeñas. Lo mas interesantes es que sus valores varian segun su viewport, osea que toma todos los valores entre 14 y 19
font-size: calc(14px(valor minimo) + (19(valor máximo) - 14) * ((100vw - 300px) / (1600 - 300)));

comentario::::::::::::=======>
Pasos para hacer imagenes responsive:
I. En los estilos generales
a. Declarar el width de la imagen y el max-width: 100%;
b. Declarar el width del contenedor de la imagen en medidas relativas
II. En la Query
a. Declarar el width: auto en el contenedor de la imagen.
Pasos para hacer textos responsive:
I. En la Query
a. Declarar un font-size en px al elemento que contiene todos los textos, el cual servirá como guía para el em
b. Declarar los em para cada texto en la primera query
NOTA
a. Al darse la necesidad de redimensionar los tamaños del texto en otra query (o la proxima) el único valor que se deberá cambiar para que todos los textos configurados relativamente se adapten automaticamente es el font-size del contenedor previamente declarado en pixeles.

#12
Revisamos como se ve el diseño en nuestra visión general, prueba con el inspector de elementos a quitar o añadir propiedades y valores.

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

Mediante el inspector de elementos, podemos revisar si determinado elemento tiene una propiedad, para ello nos situamos sobre la pestaña <<computed (disposición)>> que esta de segundas junto a <<styles (estilos)>> allí podremos realizar la consulta y saber si el elemento cuenta con dicha propiedad.

comentario::::::::======>
Anotaciones:
Cuando hay unidades de márgenes o relleno, es recomendable hacer la sumatoria al momento de ajustar porcentajes a las unidades de ancho. Ejemplo: 48% width (para repartir entre 2 elementos), mas 1% de margin, que en total sumarian 48% + 48% + 1% + 1% +1% +1%.
Cuando agregamos una medida a un selector hijo de etiqueta, y queremos hacer una configuración posterior pero con el selector de clase, el selector de etiqueta prevalece y vale más, por lo que se debe hacer la reconfiguración con el selector de etiqueta.
Ej: .event-image valdra en este caso menos que .event img


#14
Para saber cuanto vale un em que hayas definido ve al medelo de caja donde se asigno ese valor y allí veras las medidas.

display: flex; en algunas ocaciones, sino es que en todas, arruina el modelo de caja, se ve la necesidad de resetearlo dentro de media queries.

Ver proporciones por medio del inspector del elementos y como los elementos van encajando bien dentro del tamaño de viewport que tienes disponible.

enlaces::::::::======>
emojis en HTML:
https://steemit.com/spanish/@rojassartorio/emojis-muy-pro-para-steemit
https://emojipedia.org/
https://developer.mozilla.org/es/docs/Web/CSS/flex-wrap
resúmenes de Minei Toshio:
https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso de Responsive Design
https://developer.mozilla.org/en-US/docs/Web/CSS/text-align
https://www.freecodecamp.org/news/how-to-use-the-position-property-in-css-to-align-elements-d8f49c403a26/

#15
Al invocar la propiedad position junto con alguno de sus valores desbloqueamos las propiedades: top, buttom, left, right a las que podemos asignar tanto valores positivos como negativos o diferentes unidades de medida.
con la propiedad fixed dejamos el objeto con una posición fija
los elementos se ordenan por defecto al lado derecho.

Si queremos que al llegar a cierta sección esta nos comienze ha seguir hay dos opciones: 1. con JavaScript leemos el evento del escroll y cuando lleges a esa posición asignar el valor fixed
2. mediante la propiedad position y el valor sticky.


enlaces:::::::::::::::=======>
https://codepen.io/LeonidasEsteban/pen/VGWzWK
Tienes un editor de código oneline:
https://codepen.io              https://repl.it/
https://developer.mozilla.org/es/docs/Web/CSS/position
aprendan a hacer una lista de búsqueda por Abecedario:
https://alligator.io/css/position-sticky/
 para entender un poco más de las posiciones:
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
-fixed = fijo es un elemento fijo que se queda alli y se queda allí así hagamos scroll
-sticky = es cuando pasas una sección haciendo scroll y se te pega en la parte superior o donde quisieramos

Cuando aplicamos cualquiera de estos position se desbloquean:
z-indez
top bottom left y right y sirven para mover el elemento a donde quisieramos

comentario::::::::::============>
/* POSICIONES:
static / PREDETERMINADA
relative / PUEDES MOVERLO, PERO EL ESPACIO que OCUPABA SEGUIRÁ ESTANDO
absolute / SE SALE DEL LUGAR DONDE ESTABA UBICADO, Y SE UBICA DE MANERA ABSOLUTA Y RELATIVA
CON EL ELEMENTO MÁS CERCANO QUE TENGA POSICION RELATIVA,
O POR DEFECTO EN NUESTRO ULTIMO ELEMENTO DE NUESTRO HTML, BODY O HTML
fixed / PARA FIJAR UN CONTENIDO Y QUE TE PERSIGA
sticky / PARA FIJAR UN CONTENIDO DESPUÉS DE “SUPERARLO”

  position: posicion;
CUANDO SE UTILIZA ALGUNA POSICION
QUE NO SEA LA PREDETERMINADA
SE NOS DESBLOQUEAN ESTAS PROPIEDADES:
z-index
top right bottom left */

comentario:::::::::======>
TIP: Sólo va a tener el estilo de Sticky dentro de su elemento padre.

#16
Las pociciones absolutas tienen que ser relativas a algo de lo contrario se ira hasta donde pueda ocupar espacio.

Requieres de "buen gusto" para realizar diseños que sean optimos que se vean bien, como la lecturabilidad del texto dentro de la página y que las cosas funcionen. Puedes darle un background a la fuente con rgba() o con una imagen con la cual el texto tenga más legibilidad.

enlaces::::::::::::::=====>
Dejo la compatibildad de position: sticky; en todos los navegadores https://caniuse.com/#feat=css-sticky , para quien no la conozca https://caniuse.com/es es una gran herramienta para ver la compatibilidad de nuestro codigo en los navegadores. Tb hay extensiones para ver si nuestro codigo es compatible dentro del propio editor como vscode-caniuse o para anadir prefijos como autoprefixer
https://luisdark123.github.io/MediaWeb_repository/

comentario::::::::::::======>
Overflow debes asignarla al contenedor que deseas que tenga el comportamiento de ocultar o dejar desbordar su contenido.

comentario::::::::::::::::==========>
Ejemplos de uso del z-index:
Si creamos un Navbar-menu fijo o Sticky tendremos que usar la propiedad z-index para que ningún otro elemento de nuestro sitio se sobreponga.
Al hacer responsive habrá algunos elementos, como la imagen del hero y el h1 del portafolio de leonidas, que se colocaran uno debajo del otro y si queremos arreglarlo metiendo ese texto dentro de la imagen usaremos posiciones relativas y absolutas. Aqui es cuando los elementos pueden visualizarse o no dependiendo en la capa z-index que se encuentren. Entonces asignaremos, como en la clase, un valor al z-index para que la imagen se vea en la capa 1 y el h1 se vea en la capa 2.
Z-index es una buena herramienta muy útil para transponer elementos que queremos que oculten o sobrepongan a otros.
Como buena practica te recomiendo usar z-index solo en elementos que realmente lo necesitan por que yo hize una web con puras posiciones relativas cuando no entendia lo del display block e inline block y a todo le puse z-index cuando no era necesario.
https://luisdark123.github.io/MediaWeb_repository/

#17
  <video class="html-video" src="aquí ira la ubicación del archivo o la URL" width="1640" height="360" controls></video>
Al usar un max-width con un video se usa el máximo de ancho que hayamos definido para ese elemento
con un ancho del 100% lograremos que se amplie en todo el entrorno que tiene disponible dentro de la página.

enlaces::::::::=======>
https://lenguajehtml.com/p/html/multimedia/etiquetas-html-de-video
Documentacion de audio y video:
audio https://developer.mozilla.org/es/docs/Web/HTML/Elemento/audio
video https://developer.mozilla.org/es/docs/Web/HTML/Elemento/video

comentario:::::::::::::=========>
Vas a youtube y en compartir vas al boton insertar y copias el codigo que te da. Como este:
<iframe width=“560” height=“315” src=“https://www.youtube.com/embed/cqpzCLjjgJU” frameborder=“0” allow=“accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture” allowfullscreen></iframe>

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
Desktop first: si empiezas un websit desde la mayor resolución soportada hasta la menor
¿Cúal es mejor?: Técnicamente Mobile First por posicionamiento de SEO para los clientes que navegan en nuestro sito por medio de dispositivos móviles ¿Cómo accederan los usuarios a tu contenido? por medio de google analytics sabras por donde te llegan más usuarios.

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

Tenemos la equiqueta metadatos, recibe el atributo name="tipo de dato que va a maniular este meta dato, en este caso <<viewport>>", ahora manipularemos el tamaño que tendra mi contenido cuando se va a ver dentro de mi dispositivo content="width" o "initial-scale" o "maximum-scale"
	"width=320" esta medida solo maneja la únidad px por lo tanto no es necesario agregarla. Esto puede resultar algo arbitrario.
	"width=device-width" en este caso el ancho sera igual al ancho de mi dispositivo
	"width=device-width, initial-scale=1" con una coma separamos el segundo parametro que vamos a ingresar initial-scale= aquí agrego valores desde 0 a 1 donde cero es el 0% y uno el 100%, los numeros negativos (-1,-2...) serian el zoom out y los positivos (1,2...) zoom in.

En ocaciones el cache queda guardado dentro de las herramientas de desarrollador (developers tools) por lo que es necesario en ocaciones cerrarlo y recargar la página para que aparescan los cambios.
<meta name="viewport" content="">













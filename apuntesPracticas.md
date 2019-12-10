Cerrar las etiquetas que se cierran sobre si mismas y no requieren de otra


En git es importante siempre traer los datos del repositorio remoto antes de realizar cualquier subida de cambios que hallamos realizado.

Cerrar con punto y coma las l�neas de c�digo, incluso si el nuevo estandar ES2018 no requiere de estas comillas para finalizar el c�digo.

Configuraciones del archivo .JSON dentro de VSC:::
    "editor.renderWhitespace": "all", //A�ade puntos a los espacios
    // "editor.fontSize": 15, //Tama�o que le daremos a la letra del editor
    "editor.tabSize": 2,  //Espacios que tendra la tecla TAB

Elemeto HTML div (divisi�n) // spam (a nivel de texto) y cada etiqueta tiene un peso semantico para decirle al navegador que tipo de informaci�n esta representando

Debo crear un logo que me represente

Algunas de las etiquetas de HTML representan una abreviatura en ingles:
ol order list ? los elementos que estan dentro se numeran automaticamente
ul unorder list ? elementos sin numeraci�n solo en orden de lectura del c�digo
li list item

#10 Formularios HTML

Para las etiquetas:
        <label for="email">D�jame tu email</label>  <!-- "for" como atributo dentro de la etiqueta label genera un focus a la etiqueta "input" que tiene un id igual al que esta entre las comillas del �ste atributo, con lo que estamos enlazandolos -->

        <input type="text" name="" id="email" placeholder="D�jame tu email" value="@gmail.com"> <!-- "value" atributo para atribuir un valor inicial para desterminadas etiquetas,  en este caso "input", con un placeholder que aparecera si se elimina el valor que este definido en la caja de texto del "input" -->

No solamente este enlace se logra con estas etiqueta podemos hacerlo de la siguiente manera:

              <a href="#portafolio">Portafolio</a>  <!-- por medio del "id" contenido dentro de la etiqueta "section" la enlazamos  con una parte especidfica de la p�gina-->   <section id="portafolio">

Ademas estos id que estamos usuando para enlazar en algunos casos como este se usan en espa�ol ya que la p�gina se encuantra tipada en espa�ol que no es obligatorio pero cable aclararlo.

<a href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver Pl�tica</a> Con el atributo "target" logramos que el hipervinculo se abra en una pesta�a nueva

Lo que pasa con los estilos css como su nombre lo dice se ejecutan en cascada porvocando que si un elemento cuenta con m�s de un estilo el estilo que predominara se ra el ultimo en ejecutarce y que ademas abra sobre escrito a los demas.

El atributo "!important" proporciona un nivel de importancia para determinado estilo, no se recomienda su uso ya que puede acabar con el orden de cascada que es como esta dise�ado.

un metodo para ser m�s organizado es ir colocando las clases en la hoja de estilos y tenerlos comentariados y listos para el momento de usuarlos

Los motores de busqueda cargan una hoja de estilos por defecto y es distinta para cada navegador.

Las clases es la semantica con la que yo represento un objeto del documento html para poder capturarlo por medio de la hoja de estilos y darle un estilo

Colocar buenos nombres a las clases puede resultar complejo por eso trata de que sean claras y ten imaginaci�n y creatividad


En CSS puedes valerte de los "id" para darle estilos a un objeto del documento HTML, recuerda que los "id" son �nicos, sin embargo es conveniente usar clases ya que se facilta su uso en varios elementos y permite seccionar las clases para CSS y los ides para JS dandole una estructura. Por eso se recomienda en CSS el uso de clases, agrego tambi�n que dentro de esta industri generalemente se usan nombres en ingles.


https://developer.mozilla.org/en-US/docs/Web/CSS/color_value



El estilo de escritura puede ser:
camelCase
Separaci�n por dash -
sankeCase _

El pixel es la menor unidad homogenea de color que forma parte de una imagen digital

Podemos usar el selector cuando no sepamos cual es su id lo copiaremos desde el inspector de elementos, ademas resulta m�s valioso hacerlo de esta forma pues interactuas m�s y mejor, ves el modelo de caja

Recursos para dise�adores web, espero les sea de ayuda.
https://www.youtube.com/watch?v=CEpUfqlrr6A

https://fonts.google.com/

Aqu� les dejo un link sobre que tener en cuenta cuando se elige una tipograf�a. https://design.google/library/choosing-web-fonts-beginners-guide/

En este caso, CSS permite agrupar todas las reglas individuales en una sola regla con un selector m�ltiple. Para ello, se incluyen todos los selectores separados por una coma (,) y el resultado es que la siguiente regla CSS es equivalente a las tres reglas anteriores:

h1, h2, h3 {
  color: #8A8E27;
  font-weight: normal;
  font-family: Arial, Helvetica, sans-serif;
}

Los selectores descendentes siempre est�n formados por dos o m�s selectores separados entre s� por espacios en blanco. El �ltimo selector indica el elemento sobre el que se aplican los estilos y todos los selectores anteriores indican el lugar en el que se debe encontrar ese elemento.

En el siguiente ejemplo, el selector descendente se compone de cuatro selectores:

p a span em { text-decoration: underline; }
Los estilos de la regla anterior se aplican a los elementos de tipo <em> que se encuentren dentro de elementos de tipo <span>, que a su vez se encuentren dentro de elementos de tipo <a> que se encuentren dentro de elementos de tipo <p>.

Para el espaciado entre letras se usa

p {letter-spacing: -.2px;}
Se le da esta medida de espaciado para ademas tener un nivel de dise�o que se vea la creatividad del dise�ador web
Tener detalles como esto dara un plus: alto de l�nea, espaciado de la funete, peso de la fuente, tama�o de la fuente. Resulta ser un Skill importante.
 Manejar el texto de manera habitual dentro de HTML y manipularlo dentro de CSS para no afectar el posicionamiento dentro del navegador poniendo por ejemplo mayusculas en el HTML pues cuando el navegador indexe nuestro sitio aparecera todo en may�sculas 

La etiqueta "<div>" no ofrece nung�n valor semantico pero resulta muy util para seccionar el contenido de la p�gina y poder darle estilos y manipularlo de otras formas que de no ser as� el objeto que lo tenga hara m�s compleja la manipulaci�n.
Solapar elementos::::Colocar o sobreponer una cosa sobre otra cubri�ndola parcialmente.

P�gina de referencias al momento escribir CSS: https://www.w3c.es/Divulgacion/GuiasReferencia/CSS21/

https://color.adobe.com/es/create
https://annystudio.com/software/colorpicker/
Para finalizar te dejo unos enlaces bastante didacticos para que juegues y conozcas un poco mas sobre todas las propiedades de flexbox y como funcionan.
https://flexboxfroggy.com/#es

y este otro un poco mas serio;
https://the-echoplex.net/flexyboxes/


border: Establece el tama�o,tipo y estilo (10px solid red)
border-color: Establece el color del borde en todos los lados (si esta propiedad no se utiliza, utilizar� el color del texto)
border-width: Establece el grosor del borde
border-style: Establece el estilo del borde (se utiliza frecuentemente solid)

border-radius: Redondea (por pixeles) las esquinas de los bordes

border-radius:10px 10px 30px 10px;
As� se puede poner el bordeado de cada una de las esquinas.
Primer valor: esquina superior izquierda.
Segundo valor: esquina superior derecha.
Tercer valor: esquina inferior derecha.
Cuarto valor: esquina inferior izquierda.

Links

Hola a todos. Queria compartir este link que me parecio interesante y podria ser de guia cuando se nos olvide los conceptos. Esta en ingles aunque el traductor de Google no lo traduce tan mal ??
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

Esta herramienta web nos ayuda a experimentar m�s con los bordes cssmatic.com/es ?

Aqu� hay una gu�a completa de los bordes con sus propiedades y shorhand m�s usados:
https://lenguajecss.com/p/css/propiedades/bordes

Si alguien quiere generar un border de manera autom�tica puede hacerlo en
http://angrytools.com/css-generator/border/

Hacer triangulos dentro de CSS???


Div y span:
son contenedores.

Los contenerdores son elementos utilizados en el HTML para agrupar secciones, dependiendo de que tipo de contenedor utilices, el contenido tendra un valor semantico diferente.

El span por ejemplo, es un contenedor de texto, se utiliza para agrupar ciertas partes del mismo y darle propiedades css.

El div es un contenedor de igual manera, pero que no tiene valor semantico alguno, dentro no debe ir nada en especifico, puede agrupar cualquier tipo de elemento.

Id y class:
son selectores css.

Son utilizados para darle a los elementos del HTML un identificador con el cual hacer referencia desde el codigo css.
Esa es la funci�n de las dos, pero existe una diferencia.
El id es utilizado para identificar unicamente a un elemento.
El class es un identificador que pueden tener multiples elementos, y esos multiples elementos adoptar dichas caracteristicas que declares en el css.


Suponiendo que tienes un cuadro y dentro de ese cuadro tienes texto:
    El espacio que existe entre en cuadro y el texto es el padding.
    El espacio que existe entre el cuadro y otro objeto fuera de �l es margin.

1- El margin colapsing: No es la suma de margenes de dos elementos diferentes, Es la integraci�n del elemento con mayor margen a un elemento con menor margen ejemplo: si un elemento tiene un margen de 50 pixels. y otro elemento tiene un margen de 20 pixels. no se suman sino que el de 50 pixels. integra al de 20 pixels por lo tanto este amplia su margen a 50 y as� ambos comparten el mismo margen de 50 pixels .

2.- margin : el orden de sus par�metros es (TOP->RIGHT->BOTTOM->LEFT)

En mi opini�n en la hoja de estilos antes de empezar, siempre hago un css reset, para evitar tener problemas con los bordes, letras, etc. Aca les dejo el link: https://meyerweb.com/eric/tools/css/reset/


�Cuando usar padding o marging?
Diferencias de las propiedades padding y margin:
Margin es el margen que hay desde un elemento hasta los que tenga al lado.
Padding es el espacio que hay en un contenedor entre el contenido y los bordes del contenedor.

Padding utiliza los mismos valores que margin y tambi�n est�n ordenados de acuerdo a la posici�n del sentido de las agujas del reloj

Al momento de definir el margen o el relleno se debe tener en cuenta el borde y el fondo con ello podremos encontrar la propoci�n que aplicaremos al proyecto.

box-sizing: border-box; nos permite resetear el modelo de caja
Las partes que componen cada caja y su orden de visualizaci�n desde el punto de vista del usuario son las siguientes:

Contenido (content): se trata del contenido HTML del elemento (las palabras de un p�rrafo, una imagen, el texto de una lista de elementos, etc.)
Relleno (padding): espacio libre opcional existente entre el contenido y el borde.
Borde (border): l�nea que encierra completamente el contenido y su relleno.
Imagen de fondo (background image): imagen que se muestra por detr�s del contenido y el espacio de relleno.
Color de fondo (background color): color que se muestra por detr�s del contenido y el espacio de relleno.
Margen (margin): separaci�n opcional existente entre la caja y el resto de cajas adyacentes.


Se pueden alterar los modelos de caja de varias formas, entre esas:
por un display especial.
por una propiedad especial que nos ayude a hacer que este modelo de caja funcione de una manera m�s f�cil de leer.
Si uno quiere hacer que el ancho no sea afectado por el borde o el padding (es decir, que estos dos ultimos no sumen al ancho general) existe una propiedad llamada box sizing.

box-sizing: border-box;
Con border-box se hace que la caja siempre ocupe el tama�o hasta su borde del ancho (no importa el grosor del borde o el padding, nunca llegar� a medir m�s de lo que se le defini� en ancho y alto). Es decir, al a�adir padding o hacer crecer el borde, estos crecer�n hacia adentro, respetando el ancho como un limite que no se puede extender.

Display nos indica como debe ser mostrado un elemento en HTML::::
Display block: Ocupa todo el ancho posible en el eje de x
Display inline: Ocupa todo el ancho de su contenido y permite a otros elementos posicionarse a su costado
Display inline-block: Se le puede asignar un ancho y un alto, y a diferencia de display block, permite que otros elementos se posicionen a su costado.


Flexbox
Link en ingles para practicar: http://www.flexboxdefense.com/
https://filisantillan.com/el-gran-poder-de-css3-flexbox/
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

Tener en cuenta donde se ubicara la propiedad ya que unas son para hijos y otras para padres.
como es el caso de: 
flex-wrap: wrap; Para padres 
flex-shrink: 0; para hijos

Guia de referencia ::::::::: https://www.w3c.es/Divulgacion/GuiasReferencia/CSS21/
Guia en ingles para saber como escojer una fuente :::::::: https://design.google/library/choosing-web-fonts-beginners-guide/

CSS Grid Layuot :::: https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout
Usando las cajas flexibles CSS ::::::::::::::::::: https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout/Usando_las_cajas_flexibles_CSS

Secion en vivo de la beca platziLive :::::::::  https://developer.mozilla.org/es/docs/Web/API/Fetch_API
*Dibujar un problema que require una l�gica compleja, esto para sintetixar mejor las ideas que escribiremos en el c�digo y no desviarnos del problema que deseamos resolver.


Alineando elementos de forma vertical
Por medio de "justify-content" o "align-self" (alineate a ti mismo, seria para etiquetas hij@ que deseamos manipular de otra forma) no se suele usar amenudo pero es una forma f�cil de manupular estos elementos.

25 de Noviembre del 2019

Los plugins facilitaran tu vida al momento de desarrollar c�digo

La propiedad de CSS "display: flex" solo se hereda a los hijos directos si un de esos hijos tiene un hijo ya no tendra la propiedad de su abuelo por as� decirlo, por lo tanto hay que definirla propiedad (en esta caso al "nieto") 

En esta clase vemos que adem�s de las propiedades relacionadas con display:flex, en lo que se refiere a la alineaci�n de elementos internos, existen tambi�n propiedades equivalentes que nos permite alinear textos dentro de un contenedor, estas propiedades son: text-align y vertical-align.

https://www.saberespractico.com/web/emoticonos-en-html/
Web con codigos para insertar emoticones dentro de nuestro documento HTML

*******Algunos shortcuts
*******win + ctrl + d = en win 10 crea un nuevo escritorio
*******Win + Shift + S = Para hacer screensho
*******Un consejo en Office si desean guardar un archivo rapido "Guaradar *******como" utilicen F12
*******En Mozilla con las teclas shift MAS ctrl:::--->::--->:::
::-->:::-->::-->:::MAS suprimir muestra una ventana para borrar el historial3
::-->:::-->::-->:::MAS inicio seleciona desde donde este el curso, especificamente la l�nea que escribe el texto, hacia arriba.
::-->:::-->::-->:::MAS fin seleciona desde donde este el curso hacia abajo
::-->:::-->::-->:::MAS ReP�g permite mover la pesta�a del navegador hacia la izquierda.
::-->:::-->::-->:::MAS AvP�g permite mover la pesta�a del navegador hacia la derecha
::-->:::-->::-->:::MAS m muestra el modo m�vil 
::-->:::-->::-->:::MAS c mustra el inspector de elemtos presto para selecionar
::-->:::-->::-->:::MAS a --- t muesrtra el administrador de complemtos de mozilla
::-->:::-->::-->:::MAS s activa el capturador de pantallas (screenshot)
::-->:::-->::-->:::MAS j --- i inspector de elementos en una ventana aparte
::-->:::-->::-->:::MAS k inspector de elementos sobre la consosla directamente
::-->:::-->::-->:::MAS r recarga la p�gina junto con el cache
::-->:::-->::-->:::MAS e inspector de elemetos sobre la red o network
::-->:::-->::-->:::MAS w --- q cierra toda la ventana
::-->:::-->::-->:::MAS 3 --- 9 el primero va hacia la derecha mientras el segundo va en sentido izquierdo PERO solo en el teclado numerico que esta aparte del las letras, el que se activa con el BloqNum.
::-->:::-->::-->:::MAS 4  --- 6 selecciona texto desde el sitio de la p�gina donde hayas hecho click el primero, recordemos que el html es un archivo de texto.
::-->:::-->::-->:::MAS 1 --- 7  [2 --- 8 (hace lo mismo)]despalzar el scroll de la p�gina, el primero (1) al final y el segundo (7) hacia arriba y hasta aqu� van los que son con el teclado BloqNum.
::-->:::-->::-->:::MAS
::-->:::-->::-->:::MAS
*******
*******
*******
*******
*******
*******
*******

Buena practica es ponerle un ancho(width) y alto(heigth) a los elemtos img dentro del documento HTML 

Algo que he hecho y me ha funcionado es retarme, por ejemplo, luego de terminar el proyecto, hacer 5 dise�os diferentes uno por d�a, es facil encontrar landing en internet y la idea es ir aplicando todos y cada uno de los conceptos, seguramente el primero ser� dificil pero conforme pase el tiempo ser� m�s facil.
Otra cosa que puedes hacer tambi�n es lo que se llama el CSS Zen: busca un sitio que valga la pena copiar, le quitas el CSS y copias su texto, y luego lo modelas con tus propios estilos, primero buscando hacerlo similar solo con CSS, y luego con tus propias ideas. Se descubre un mont�n de cosas nuevas.

LANDING PAGE
https://www.youtube.com/watch?v=WZqJ1R4-8aA
Enfocar al cliente en la informaci�n que le interesa y por la cual llego a esta p�gina.

con display: flex; puedo poner un elemento junto a otro como por ejemplo dos <div>

Les recomiendo esta p�gina para hacer sus imagenes dummies y puedan armar sus plantillas para sus proyectos posteriores.
https://dummyimage.com/

Esta es una combinaci�n muy util, en el elemento padre:
    display: flex;
    align-items: center;
    justify-content: space-between;

La letra por defecto en los navegadores dentro de etiquetas con contenido de texto el tama�o por defecto que generalmente tienen es de 16px

ES MUY IMORTANTE QUE TODO QUEDE BIEN ESCRITO PARA QUE NO LA LIES MAS ADELANTE CUANDO EL CODIGO SE HAGA MAS EXTE NSO

Para centrar algo horizontalmente en navegadores modernos, usa display: flex; justify-content: center; 
Si tengo un elemento con display flex y flex-direction column �Con qu� propiedad centro su contenido verticalmente?
El primero de estos m�todos es �vertical-align�, que no siempre funcionar�, pero nos ayudar� a comprender mejor el centrado vertical en general.

Con el inspecionador de elementos puedo ir verificando las alturas de todos los elemetos de mi archivo HTML y saber donde se encuentra el posible error que hace que un estilo CSS no se vea como nosotros queremos, recientemente me paso con un div y su contenido se desbordaba resulta que le habia asignado un heigth:100px; a una clase que se encontraba dentro de esta y que estaba probocando dicho desbordamiento.

La propiedad de CSS overflow especifica qu� hacer cuando los elementos se desbordan de un contenedor con tama�o fijo como podr�a ser un div.
overflow: visible # por default son visibles los elementos que sobrepasan el tama�o del contenedor
overflow: hidden # se cortan donde termina el contenedor
overflow: scroll # agrega barras de scroll para poder desplazarse
overflow: auto # lo deja a decisi�n dell navegador

esto me ayudo a entender mejor el position http://es.learnlayout.com/position.html

Ctrl + Mayus + K = Eliminar linea de c�digo
 Que no te confundas con las propiedades como width y heigth ya me paso jajajaja

Para poner varias clases dentro de un elemento solo hace falta separarlas con un espacio dentro del mismo atributo class=""

El formato SVG (Scalable Vectors Grafics) es aquel el cual no importa cuanto le modifique su tama�o, este no va perder su resoluci�n. Siendo esto porque usa vectores en vez de pixeles para dibujar en pantalla.


Recuerda que display: flex; solo afecta a los hijos directos, por lo que si incluimos un div dentro de otra etiqueta habra que hacer que se herede esta propiedad. La ubucaci�n de los elementos es muy importante.

Me di cuenta que el borde solido de color rojo se usa para poder ver todo el espacio que comprende dicho elemento y poder guiarnos para acomodarlo de uno u otra forma, lo que llaman depurar estilos.
    
.elNombredelaClase + tab hace que se cree un div con el nombre de la clase que se a espesificado.


Hay m�ltiples opciones para tener una web estatica, ac� te dejo tres clases en las que te ense�an a hacer deploys est�ticos de tus p�ginas en diferentes plataformas:
*****now.sh
*****github
*****surge.sh
















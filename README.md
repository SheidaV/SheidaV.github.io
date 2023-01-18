Segunda parte

Realizaréis el prototipo de un sitio web que recoge información sobre la presencia de la mujer en el mundo de la ciencia. La información ha sido elaborada a partir de la biblioguía Mujeres, ciencia y tecnología de la biblioteca de la UOC.

Este prototipo mostrará cuáles serán los contenidos principales del sitio, el sistema de navegación, así como el diseño que tendrá el sitio web una vez finalizado.

El prototipo constará de cuatro páginas: la página de inicio (index.html), la página con la enumeración de 10 mujeres referentes del mundo de la ciencia y la tecnología (referentes.html), la página con un artículo sobre el Día Internacional de las Mujeres y las Niñas en Ciencia (11-de-febrero.html) y la página con una recopilación de iniciatives relacionadas con el tema que nos ocupa (iniciativas.html).

El material necesario para realizar la PEC lo encontraréis en el archivo MaterialesPEC3.zip. Se han incluido las imágenes (carpeta img), los textos del contenido e instrucciones de maquetación (TextosCondicionesMaquetacion.rtf / TextosCondicionesMaquetacion.pdf) y los mockups (carpeta mockups).

Los mockups indican cómo deben disponerse los elementos de cada página tal como tienen que ser visualizados en dispositivos pequeños (01-index-telefono.png, 02-referentes-telefono.png, 03-11-de-febrero-telefono.png y 04-iniciativas-telefono.png); en dispositivos medianos (01-index-tablet.png, 02-referentes-tablet.png, 03-11-de-febrero-tablet.png y 04-iniciativas-tablet.png) y en dispositivos grandes (01-index-desktop.png, 02-referentes-desktop.png, 03-11-de-febrero-desktop.png y 04-iniciativas-desktop.png). Estas imágenes muestran el aspecto visual y estético que debéis reproducir con la máxima fidelidad posible en vuestro prototipo; en el archivo TextosCondicionesMaquetacion.rtf / TextosCondicionesMaquetacion.pdf encontraréis instrucciones relacionadas con los tipos de fuente, colores y aspecto de los enlaces que debéis también tener muy en cuenta.

Consideraciones generales

Debe maquetarse en HTML5, respetando los estándares web y aplicando las mejores técnicas aprendidas a lo largo del semestre.

Todas las páginas deben poder ser correctamente visualizadas en distintos dispositivos (teléfonos, tabletas y ordenadores de escritorio), por lo que deberán tener un diseño responsive. Os aconsejamos que en su construcción apliquéis el criterio mobile first, aunque podéis utilizar la estrategia que consideréis más adecuada.

Para la maquetación de las páginas podéis utilizar cualquiera de los métodos que se explican en la unidad 5 (Flexbox o Grid); aplicad el que consideréis adecuado a cada caso (no se aceptará el uso de tablas, que están completamente desaconsejadas en la creación de este tipo de estructuras).

El sitio tiene que tener una estructura lógica y organizada de archivos y carpetas.

Cada página debe tener un título (title) que debe ser adecuado y descriptivo de su contenido.

Tanto el HTML como vuestro CSS (en un único archivo para todo el sitio) deben presentar el código visualmente ordenado y deben estar libres de errores de validación.

Descripción del contenido

Elementos comunes de las cuatro páginas:

Anchura de los contenedores: como podéis ver en los mockups, en los dispositivos más pequeños, los contenidos ocupan el 100% de la anchura de la ventana del dispositivo (con una separación razonable a izquierda y derecha para evitar que los contenidos toquen las paredes laterales). En los dispositivos más grandes, los contenidos no ocupan el 100% de la ventana del navegador y se muestran horizontalmente centrados. Hay, sin embargo, una excepción: el pie de todas las páginas ocupa el 100% de la ventana (sus contenidos, no).
Cabecera
Logotipo y texto con enlace a "index.html".
Menú de navegación principal compuesto por una lista de tres ítems que debéis presentar en este orden: "Referentes científicas" (con enlace a "referentes.html"), "11 de febrero" (con enlace a "11-de-febrero.html") e "Iniciativas" (con enlace a "iniciativas.html").
En dispositivos pequeños y medianos los elementos de esta cabecera se mostrarán centrados, con el menú de navegación en una lista con sus ítems uno debajo de otro; en dispositivos más grandes los elementos se alinearán en una única línea con el logotipo situado a la izquierda y el menú en una lista con sus ítems dispuestos en horizontal y situada a la derecha.
No debéis olvidar tratar convenientemente el estado :hover de los enlaces del menú.
Pie de página
Los contenidos del pie de página se mostrarán en cuatro bloques.
En un primer bloque, el logotipo y el correo electrónico de contacto.
En un segundo bloque, el formulario de suscripción al boletín de noticias.
En el tercer bloque, un menú de navegación con tres ítems (con enlaces vacíos): "Aviso legal", "Política de privacidad" y "Política de cookies".
En un cuarto bloque, los textos relacionados con la autoría de la PEC y créditos a los autores de algunos de los contenidos.
En todos los dispositivos, los textos se mostrarán centrados. En dispositivos pequeños, el menú de legales se dispondrá en una lista con los ítems uno debajo del otro; en el resto de dispositivos el uno al lado del otro.
En el archivo TextosCondicionesMaquetacion.rtf encontraréis detallados los textos a incluir en cada uno de los apartados del pie.
No debéis olvidar tratar convenientemente el estado :hover de los enlaces del pie.
A continuación os hacemos las indicaciones para la construcción del resto de contenidos de cada una de las páginas del prototipo. Los textos para copiar y pegar los localizaréis en el archivo TextosCondicionesMaquetacion.rtf.

Página de entrada al sitio web (index.html):
Esta es la página inicial del sitio, tenemos que poder acceder siempre desde el logotipo y texto de la cabecera de cada página.
Consta de dos secciones. En la primera, un titular y un texto introductorio con una imagen decorativa a su izquierda. En la segunda, por debajo del correspondiente titular, una relación de cuatro científicas referentes. Sobre cada científica debe incluirse una imagen, la disciplina, el nombre y las fechas de nacimiento y muerte. Las imágenes y el texto deben ser clicables i deben llevar a la página referentes.html, situando al navegante en la posición donde aparezca la científica. El enlace por debajo del titular debe llevar a la página referentes.html.
Página "Referentes científicas" (referentes.html):
A esta página debemos poder acceder desde el menú de navegación principal de todas las páginas; desde el enlace por debajo del titular de la segunda sección de la página de inicio y desde cada una de las científicas enumeradas en esta página de inicio.
La página consta de un menú de navegación secundario compuesto por los nombres de las diversas científicas. Los ítems de este menú tienen que ser enlaces que lleven a la posición donde se muestra la información de cada una de las científicas. El apartado descriptivo de cada una de ellas consta de la siguiente información: número de orden, datos básicos de identificación (nombre, disciplina, fechas), imagen, breve información y enlace a un recurso externo que desarrolla la información.
En dispositivos pequeños y medianos, el menú de navegación secundario debe mostrar sus ítems en línea y centrados en pantalla. En dispositivos grandes, uno por debajo del otro y en una columna situada a la izquierda de la página.
En los dispositivos más grandes, los contenidos se repartirán el espacio en dos columnas: a la izquierda, el menú y a la derecha, la información de cada una de las científicas.
Página "11 de febrero" (11-de-febrero.html):
A esta página tenemos que poder acceder siempre desde el ítem "11 de febrero" del menú principal de cada una de las páginas.
Esta página consta de un artículo que incluye, entre otras cuestiones, una cita de bloque y un video de YouTube.
Los mockups correspondientes muestran como cada uno de los elementos utiliza el espacio; prestad especial atención a la representación responsiva del vídeo de YouTube.
Página "Iniciativas" (iniciativas.html):
A esta página tenemos que poder acceder siempre desde el ítem "Iniciativas" del menú principal de cada una de las páginas.
Esta página consta de una enumeración de iniciativas. Por cada una se muestra el nombre, una breve descripción y enlace a la página del recurso.
Debe construirse mediante una lista de descripción convenientemente modificada con CSS
Otras actividades a realizar

Debéis elaborar un informe que documente las características del sitio web. El objetivo del informe es conseguir que cualquiera que debiera continuar construyendo el sitio tuviera claro el procedimiento a seguir (organización de archivos, arquitectura de la información, diseño gráfico…). Este informe, como mínimo, incluirá una explicación de los elementos HTML y de las declaraciones CSS que se han utilizado, explicando lo que es común a todas las páginas y también las estructuras particulares de cada una de ellas. Este informe deberá entregarse junto con las preguntas teóricas de la primera parte, en un documento con cualquiera de las extensiones siguientes: .doc, .odt o .pdf.

Además de entregar la solución en el espacio de Entrega y Registro de Evaluación Continua, tendrá que hacerse su publicación para que sea accesible desde Internet.

Esta publicación puede hacerse de una de las siguientes formas:

alojar el sitio web en el servicio GitHub Pages, o
alojarlo dentro del Campus mediante la aplicación WebFTP que encontraréis en el aula.
Las instrucciones para poder realizar la publicación las encontráis en el archivo "InstruccionesPublicacion.zip"

En el informe debéis indicar qué servicio de publicación habéis utilizado e indicar el URL que conduce a la primera página ("index.html") del prototipo que habéis desarrollado.
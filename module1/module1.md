# Curso   Semana 1   Tema 1. Introducción a la visión por computador   Introducción semana 1

Introducción semana 1
 
¡Hola!
Bienvenidos a la 1ª semana del curso "Introducción a la visión por computador: desarrollo de aplicaciones con OpenCV".
Durante estos siete días vamos a explicar, en mayor detalle, lo que es esta tecnología
y los principales campos en los que se usa.
Vamos a ver los dos elementos hardware más importantes:
las ópticas y las cámaras.
Con las primeras, conseguimos que los rayos reflejados por los objetos,
converjan sobre el elemento sensor de las cámaras.
Además de su uso, debemos conocer sus principales parámetros y cómo podemos modelarlas.
Respecto a las cámaras,
éstas pueden ser de distinto tipo y, dependiendo de la aplicación concreta que queramos desarrollar,
tendremos que elegir entre uno u otros.
Por último, se verán los programas informáticos que se van a utilizar a lo largo de todo el curso:
la biblioteca OpenCV
y el entorno de programación Microsoft Visual Studio
y cómo se integran.
El alumno va a realizar la escritura del primer programa,
cargar una imagen de disco para verla por pantalla,
que será el programa base sobre el que vamos a desarrollar el resto de aplicaciones.
En este módulo hay material audiovisual, material complementario y una autoevaluación.
Esperamos que os abra el apetito para la 2ª semana,
donde desarrollaremos más programas y aplicaciones.

# Curso   Semana 1   Tema 1. Introducción a la visión por computador   ¿Qué es la visión por computador?

¿Qué es la visión por computador?
 
En este primer tema vamos a establecer el marco del curso:
qué es la visión por computador
y los principales problemas a los que hay que enfrentarse
cuando hay que diseñar una aplicación que utiliza esta tecnología.
Para ello, en este primer vídeo, se va a comenzar estableciendo unas definiciones,
siendo la más importante de ellas, la visión por computador.
En segundo lugar veremos por qué esa tecnología es importante
y qué causas han propiciado su enorme desarrollo en los últimos cinco/diez años.
En el siguiente apartado,
es una descripción de las principales tecnologías que han propiciado la aparición de la visión por computador.
Eso sí,
no podemos dejar de decir que las aplicaciones de análisis de imágenes no son fáciles de llevar a cabo
ya que tendremos que solventar una serie de problemas,
que es lo que explicaremos en el segundo vídeo.
Pasamos, por tanto, a ver diversos conceptos y definiciones.
El primer concepto es qué entendemos por sentidos.
Los sentidos son los medios por los que podemos interactuar con el entorno que nos rodea.
Nos permite obtener información del mundo
y decidir en función de ella las acciones que debemos tomar para movernos, comunicarnos o interaccionar
con los objetos.
Sin los sentidos estaríamos inmóviles y permaneceríamos ignorantes.
Entre todos los sentidos, el de la vista es el más importante y complejo de ellos.
La visión nos da mucha mayor información que los demás,
pero es importante recalcar que es el sentido más complejo que tenemos y del que se
desconoce en gran medida su funcionamiento.
Para resaltar su papel vital,
diremos algunos estudios cifran que el 75% de la información sensorial procesada
por el cerebro está dedicada a la vista,
mientras que el 25% restante se centra en los otros cuatro sentidos.
Gracias a la visión tenemos información de los objetos que existen en nuestro entorno:
sabemos donde están,
si están moviendo o no y qué trayectorias siguen.
Podemos determinar el camino libre de obstáculos,
reconocemos los objetos que nos rodean, de entre ellos, posibles peligros y un largo etcétera.
Con todo lo visto antes podemos definir la visión por computador
como el análisis de imágenes a través de computadores
para obtener una descripción
de los objetos que son captados por la cámara.
De esta definición es importante recalcar que la entrada a nuestro sistema es una imagen y, sobre todo,
que la salida es información.
Esto a diferencia de visión por computador de otras tecnologías similares como el procesamiento de imágenes digitales
y la generación de gráficos por computador.
¿Qué ventajas o avances presenta la visión por computador?
Son bastante numerosas.
A nadie se le oculta que dotar, en alguna medida, del sentido de la vista a los
robots que se utilizan en la industria
dispararía el número de aplicaciones.
Otro ejemplo en el mundo industrial es el control visual de calidad
ya que las cámaras nos permiten un control de calidad del 100% de lo que fabriquemos.
De hecho, estas dos aplicaciones son las que históricamente han desarrollado los algoritmos de análisis de imágenes y las cámaras digitales.
Además nos encontramos con que la llamada sociedad de la imagen lo es cada vez más.
Así tenemos cámaras integradas en cualquier dispositivo electrónico.
Hemos pasado de las cámaras en los ordenadores a los teléfonos, las tabletas, los televisores,
y ya se nos anuncia que las vamos a tener disponibles en las gafas.
Ese aumento de cámaras ha propiciado que nos encontremos con imágenes en todas partes,
con inmensas bases de datos de ellas,
distribuidas de forma desorganizada por internet,
almacenadas en los ordenadores personales, etcétera.
Este hecho
ha propiciado aplicaciones nuevas.
También los sistemas de visión por computador son muy útiles a la hora de realizar gráficos por computador,
a los que cada vez se les exige que sean más realistas.
Por todo ello el rango de aplicaciones de la visión por computador es cada vez más amplio.
Aquí queremos enseñar un pequeño muestrario.
Vemos que existen desde aplicaciones en el campo militar,
el control de calidad o la robótica industrial
que constituyen el núcleo central y tradicional,
a las aplicaciones en el mundo de la seguridad,
el control de tráfico, la identificación de personas que son campos de aplicación emergentes, y cada vez más importantes.
¿Qué tecnologías han propiciado que la visión porque computador haya tenido un desarrollo tan grande los últimos años?
Por un lado el desarrollo de hardware.
A nadie se le oculta que los microprocesadores cada vez son más potentes y de dimensiones más
reducidas,
con lo cual, por un lado son capaces de procesar muchísima más información en menos tiempo,
y por otro,
puede ser incorporados en prácticamente cualquier dispositivo.
Esto es lo que ha llevado a que las cámaras sean introducidas en cualquier equipo electrónico
y que en ese mismo dispositivo se puedan implementar algoritmos de análisis de imágenes.
De nada serviría un gran hardware si no tuviésemos herramientas software para implementar nuestras ideas.
Si además se tuviese siempre que empezar a partir de cero
el diseño de aplicaciones informáticas estaría reducido a unas pocas empresas.
Sin embargo,
cada vez hay más herramientas informáticas de dominio público
que permiten que el programador se centre en la implementación de la idea a partir de unos bloques básicos ya construidos.
Las bibliotecas de funciones son uno de esos bloques
y en el campo de la visión por computador destaca la biblioteca de funciones OpenCV,
que utilizaremos durante este curso.
Además de un buen hardware y herramientas informáticas necesitamos buenas ideas.
La inteligencia artificial también ha dado durante estos últimos años
numerosas algoritmos
que han permitido al análisis de imágenes salir del mundo de la industria a ambientes menos controlados.
Un caso paradigmático son los programas de fotografía
donde ahora en casi todos ellos se nos recuadra la cara de las personas que están presentes.
Hasta hace pocos años
establecer qué características definían una cara en una imagen
era una tarea no resuelta.
Ahora,
gracias a los algoritmos de inteligencia artificial,
en concreto los de aprendizaje de máquina,
esta aplicación está al alcance de todos.
Con esto damos por concluido este vídeo
donde hemos visto qué esa visión por computador
y por qué es una de las tecnologías que se están desarrollando con mayor rapidez en la actualidad.
En el próximo vídeo
explicaremos las principales dificultades a las que nos enfrentamos
cuando queremos que los ordenadores analicen de forma automática una imagen.

# Curso   Semana 1   Tema 1. Introducción a la visión por computador   ¿Es difícil analizar una imagen?

¿Es difícil analizar una imagen?
 
En el vídeo anterior explicamos qué es la visión por computador.
En éste
nos vamos a centrar en los principales problemas a los que hay que enfrentarse
cuando hay que diseñar una aplicación que utiliza esta tecnología.
Una vez vista la utilidad de la visión por computador cabe preguntarnos
¿cómo es de fácil desarrollar algoritmos que se basen en el análisis de imágenes?
La respuesta es que es más complicado de lo que parece.
Para las personas el ver resulta una operación fácil, no costosa,
pero eso no quiere decir que no sea compleja
como ya hemos visto en la transparencia anterior.
La visión es un proceso que se realiza en el subconsciente
con lo cual no sabemos los pasos que realizamos para llevarla a cabo.
Por tanto
tampoco sabemos qué pasos deben de dar los computadores a la hora de analizar una imagen.
En el caso de los ordenadores
tenemos una complicación adicional,
y es que realmente los computadores no captan imágenes como las que nosotros vemos,
sino que para ellos constituye una matriz de números
y nuestras aplicaciones
tendrán que traducir esos números en objetos.
En el caso de aplicaciones industriales, donde el ambiente está controlado,
esta tarea es más fácil que en el caso de aplicaciones en exteriores o en nuestra propia casa,
donde existen muchas variables que no podemos determinar o fijar
por lo que la solución de las tareas se va a complicar bastante.
¿A qué nos vamos a enfrentar? o ¿qué problemas tenemos que solventar?
Son varios.
Por un lado los objetos van a presentar un conjunto de apariencias muy distintas en nuestra imagen
ya que dependerá, por ejemplo, del punto de vista
que lo hará aparecer rotados,
trasladados a una zona de la imagen o a otra,
o más o menos grandes.
Y a pesar de esos cambios nuestro algoritmo tiene que saber que se trata del
mismo tipo de objeto.
Además,
podemos tener el caso de que el objeto que estamos buscando no tenga una forma rígida,
por ejemplo un animal,
por lo que presenta cambios debidos al movimiento.
Otro factor muy importante es la iluminación,
que puede no ser constante,
y que no sólo va a producir que las imágenes se vean más claras u oscuras,
sino que además
nos producirán sombras, modificará el contraste entre diversas zonas, etcétera.
En una aplicación normal
el objeto que estamos buscando no va a ser el único que existe en la imagen.
La presencia de otros objetos puede producir oclusiones
con lo cual lo que estamos buscando no lo veremos globalmente
sino sólo alguna de sus partes.
Además se nos complica la búsqueda
ya que tenemos muchos posibles casos donde encontrarlo.
En algunas aplicaciones es difícil definir de forma explícita qué es lo que define a los objetos.
Pensemos un sistema de seguridad
que quiere detectar personas donde por la postura, la ropa, la iluminación, etcétera,
no es fácil definir de forma concreta
qué características queremos buscar en la imagen
para determinar que una persona está presente o no.
O el ejemplo tradicional
de qué es lo que define una silla
ya que pueden tener formas, colores,
o estar hecha de materiales diversos.
A todo ello hay que añadir que, normalmente, existe una restricción temporal muy exigente.
No podemos dar resultados dos minutos o un segundo después de haber capturado la imagen,
sino que tenemos unas pocas decenas de milisegundos.
Y en ese poco tiempo
tenemos que examinar decenas de miles de posibilidades en cada imagen,
con lo cual, si no solo algoritmo funciona al 99,9% de acierto
tendremos varias decenas de errores por cada imagen.
Estos errores serán los falsos positivos, es decir, cuando afirmemos que los objetos buscados están presentes en la imagen
y no sea así.
Y en caso contrario, los falsos negativos,
que es cuando los perdemos.
A pesar de lo anterior, me gustaría decir que son precisamente estas dificultades
las que hacen que implementar un algoritmo de visión por computador sea una tarea apasionante
y ese es el motivo por el cual hemos querido hacer este curso,
para que cada vez más personas se animen a realizar sus propias aplicaciones
de análisis de imágenes.
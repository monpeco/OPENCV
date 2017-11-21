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

# Curso   Semana 1   Tema 2. Óptica   Óptica: definición y parámetros principales

Óptica: definición y parámetros principales
 
Hola,
en este primer módulo del tema 2 vamos a introducir uno de los elementos principales en un sistema de visión:
la óptica.
Para ello, abordaremos distintos aspectos, cuál es su misión en un sistema de percepción,
cuáles son los parámetros fundamentales que la definen y, finalmente, los diferentes tipos de ópticas que tenemos disponibles en el mercado.
Todos hemos tenido en alguna ocasión una cámara de fotos entre las manos y nos hemos preguntado
cuál es la función del juego de lentes que sobresale del cuerpo de la cámara.
Pues bien,
la función de una óptica es redireccionar los haces de luz, que provienen de la escena que
pretendemos capturar, sobre la zona de elementos sensibles de la cámara
para crear una imagen.
Para ello, los diferentes elementos que la componen deberán facilitar la alineación
del sistema óptico para obtener haces paralelos de rayos luminosos. Además, deberá permitirnos realizar
un enfoque lo más preciso posible.
A continuación, vamos a pasar a valorar cuáles son los parámetros fundamentales que definen una óptica.
A la hora de escoger una óptica
dentro de la amplia variedad que podemos encontrar,
hemos de fijarnos en varios parámetros que suelen aparecer impresos en su carcasa,
tales como la distancia focal, el número F,
además de otros de los cuales dependerá en gran medida la calidad de la imagen que capturemos,
como es el caso de la luminosidad y su rango de enfoque.
Precisamente, la luminosidad de un objetivo está condicionada, entre otros aspectos, por la cantidad de lentes que lo componen,
de qué materiales están fabricados,
el tipo de recubrimiento de sus caras y de su tamaño, sus diámetros.
A partir de éstos, se define la apertura máxima del diafragma,
siendo éste un elemento mecánico con forma de cortinilla o aletas, como puede apreciarse en la imagen de la derecha,
que permitirá regular la cantidad de luz que entra en la cámara.
En las ópticas de mayor calidad, para facilitar el enfoque de la escena de trabajo,
el objetivo lleva impreso una escala de distancias normalmente graduada en metros,
de manera que podremos enfocar sin necesidad de utilizar el visor.
En cuanto al resto de parámetros,
la distancia focal es uno de los principales a la hora de seleccionar una óptica.
Su valor suele venir expresado en milímetros y puede tomar un valor fijo o variar dentro de
un cierto intervalo en las ópticas de tipo zoom.
La distancia focal de una lente es la distancia entre el centro óptico de la lente y el foco o punto focal,
cuando enfocamos al infinito.
Los haces paralelos de rayos luminosos que proceden de la escena que pretendemos captar con nuestra
cámara convergen sobre ese punto que hemos llamado punto focal.
La distancia focal es el parámetro fundamental de nuestra óptica a la hora de relacionar el
tamaño de los objetos presentes en la imagen
y el que tienen en el mundo real.
En el siguiente módulo se analizará en detalle los diferentes modelos empleados para establecer
este tipo de relaciones.
Otro de los parámetros es el denominado número F.
Éste se utiliza como indicador comparativo entre objetivos. Se obtiene a través del cociente entre la
apertura máxima y la distancia focal.
El número F es inversamente proporcional a la apertura:
a menor número F tendremos una mayor luminosidad.
Algunos objetivos pueden presentar un número F fijo.
En el caso de ser variable, su valor se regula mediante la apertura o cierre del diafragma.
Generalmente, la apertura
efectiva se rotula gráficamente en el objetivo, con relación a la distancia focal.
En el caso de los objetivos con distancia focal variable,
suele venir representado por dos valores,
indicándose así la disponibilidad de apertura de diafragma según los extremos de funcionamiento.
Finalmente, en esta última sección de este módulo vamos a introducir los diferentes tipos de ópticas.
Por un lado,
están las ópticas de distancia focal fija. Éstas se destacan por poseer una calidad óptica superior, ya
que están construidas con menor número de elementos.
Suelen ser más luminosas desde el punto de vista de la calidad de la imagen,
poseen menos aberraciones geométricas y cromáticas y son más livianas y compactas que las de tipo zoom.
Como desventaja, hacen necesaria su sustitución por otros objetivos cuando
es preciso una distancia focal diferente, puesto que su longitud focal no puede cambiarse.
Por el contrario,
las ópticas de tipo zoom tienen la ventaja de ofrecer varias longitudes focales agrupadas en un solo cuerpo de objetivo,
lo cual se consigue mediante el movimiento de los elementos ópticos dentro de la carcasa.
Esto las hace más versátiles, ya que no requieren el cambio de objetivo para obtener una longitud focal diferente.
Como desventaja, poseen más elementos ópticos,
con lo cual existe una mayor probabilidad de aparición de aberraciones
y una mayor pérdida de luz.
Por otra parte, son más pesadas y frágiles que un objetivo fijo en igual relación de luminosidad.
Con esto concluimos el primer módulo del tema 2 dedicado a la óptica, donde
hemos valorado cuál es su misión en un sistema de percepción,
los parámetros fundamentales que la definen y los diferentes tipos que tenemos disponibles en el mercado.

# Curso   Semana 1   Tema 2. Óptica   Modelado de una óptica

Modelado de una óptica
 
Hola, en este segundo módulo del tema 2 vamos a estudiar cómo modelar la funcionalidad de una óptica en nuestro sistema de percepción.
Para ello,
analizaremos en primer lugar el modelo de lente fina, para pasar a continuación a valorar el modelo pin hole,
así como el estudio comparativo de ambos.
Finalmente, se introducirán otros parámetros representativos a tener en cuenta en el modelado de una óptica.
El modelo de lente fina nos relaciona la distancia a la que se enfocan los rayos luminosos, en función de la distancia
a la que se encuentran de la cámara los objetos presentes en la escena de trabajo.
Imaginemos que tenemos un objeto que está situado a una distancia U de la cámara,
varios de los rayos de luz reflejados por un punto de él serán captados por la lente y estos convergerán
una distancia V.
Como siguiente paso, sería interesante poder establecer algún tipo de relación entre ambas distancias.
De entre todos los rayos reflejados habrá uno que será paralelo al eje óptico y que, como ya
se explicó en el módulo anterior, cortará a este eje
por el punto focal.
Si tomamos en cuenta que la óptica es simétrica, un rayo de luz que corte al eje
óptico a una distancia igual a la distancia focal antes de la lente,
al pasar por ella saldrá paralelo a dicho eje.
Con estos dos rayos se pueden apreciar varios triángulos semejantes y, a partir de ellos, podemos
obtener la fórmula del modelo de lente fina,
en la que se aprecia que la suma de la inversa de la distancia a la que está
el punto del mundo y a la que convergen los rayos es constante e igual a la inversa de la distancia focal.
Del análisis de esta expresión se puede deducir que los objetos más lejanos quedarán enfocados antes que
los objetos cercanos
y, también, que es imposible enfocar los rayos de luz provenientes de un objeto que esté más cercano que la distancia focal.
Ahora se entiende porqué, cuando modificamos la distancia de enfoque en la óptica, conseguimos un efecto similar
al de mover el elemento sensor,
razón por la que se irán enfocando objetos que estén a diversas distancias de la cámara
y desenfocando otros a distancias mayores
o menores.
A continuación, pasamos a valorar el modelo pin hole.
El modelo denominado pin hole o de ojo de aguja se corresponde con el modo de funcionamiento
de las primeras cámaras de fotografía que se desarrollaron
y que consistían en una caja en la que se realizaba una pequeña abertura, un agujero,
de tal forma
que de entre todos los rayos luminosos reflejados por un punto del objeto, solamente uno de ellos alcanzaba la película fotográfica,
en nuestro caso el sensor de la cámara.
Cuando aplicamos este modelo a las cámaras, también suponemos que sólo existe un rayo luminoso
que es el que une el punto focal
y el punto del objeto.
A una separación igual a la distancia focal se encontrará el sensor de la cámara y
el punto de corte del rayo dará lugar a la proyección del punto del objeto en la imagen.
Llegado a este punto,
podemos preguntarnos cuál es la expresión matemática que relaciona las coordenadas del mundo y las de la imagen
en el modelo.
De nuevo, vamos a utilizar relaciones entre triángulos semejantes.
En la figura se puede apreciar que la proporción entre las coordenadas del punto de la imagen
y la distancia focal
es igual a la de la coordenada del mundo y la distancia a la que está este punto de
la cámara.
A partir de estas relaciones podemos fácilmente deducir que cuanto mayor sea la distancia focal de la óptica empleada,
mayores serán las dimensiones del objeto en la imagen.
En este apartado vamos a realizar una comparativa de los dos modelos vistos.
Para ello, vamos a recurrir al llamado factor de magnificación,
que se define a partir de la relación entre el tamaño real del objeto y el proyectado
sobre el plano de la imagen.
En el modelo pin hole,
la distancia focal es proporcional al factor de magnificación,
mientras que en el modelo de lente fina quedaría según se muestra en la ecuación.
Además, normalmente las dimensiones en la imagen
son mucho menores que las del mundo real,
de tal forma que podremos aproximar M+1 a la unidad, obteniendo así en ambos casos la misma expresión.
Finalmente, vamos a analizar otros parámetros característicos de las ópticas.
El ángulo visual es aquel formado por dos rayos que inciden sobre los bordes extremos de
la zona sensible de la imagen. Obviamente, este parámetro dependerá de las dimensiones del sensor y de
la distancia focal de la óptica utilizada.
Una misma cámara tendrá un mayor ángulo visual conforme le coloquemos una óptica con una distancia focal
menor,
de esta forma distancias focales bajas son capaces de captar
un espacio mayor que focales largas, pero por contrapartida los objetos se verán más pequeños.
Otro parámetro importante es la profundidad de campo. Del modelo de lente fina se puede derivar
que solamente los objetos que están a una determinada distancia estarían enfocados en el plano de imagen.
Los rayos de luz provenientes de objetos que estuviesen más cercanos no lograrían converger sobre un punto del plano de imagen
y los provenientes de puntos más lejanos habrían ya convergido y empezado separarse.
Sin embargo, la experiencia demuestra que esto no es así,
sino que en una imagen hay un rango de distancias para la que todos los objetos están enfocados.
Este rango de distancias es la llamada profundidad de campo.
Esto se debe a que el elemento sensor de la cámara tiene unas dimensiones pequeñas,
pero no infinitesimales.
Esto conduce a que, aunque los rayos de luz hayan convergido y comenzado a separarse,
todos ellos caen dentro del mismo elemento del sensor
y, por lo tanto, desde el punto de la imagen estarán tan enfocados como si estuvieran a la distancia de
enfoque,
ocurriendo lo mismo para el caso contrario.
Un caso particular de la profundidad de campo es la distancia hiperfocal.
Se define como aquella distancia de enfoque cuya profundidad de campo tiene un margen desde infinito hasta la mitad de ella.
En el aro de enfoque que tenemos en las ópticas, se corresponde a la posición marcada con el símbolo de infinito.
Con todo esto concluimos el segundo módulo del tema 2,
donde se han introducido los conceptos para el modelado de la óptica y otros parámetros fundamentales que nos ayudarán a escogerla.

# Curso   Semana 1   Tema 3. Cámaras digitales   Sensores CMOS y CCD

Sensores CMOS y CCD
 
Hola,
bienvenidos a este nuevo tema en el que trataremos las cámaras digitales.
Durante los próximos vídeos vamos a estudiar las nociones básicas sobre cámaras digitales que suelen emplearse
en las diferentes aplicaciones de visión por computador.
Para ello, vamos a ver primero una serie de aspectos que nos pueden servir para realizar
clasificaciones de cámaras digitales,
de tal forma que podamos decidir qué cámara emplear en cada aplicación,
dependiendo de las necesidades que tengamos que utilizar.
¡Empezamos!
Las cámaras se pueden diferenciar de acuerdo a:
el tipo de sensor,
tendremos cámaras de sensores tipo CCD y sensores CMOS y
también hablaremos, aunque ya en el próximo vídeo, de la clasificación de cámaras dependiendo del número sensores
y dimensión de éstos,
así como de si son tecnologías de dos dimensiones o de tres dimensiones.
En último lugar, veremos los protocolos de comunicación que se emplean para conectar las cámaras digitales con las computadoras.
Volviendo al tema de este vídeo, que trata sobre los tipos de cámaras digitales de acuerdo a la tecnología del sensor,
tenemos dos grandes tipos de cámaras, según utilicen sensores de tipo CCD
o sensores de tipo CMOS.
Los primeros se basan en elementos sensibles a la luz,
que al ser activados por un reloj, crean un pozo de potencial.
Al llegar la luz se producen electrones que quedan atrapados en este pozo de potencial, siendo su número proporcional
a la intensidad luminosa que reciben.
Usando registros de desplazamiento,
se lee la imagen línea a línea, utilizando conversores analógico-digitales.
De esta forma, se consigue que el valor de intensidad lumínica de cada punto del sensor
se corresponda con cada píxel de la imagen.
Las cámaras CMOS son más modernas que las cámaras CCD.
En estos casos, la conversión de luz nos da un valor digital,
mediante el uso de varios transistores en el propio elemento sensible.
Por lo tanto, a diferencia de las cámaras CCD,
no necesitan registrar este desplazamiento ni conversor analógico-digital.
¿Qué ventajas e inconvenientes presentan una y otra tecnología?
La primera ventaja que nos encontramos, al comparar las cámaras de tipo CCD y CMOS,
es que, estas últimas,
realizan la conversión analógico-digital en el mismo fotodiodo, por lo que los sensores son más reducidos,
ya que no son necesarios elementos electrónicos para el desplazamiento de carga.
Por otro lado, se puede acceder a cada píxel de forma individual,
por lo que no se necesita leer toda la imagen de una sola vez, como ocurre con
las cámaras de tipo CCD.
Por ello, es frecuente que, en las cámaras de tipo CMOS, se defina lo que se conoce como una región de interés
o ROI por sus siglas en inglés,
que se puede leer, sin necesidad de obtener el resto de la imagen,
una región reducida de esta misma.
Se consiguen así velocidades de transferencia superiores, al centrarnos en una región más pequeña de la imagen, que
es sobre la que vamos a trabajar.
Por otro lado, al ser la tecnología de CMOS igual a la de otros dispositivos electrónicos,
como memorias o microprocesadores,
el coste de fabricación es menor y se pueden integrar en circuitos electrónicos de control
dentro del mismo dispositivo de captura.
Otro aspecto interesante,
es que el consumo eléctrico de las cámaras de tipo CMOS es más reducido que el de las cámaras de tipo CCD.
Por último, y muy importante, las cámaras de tipo CMOS no presentan efecto blooming,
efecto que sí sufren las cámaras de tipo CCD.
Este efecto se da cuando un píxel de una cámara CCD recibe mucha luz,
por lo que el número de electrones que desprende el elemento sensor es mucho mayor del que es capaz de almacenar,
con lo que se desborda y transmite la carga que le sobra a los píxeles vecinos,
llegándose a saturar y, por lo tanto, propagando el efecto
a largo del sensor y,
por ello, las cámaras CCD son más sensibles a brillos de focos de luz muy potentes.
Un ejemplo clásico es una cámara CCD captando la imagen de la bombilla encendida.
La imagen sería similar a lo que ve un ser humano, donde toda ella está iluminada,
mientras que si la cámara es de tipo CMOS,
solamente el filamento estaría claro y el resto de la bombilla sería transparente.
En estas imágenes podéis ver dos ejemplos de situaciones parecidas en las que una de ellas sufre este efecto.
Las imágenes muestran una puesta de sol,
la de la izquierda sufre el efecto blooming y la de la derecha
no lo sufre.
De esta forma, en la imagen de la derecha podéis apreciar el contorno del sol, mientras que el
efecto blooming no nos deja observar este detalle en la imagen de la izquierda.
Así que, recapitulando, las cámaras CMOS tienen la ventaja de
mejor acceso, más rápido y eficiente,
un consumo menor y no sufren el efecto blooming que os he descrito.
Por contra, las cámaras CCD tienen también una serie de ventajas importantes a tener en cuenta,
como son que la calidad de la imagen es más alta,
luego tienen mejor sensibilidad al ser mejor la relación señal a ruido.
Esto se debe a que se tienen procesadores de señal externos al propio sensor,
lo que permite añadir sistemas más complejos y sofisticados.
Además, tiene menos píxeles defectuosos y la ganancia de cada uno de ellos es uniforme y
el número de píxeles de los sensores es mayor.
Todas estas ventajas hacen que aún se empleen en muchas de las cámaras de alto rendimiento,
como cámaras réflex, pero de cualquier forma,
los avances en tecnología CMOS, con sensores mayores,
más potentes, de mejor calidad y de bajo consumo hacen que cada vez más cámaras de alto rendimiento
incorporen sensores de tipo CMOS.
Esto es todo en este capítulo dedicado a los sensores de las cámaras digitales.
Cuál elegir y cómo dependerá de la aplicación que desarrollemos, pero de cualquier forma, ya tenemos los ingredientes necesarios para poder escoger
cuál nos interesará para cada una de las situaciones.
En el próximo capítulo trataremos otro tipo de clasificación de cámaras,
dependiendo de las dimensiones del sensor
y de la cantidad de sensores incorporados.
Esto es todo, espero que os haya gustado, un saludo y hasta el próximo capítulo.

# Curso   Semana 1   Tema 3. Cámaras digitales   Número y dimensión de sensores

Número y dimensión de sensores
 
¡Hola! Bienvenidos a este nuevo vídeo del tema 3 del curso Hasta dónde pueden ver las máquinas.
Como recordaréis del vídeo anterior, estamos estudiando las nociones básicas sobre las cámaras digitales,
que se pueden utilizar para las diferentes aplicaciones de visión por computador.
En este nuevo vídeo veremos diferentes opciones de sensores según el tamaño y dimensiones de los mismos
y es que puede haber distintos sensores, ya sean unidimensionales o sensores bidimensionales
o, incluso, podemos encontrarnos también con cámaras con un único sensor o con cámaras con varios sensores
incorporados.
Como veis hay muchas y varias combinaciones
y vamos a ver, en este capítulo,
a qué nos referimos con cada una de ellas.
Por lo tanto,
según las dimensiones tendremos sensores matriciales o sensores lineales.
A su vez, cada uno de estos sensores
pueden ser sensores en blanco y negro o sensores en color
y, dentro de estos últimos, se puede dar el caso de un solo sensor
o de tres sensores.
Si estudiamos las cámaras en función de las dimensiones del sensor tendremos cámaras matriciales y cámaras lineales,
según que el elemento sensor sea bidimensional o tenga una única línea de sensores.
Las cámaras matriciales son las que utilizan clásicamente las cámaras fotográficas que todos conocemos,
mientras que las lineales se utilizan, por ejemplo, en una escáner.
Un ejemplo
de este tipo de cámaras también es un escáner de huella dactilar,
que son comunes, hoy por hoy, en la mayor parte de computadores, como veis en el vídeo que tenéis en la imagen.
Otro ejemplo de sensores lineales en la industria es cuando utilizamos cámaras lineales para inspeccionar productos continuos, como puede ser
el papel
o la madera
o, incluso, los lectores de códigos de barras.
En ambos casos, las cámaras pueden capturar imágenes en blanco y negro o imágenes en color.
En el caso de las imágenes en color,
se puede dar que tenemos un único elemento sensor o tres elementos sensores,
como veremos en las próximas transparencias.
Las primeras cámaras capturaban las imágenes en blanco negro,
ya que la salida
que obteníamos era proporcional a la cantidad de luz que llegaba al sensor, independientemente de la longitud de onda del mismo.
Lo que ocurre con las cámaras a color es que utilizamos filtros colocados en cada uno
de los píxeles, que solamente dejan pasar la longitud de onda de un color determinado.
De esta forma, podemos capturar el color.
Para ello, necesitamos capturar, por un lado, la componente roja, la componente verde y la componente azul
o RGB por su notación en inglés.
En caso de tener un único sensor, lo que tendremos es una matriz de píxeles en la
que se van alternando píxeles rojos, píxeles verdes y píxeles azules,
como se observa en la imagen que tenéis en vuestra transparencia.
Esa imagen representa la disposición más común de este tipo de sensores,
que es lo que se conoce como filtro de Bayer.
Se ve como para cada píxel
de color
lo que tenemos es una combinación de píxeles
rojo, azul
y dos píxeles verdes.
El hecho de que haya dos píxeles verdes se debe a que el ojo humano es más sensible al color verde
y lo que vamos a intentar en nuestra reproducción de imágenes, es reproducir de una forma lo más fielmente posible,
la imagen que tenemos tal y como la vemos nosotros.
Aunque la imagen de la calidad es buena,
lo que ocurre es que para cada uno de los filtros de Bayer, cada uno de los píxeles del filtro de Bayer, corresponde
a 4 puntos colocados distintos en el mundo,
por lo que tendremos problemas a la hora de representar la imagen en nuestro ordenador, sobre todo
cuando estamos intentando representar contornos.
Por esta razón, se desarrollaron las que se conocen como cámaras de tres sensores.
Lo que ocurre con los tres sensores es que están colocados en posiciones distintas dentro de la propia cámara
y, mediante un juego de filtros y prismas, se lleva la luz a cada una de las tres componentes
del sensor.
En la animación que tenéis en la pantalla, veis cómo la imagen se divide en tres componentes distintas
y cada una de ellas es dirigida a cada uno de los distintos sensores
que tiene la imagen para cada uno de los colores.
La calidad de la imagen de este tipo de sensores es mucho más alta, al igual que el precio de la cámara.
En cuanto a los tamaños de sensor,
las resoluciones de las cámaras matriciales son muy diversas y van desde las dimensiones mínimas de 640x480
o 742x582, que corresponde a los antiguos estándares de vídeo analógico,
a casi los 5000x3000 píxeles actuales.
Desde luego,
hay que decir que estos datos son totalmente provisionales, ya que la tendencia es construir sensores cada vez más
potentes, con mayor número de píxeles
y es posible que el día que vosotros veáis este vídeo
tengáis a vuestra disposición sensores con mucha más capacidad que los que acabo de comentar.
Otro aspecto importante a saber es que las dimensiones globales del sensor,
que afectan a varios parámetros,
el ángulo visual, por ejemplo,
la tendencia es a hacer sensores cada vez más pequeños
y, así, mientras hace unos años teníamos cámaras de 2/3",
que eran las más frecuentes, hoy por hoy, se usan mucho las de 1/3".
En el caso de las cámaras lineales, tendremos desde los 500 píxeles hasta muchos miles de ellos.
La resolución de las cámaras lineales siempre va a ser mayor que las matriciales
y aquí, otro parámetro importante en el caso de estas cámaras es el número de líneas capaces de capturar por segundo,
que nos darán el formato de las imágenes con las que vamos a poder trabajar.
Esto es todo en este nuevo capítulo dedicado a los sensores de las cámaras digitales,
en concreto a su número y dimensiones.
En este capítulo, hemos visto que las cámaras pueden tener sensores bidimensionales o sensores unidimensionales
y, además, hemos visto que las cámaras a color pueden tener desde un único elemento sensor hasta
tres elementos sensores, según la configuración.
De nuevo, cuál elegir dependerá de la aplicación que queremos desarrollar
y, gracias a este capítulo que hemos visto hoy, sabemos las ventajas e inconvenientes de cada uno de ellos.
Esto es todo, espero que os haya gustado este capítulo. Un saludo y hasta el próximo capítulo de
hasta dónde pueden ver las máquinas,
donde demostraremos que la visión ya no es sólo cosa de seres humanos.

# Curso   Semana 1   Tema 3. Cámaras digitales   Tipos de salida y cámaras 3D

Tipos de salida y cámaras 3D
 
Bienvenidos a este nuevo vídeo del tema 3 del curso Hasta dónde pueden ver las máquinas.
Como recordaréis de los vídeos anteriores, estamos estudiando las nociones básicas sobre las cámaras digitales
que se pueden utilizar
en las diferentes aplicaciones de visión por computador.
En este último vídeo veremos los dos últimos aspectos que nos quedan por tratar, que son
las cámaras tridimensionales, en las que veremos las diferentes alternativas,
que nos permiten obtener, además de la imagen en color,
otra información extra,
como distancia.
Por último, veremos un aspecto que, no por menos tratado, es menos importante.
Me refiero al tema relacionado con los protocolos de salida, es decir, las comunicaciones entre las cámaras, o el sensor mismo,
con el propio ordenador.
Existen diversos métodos y el uso de uno u otro nos permitirá sacar el máximo partido
y rendimiento a nuestro sistema.
Las cámaras de vídeo y fotos clásicas con las que trabajamos actualmente, son cámaras de tipo
2D, donde lo que vemos es una representación bidimensional de un mundo tridimensional.
Pero existe un tipo de cámaras, que ha aparecido recientemente, que son los que se denominan cámaras
de tipo 3D.
Se llaman así porque nos proporcionan información tridimensional de los objetos,
que hay delante de la cámara. Es decir, además de la información propia de las cámaras comunes, como el color,
la intensidad, etc.
tenemos información de la distancia de los objetos dentro de esta imagen.
Básicamente, hay dos grandes grupos según se obtenga esa información, por tiempo de vuelo o por la
deformación de un patrón de luz conocido.
Las primeras calculan la distancia midiendo el tiempo que tarda la luz en ser reflejada por los objetos del entorno,
de ahí su nombre,
y esto se realiza para cada uno de los píxeles de la imagen.
Además,
como se utilizan diodos led para iluminar la escena,
además de la información relativa a la distancia, dan una  imagen bidimensional en el infrarrojo cercano.
Otra forma de obtener la información tridimensional es observar la deformación de un patrón de luz
capturada por una cámara.
De acuerdo a los cambios, se puede obtener la información tridimensional de la imagen.
Ésta es la tecnología que se utiliza, por ejemplo, para la primera cámara kinect de Microsoft.
Este sensor se empleó para grabar la secuencia que tenéis en pantalla. Aunque no es necesario
para su funcionamiento, se suele añadir otra segunda cámara a color, dando lugar a lo que se denomina
sensores RGBD.
R es por Red,
G es por Green,
B por Blue y D
es relativa a la distancia que obtenemos para cada uno de los píxeles de nuestra imagen,
gracias a esta información que os he comentado.
Por último, otro de los sistemas de cámaras que nos permiten obtener información tridimensional, son los llamados sistemas estéreos.
Este sistema estéreo, como el que tenéis en la imagen,
permite
obtener la información tridimensional gracias a dos cámaras que están separadas a una distancia conocida.
Gracias a la combinación de las dos o más cámaras
y comprobando la diferencia de píxeles para el mismo objeto en una cámara y en la otra,
podemos identificar la distancia a la que están estos objetos
de una forma determinada.
De hecho, imita a la visión humana. Es decir, nosotros como seres humanos podemos
obtener información tridimensional gracias a que tenemos dos ojos. Con un único ojo, el ser
humano sería incapaz de interpretar la profundidad de una imagen de una forma fiable.
Los sistemas estéreos
no es una teología moderna, ya que se lleva empleando en el sector de la visión por computador
durante muchos años.
Lo que ocurría con este tipo de sistemas es que el requerimiento computación era muy grande.
Por lo tanto, esto hacia que no se utilizasen estas aplicaciones,
sobre todo de cara a utilizar aplicaciones de tiempo real.
En los últimos años, gracias a los avances en las capacidades de computación de los ordenadores,
se ha podido lograr que estos sistemas funcionen de una forma más o menos
robusta en tiempo real,
llegándose a utilizar de una forma cada vez más y más frecuente.
Por ultimo, como os comenté con anterioridad, vamos a ver los protocolos de comunicaciones entre el sensor de la cámara y el ordenador.
Éste es un aspecto que ha cambiado mucho durante los últimos años.
Hasta hace relativamente poco, las cámaras tenían como salida estándar una señal analógica y necesitábamos
lo que se denominaban tarjetas capturadoras de vídeo para digitalizarlas.
Esto ya no es necesario, ya que en los ordenadores hay varios estándares de comunicaciones serie, que permiten transmitir una cantidad de información muy alta
al ordenador
en tiempo real
y, además, esta información del sensor ahora es capturada de forma digital, no analógica como teníamos anteriormente.
En la actualidad, hay dos estándares que son los más importantes,
que son el USB3,
el gigabit ethernet
y existe, además, un tercer estándar como es el Firewire,
que aunque cada vez tiene menos importancia, no se puede descartar del todo.
El estándar más reciente es el USB3. A partir de este estándar,
se ha desarrollado lo que se denomina USB3 Vision,
específicamente diseñado para cámaras digitales
y que está siendo desarrollado y apoyado por varios fabricantes importantes de cámaras.
Permite una transmisión de hasta 350 MB/s y una distancia máxima de 5 m.
entre la cámara y el ordenador.
Como alternativa existe gigabit Ethernet, que es el protocolo empleado por las tarjetas de red con las
que vienen equipados cualquier ordenador de sobremesa u ordenador portátil.
La versión 2.0,  que es la llamada 10 gigabyte,
permite una transmisión muy alta de información entre el ordenador y la cámara
y, sobre todo, una distancia muy grande entre los dos elementos
que se puede cifrar en 100 metros.
Como he comentado, existe un tercer estándar que es el Firewire, aunque es muy útil para las cámaras está
un poco en desuso en los últimos años.
Lo que ocurre es que los últimos modelos de PC directamente no traen estos puertos de comunicaciones.
Por lo tanto, se hace cada vez menos común encontrarnos con cámaras que también lo incorporen.
Esto es todo en este nuevo capítulo dedicado a los sensores de las cámaras digitales,
en concreto a los sensores de tres dimensiones y a los protocolos de comunicaciones.
De nuevo, cuál elegir dependerá de la aplicación que queremos desarrollar
o de nuestro presupuesto.
Espero que os haya gustado este capítulo. Un saludo y hasta el próximo capítulo de Hasta dónde puede la máquinas,
donde demostramos que la visión ya no es sólo cosa de seres humanos.

# Curso   Semana 1   Tema 4. La biblioteca OpenCV   Qué son las OpenCV

Qué son las OpenCV
 
Hola, yo soy David
y yo soy Abdulla.
Somos vuestros profesores de prácticas y os guiaremos en este curso en el aprendizaje de las librerías OpenCV
de visión por computador.
A partir de ahora no vais a vernos, pero estamos con vosotros en las prácticas.
Por tanto, vamos a empezar este primer vídeo práctico
y os vamos a presentar la librería de funciones OpenCV,
que se utilizará durante el curso cuando se programen los diversos algoritmos de análisis de imágenes.
Para ello, haremos una breve introducción al motivo por el que las OpenCV fueron diseñadas.
Comenzamos, por tanto, con una breve introducción a la biblioteca de funciones OpenCV
que, desde su aparición en el año 2000,
se ha convertido en el estándar
para cualquier aplicación de visión por computador programada en C o en C++.
Esta biblioteca
tiene como finalidad ayudar al avance de la visión por computador,
aportando código abierto y optimizado
para que los investigadores o empresas puedan desarrollar algoritmos de análisis de imágenes.
Su inicio
fue en el año 1999,
cuando la empresa Intel anunció el desarrollo de esta biblioteca.
El año siguiente publicó la primera versión alfa.
Hasta el año 2005 aparecieron 5 versiones beta,
en el año 2006 se publicó la primera versión desarrollada en lenguaje de programación C,
que se extendió en la versión 2,
tres años después, al lenguaje programación C++.
A partir de ahí,
aunque las OpenCV siguen manteniendo su compatibilidad
con el lenguaje C,
cada vez incorporan más funciones descritas en C++ y,
en la actualidad, hay más de quinientas funciones.
En el año 2012 se creó la fundación sin ánimo de lucro
OpenCV.org,
hoy en día encargada de mantener y seguir desarrollando esta biblioteca.
Como se ha comentado anteriormente,
los lenguajes de programación principales
son el C y
el C++,
pero en las versiones recientes se han añadido el lenguaje Python y CUDA.
Este último es una extensión del lenguaje C
desarrollado por el fabricante de tarjetas gráficas Nvidia,
que permite el desarrollo de algoritmos que corran en paralelo en ellas,
con lo que se aceleran mucho los tiempos de cómputo.
Las OpenCV inicialmente se desarrollaron para Windows y Linux,
pero, posteriormente, han sido portadas a otros sistemas operativos como OS X, Android e iOS.

# Curso   Semana 1   Tema 4. La biblioteca OpenCV   Bibliografía

Bibliografía
 
Hola a todos.
En el siguiente vídeo práctico veremos la bibliografía actual.
Los libros que podemos comprar y que explican las librerías OpenCV son los siguientes:
el primer libro, Learning OpenCV, de la editorial O'Reilly,
que fue escrito por Gary R. Bradski y Adrian Kaehler
en el 2008
y utiliza la versión 2.0 de las librerías OpenCV,
por lo que hay muchos temas que se han ido implementando en la librería desde esa primera versión
y que no son tratados en el libro.
Por ello, se realizó una segunda edición en el año 2014
y que, como anuncia el subtítulo del libro, utiliza el C++
como lenguaje de programación,
a diferencia de la primera versión que utilizaba el lenguaje de programación C.
El segundo libro, OpenCV Cookbook
fue escrito por Robert Lagarnière en 2011
y su enfoque está centrado ya en el uso del lenguaje de programación C++,
donde, en la siguiente dirección que podéis observar en pantalla,
se puede hacer a los códigos fuente y a todas las imágenes usadas
en el documento,
así como a las erratas del libro.
El tercer libro, Mastering OpenCV with Practical Computer Vision ProJect,
está publicado por la misma editorial
y está escrito por varios autores.
El libro apareció en el año 2012
y el enfoque es distinto a los dos anteriores, ya que aquí se divide el documento en varios proyectos prácticos
que pueden ser implementados
por las librerías OpenCV y que son descritos paso a paso.
El siguiente libro,
Instant OpenCV Starter de Dalal y Patel,
es muy breve, solamente son 56 páginas, y tiene como finalidad resolver las primeras dudas
de alguien que quiere familiarizarse con las librerías OpenCV.
Por tanto, se explica así su instalación y unos primeros programas básicos.
Como se ha comentado anteriormente, esta librería de funciones está portada a diversos sistemas operativos
y, por ello, están empezando a aparecer
libros centrados en otros sistemas operativos
distintos a Windows y Linux.
Así, el libro Android Application Programming with OpenCV está escrito por Howse
para el sistema operativo Android.
O el de Kornyakov y Shishkov titulado Instant OpenCv for iOS para el sistema operativo iOS.
Tampoco es obligatorio realizar los programas en C++
y, debido a ello, tenemos el libro OpenCV Computer Vision with Python escrito por Howse.

# Curso   Semana 1   Tema 4. La biblioteca OpenCV   Manuales y página web

Manuales y página web
 
Hola a todos. En el siguiente vídeo práctico veremos los manuales y la página web de las librerías
OpenCV,
donde tenemos toda una serie de manuales online
accesibles en Internet
y que están accesibles en la página web de las librerías OpenCV
y, especialmente, uno de ellos que los autores han llamado chuleta,
porque recoge
las funciones más importantes.
La primera forma de acceder en la página web de las OpenCV es a través
de los enlaces rápidos, lo que llamamos quick links,
donde tenemos diversos apartados.
Si pinchamos en la documentación online
pasamos a tener un acceso a todas las bibliotecas individuales que forman la biblioteca OpenCV.
En cada una de ellas podemos buscar todas las funciones que las componen.
Tenemos también un enlace genérico a documentación
y dentro está referencia,
donde podemos ver la información de la API,
que es la interfaz de programación
de aplicación de las OpenCV,
en donde podemos ver de nuevo todas las librerías,
pero con un detalle mayor que en el enlace que hemos visto anteriormente.
Tenemos también la guía de usuario,
que es uno de los puntos menos elaborados en la documentación escrita por los desarrolladores de las librerías OpenCV.
Es por ello por lo que se han escrito los libros que hemos nombrado en el
vídeo anterior.
En tercer lugar, tenemos los tutoriales que agrupan varias páginas por temáticas afines.
Por un lado, tenemos los que hacen referencia
a cada una de las bibliotecas,
donde se nos irán poniendo diferentes ejemplos
para usarlos en las funciones que las componen.
También tenemos todo un tutorial de introducción, donde se nos enseña la instalación de las OpenCV en Windows
o en Linux,
junto al primer ejemplo para mostrar una imagen por pantalla.
Tenemos otros tutoriales, por ejemplo, para la instalación de programación desde OpenCV bajo el sistema operativo iOS
o el módulo de aprendizaje máquina
que, en general, están poco desarrollados en las librerías OpenCV.
El enlace de comienzo, Quick Start,
hace referencia a lo que son los primeros pasos
con la biblioteca,
su instalación en diversos sistemas operativos
y el uso de diversos editores de programas como el Eclipse o el Visual de Microsoft.
En segundo lugar, vamos a ver un bloque
que hace referencia a los distintos manuales,
que son cinco ficheros en formato PDF.
El primero de ellos es el manual de referencia,
en el que si leemos el índice observaremos que están todas las librerías que forman las OpenCV
y, además, detalla las distintas funciones que existen dentro de cada una de ellas.
A continuación, el manual de administración,
Manager Manual,
está en sus comienzos
y apenas trae
algo de información, sobre todo de Android y Java.
El siguiente manual, La guía de usuario, también está muy incompleta
y apenas tenemos información de unas pocas funciones de las librerías OpenCV.
Sin embargo, mucha más suerte tenemos con el siguiente documento dedicado a los tutoriales
y en el que se repasan una serie de bibliotecas
y se nos presentan diversos ejemplos, que están relativamente bien explicados
para lo que podemos hacer
los programas por nuestra cuenta.
Por último, tenemos la chuleta.
Éste es el nombre que realmente han dado los desarrolladores de las librerías OpenCV
y en este documento tenemos las funciones más importantes junto a los parámetros que necesitamos para trabajar
con dichas referencias.

# Curso   Semana 1   Tema 5. Herramientas software del curso   Descarga e instalación de las OpenCV

Descarga e instalación de las OpenCV
 
Vamos a nuestro buscador, por ejemplo Google, introducimos
www.opencv.org.
Directamente esto nos lleva a la página web de
OpenCV,
donde tenemos que pinchar en OpenCV.
Una vez que entramos dentro de su página web,
podemos observar que en el lado derecho tenemos la zona de descargas. Vamos a la zona de OpenCV
for Windows
y descargamos la versión que tienen actualmente, la 3.0 RC1.
Pinchando en OpenCV for Windows vamos directamente a la descarga del ejecutable
que nos va a permitir descargar las librerías OpenCV.
Pasados unos segundos se puede observar que se nos abre una ventana de diálogo
con las librerías OpenCV.
Decimos donde queremos descargarlas. En este caso, yo voy a realizar mi instalación directamente en el disco C,
en el raíz y voy a darle aguardar justamente en el disco C para que se descarguen
y descompriman las librerías.
A continuación, damos a guardar y se puede observar que nos ha aparecido en nuestro disco C,
en el raíz,
el ejecutable de OpenCV 3.0.0 RC1.
Pinchamos y nos aparece que nos lo va a extraer en C,
decimos que sí
y comienza
la extracción de las librerías OpenCV en la carpeta que hemos seleccionado.
Una vez que termina justamente la extracción de las librerías, podemos ir directamente a la carpeta opencv
y observar, justamente, las librerías que se han descomprimido.
Como hemos comentado,
directamente,
si vamos a C, que es donde hemos pedido que se descompriman
y vamos directamente a
"Build",
podemos observar que tenemos x64 y x86, nos quedamos con x86
para máquinas de 32 bits
y entramos en vc12 que corresponde a Visual C 2013.
A continuación, en "Propiedades"
vamos a "Configuración avanzada del sistema" para establecer lo que son las variables de entorno.
Estas variables de entorno, vamos directamente a Variables del sistema, decimos que queremos crear una nueva variable
e introducimos OPENCV_DIR
y, a continuación,
indicamos
el valor de la variable que será C que es donde hemos instalado,
C:\opencv
y, a continuación,
\build
y, a continuación, vamos a decir el tipo de máquina que vamos a ejecutar -en
mi caso va a ser x86,
que es justamente una máquina de 32 bits- para ejecutar en vc12 que corresponde
a Visual C 2013.
Damos a aceptar y ya tendríamos las variables de entorno configuradas
de nuestras librerías OpenCV.
A continuación, volvemos a "Variables de entorno",
vamos a la parte de "path" donde tenemos que indicar dónde están estas librerías para que luego Visual C las
pueda encontrar.
Por tanto, vamos a "path" e introducimos
;%OPENCV_DIR%\bin
;%OPENCV_DIR%\bin
De esa forma,
Visual 2013
edition 2013 podrá encontrar
las librerías de OpenCV instaladas en nuestra máquina en Windows 8.
En el próximo vídeo veremos la creación de un primer programa utilizando las librerías OpenCV 3.0,
programadas en Visual C 2013 y Windows 8.

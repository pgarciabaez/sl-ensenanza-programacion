# Migración a SL en la enseñanza de la programación [^1]
[^1]: Este trabajo fue presentado en el [I Congreso de las Tecnologías del Softaware Libre](https://dialnet.unirioja.es/servlet/libro?codigo=476932) (La Coruña, 2005)

__Patricio García Báez__

__Dpto. de Estadística, I.O. y Computación__

__Universidad de La Laguna__

__38271 La Laguna, S/C Tenerife__

__e-mail:__ ``pgarcia AT ull.es``




## Software libre

El movimiento de software libre (SL) se fundamenta en una filosofía que supone que un usuario puede estudiar y modificar el funcionamiento de un programa para adaptarlo a sus necesidades y que puede distribuir copias del mismo incorporando esas modificaciones. Esta filosofía está soportada legalmente por un tipo de licencia libre. Una condición imprescindible para cumplir con estos requisitos es que el código fuente de las aplicaciones esté disponible para sus usuarios finales. Es por ello que con frecuencia a los programas de SL también se les denomina aplicaciones de código abierto.

En la actualidad hay varios segmentos del mercado informático donde el SL le está ganando terreno al software propietario. Por ejemplo, la mayoría de los servidores web utilizan Apache, una aplicación de código abierto. Otros proyectos que están teniendo un alto grado de implantación son el sistema operativo GNU/Linux, la suite ofimática OpenOffice.org, o el navegador Mozilla, por citar sólo algunos ejemplos. El factor más importante que limita la expansión del SL es el desconocimiento de su existencia por parte del gran público. Otros factores que inciden negativamente en el éxito del SL son: en primer lugar, la idea errónea de que todo lo que es gratis carece de un nivel suficiente de calidad, y en segundo lugar, que son muchos quienes piensan que los programas libres son más complejos de manejar que sus alternativas propietarias.

El SL está en auge y ello se debe en gran medida a la cantidad de iniciativas que han apostado firmemente por su implantación en diferentes ámbitos. Las universidades constituyen un entorno particularmente adecuado para el crecimiento de aplicaciones desarrolladas bajo esta filosofía [3], puesto que el modelo de desarrollo del SL, en el que se prima el compartir e intercambiar ideas, es muy parecido al que siguen la Ciencia y la Tecnología donde los descubrimientos se publican y comparten para, a partir de ellos, producir otros nuevos. De hecho, la mayoría de este tipo de aplicaciones surge de entornos académicos.

En la universidad se deben formar profesionales con capacidad de dar respuestas a los problemas que encontrarán en el ejercicio de su actividad. Si sólo exponemos a nuestros estudiantes a la utilización de herramientas propietarias, será este tipo de herramientas las que utilicen cuando ejerzan su profesión y así seguiremos promoviendo el status quo. Nuestros estudiantes deben conocer las diferentes formas de resolver un problema y llegado el momento decidirán la mejor solución para cada caso. Si sólo les enseñamos una forma de trabajar, estarán limitados en el ejercicio de su profesión.

Una razón adicional para promover el uso de SL es que al hacerlo estamos potenciando nuestra industria local y la formación de profesionales en nuevas tecnologías. Por último, la razón más evidente e importante para promocionar la utilización de SL en las aulas universitarias, viene determinada por la gran calidad que aportan algunos productos desarrollados bajo este modelo. Se trata en muchos casos de herramientas, con una calidad similar o superior a su contrapartida propietaria, que permiten eliminar la copia ilegal de programas.

En el contexto de la docencia en informática, el hecho de que los alumnos dispongan del código fuente de estas aplicaciones les permite profundizar mucho más en su conocimiento y para los docentes son una fuente casi inagotable de ejercicios y posibilidades educativas. En el caso de otras disciplinas, veremos que también son importantes las ventajas que conlleva la implantación de SL en las aulas.

## ETSII y el software libre

La ETSII (antiguo Centro Superior de Informática) desde su inicios, en 1990, siempre ha utilizado SL asociado a sus sistemas informáticos unixs (HP-UX y Solaris). El sistema operativo GNU/Linux en sus inicios fue introducido para permitir que los PCs pudieran conectarse en modo gráfico a los servidores Sun. Poco a poco ha ido ganando mas relevancia como sistema operativo autónomo, convirtiéndose hoy en día en el mas utilizado en las aulas de informática, con un 65% de los accesos, seguido muy por detrás por Soraris (21%) y Windows (14%). En la Figura 3 se muestra la evolución de los accesos en parte de los meses del año 2002.

![Uso de los distintos sistemas operativos en las salas del centro de cálculo ETSII](assets/imagen10.png)

**Figura 3:** Uso de los distintos sistemas operativos en las salas del centro de cálculo ETSII

Un factor clave que determinó el aumento de utilización de GNU/Linux y el SL fue el abandono de los servidores Novell, en el año 2001\. Hasta entonces dichos servidores se encargaban de soportar al sistema operativo MS-DOS, que era el utilizado para impartir las asignaturas descritas en el apartado anterior. Las alternativas existentes era migrar hacia Windows o hacia GNU/Linux.

También dentro de la ETSII y otros centros de la ULL existen miembros de Grupo de Usuarios de Linux de Canarias (GULiC) que siempre han prestado su apoyo a iniciativas de promoción del SL.

A raíz de la organización de una fiesta de instalación de GNU/Linux se creó una lista de distribución dentro de la ULL. Hoy en día en esa lista sus miembros discuten sobre SL y organizan iniciativas en apoyo de éste. Entre los proyectos e iniciativas relacionadas con la Universidad [4] en que han colaborado miembros de esta lista destacamos:

* Elaboración de un dossier sobre el apoyo de la Universidad de La Laguna hacia el SL y recogida de firmas.
* Curso y libro CILA: Anualmente se organizan, auspiciados por la Facultad de Matemáticas, unos cursos de Introducción al Linux para Alumnos (CILA). En ese marco se ha elaborado un libro con colaboraciones de toda España.
* Distintas conferencias, talleres, proyecciones, fiestas de instalación y mesas redondas relacionados con el SL.
* Creación de Guachinche::Live CD [9]: una distribución de GNU/Linux que puede arrancar desde el CD-ROM.
* Portal de la futura Oficina del Software Libre (OSL) de la ULL.
* Lebrillo: Web para la gestión de proyectos relacionados con el SL.

El apoyo al SL dentro de la ULL es notable entre sus miembros, como así lo atestigua las mas de 300 firmas recogidas en la primera iniciativa, que pedía a los candidatos a Rector en las elecciones del 2003 que dieran también su apoyo institucional. Es de destacar dentro de dichas firmas el predominio de miembros de la ETSII, donde se encuentran gran parte de los expertos informáticos de la ULL, y por tanto conocedores de lo que el SL significa.

Lamentablemente, y a pesar de las promesas electorales, el apoyo con el que cuenta el SL entre los miembros de la ULL no se ha aún conseguido que sea asumido por las instituciones.

## Migración a software libre

### Antecedentes

Hasta el curso 2000/2001 las prácticas de las asignaturas venían impartiéndose sobre el sistema operativo MS-DOS haciendo uso del los compiladores de la casa Borland: TurboPascal y BorlandPascal, para las asignaturas de primer curso, y BorlandC y TurboC para las de segundo curso. Ello suponía las siguientes dificultades:

* El MS-DOS en la ETSII iba a dejar de mantenerse.
* Borland no se planteaba seguir sacando nuevas versiones de compiladores para MS-DOS, sino aconsejaban pasarse a Delphi o C++Builder bajo entorno Windows.
* La exclusividad de los compiladores usados a una sola plataforma hacía que en posteriores asignaturas el alumno tuviera que aprender otras herramientas de desarrollo.
* Al ser herramientas de pago, si el alumno deseaba trabajar en su casa necesitaba adquirir el producto o trabajar con copias ilegales.

Las opciones que se barajaron era migrar hacia un entorno GNU/Linux o bien hacia un entorno Windows. Además se contaba con la dificultad de que en las aulas de informática habían muchos ordenadores con bajas prestaciones, que bajo MS-DOS y GNU/Linux podrían seguir trabajando, pero que carecían de recursos para la versión de aquellos momentos de Windows (NT workstation). Esto junto al hecho de que con Windows no se resolvían las dos últimas dificultades de la lista anterior y a las ventajas de SL decantaron que los profesores eligieran GNU/Linux como plataforma de trabajo.

La migración en la ETSII arrastró también migraciones en las otras titulaciones, principalmente debido a que compartían profesores y aulas con la ETSII.

### Herramientas elegidas

Las herramientas de trabajo elegidas fueron por tanto:

* GNU/Linux como sistema operativo.
* Compilador Free Pascal [5], para las asignaturas de primer curso, ya que mantenía la compatibilidad con los productos de Borland y podía ejecutarse en el resto de plataformas de la ETSII.
* Compilador GNU gcc (C y C++) para las asignaturas de segundo curso.
* Editor Xemacs [6], debido a su potencia para la edición de programas y su capacidad de trabajar con múltiples lenguajes, herramientas y plataformas.
* Entorno depurador DDD [7], que permitía su uso también con múltiples lenguajes.

### Acciones de apoyo

Para detectar posibles dificultades en la migración durante los finales de lostres últimos cursos se ha distribuido entre los alumnos una encuesta [8] sobre la implantación del nuevo entorno de desarrollo. Entre las principales dificultades detectadas tanto entre alumnos como profesores pudieron destacarse:

* Falta de formación de algunos profesores en dicho entorno de desarrollo.
* Escasa familiarización también en el sistema operativo GNU/Linux, tanto de profesores como de alumnos.
* Dificultades para la instalación y configuración del entorno de trabajo.

Para paliar los efectos de estas dificultades se llevaron a cabo las siguientes acciones:

* Organización de seminarios para profesores: en ellos, los profesores que ya contaban con experiencia en el nuevo entorno de desarrollo adiestraban a los recién llegados y servían como apoyo en las tareas de instalación y configuración de herramientas.
* Organización de cursos de GNU/Linux y fiestas de instalación: en estos cursos y fiesta los propios alumnos de cursos superiores enseñan a sus compañeros recién llegados a la ETSII.
* Refuerzo en el temario de la parte dediacada a la introducción del sistema operativo y su entorno: se incrementó de un 16% a un 20%, aumentando el número de prácticas tuteladas de dos a tres.
* Creación de foros de discusión a través de internet: así se solventan dudas sobre el entorno de trabajo, que son respondidas por los propios alumnos y profesores.
* Insistir en la posibilidad de utilizar las herramientas de desarrollo también bajo el entorno Windows: esto permitía a los alumnos menos avezados la realización de las prácticas en sus casas sin necesidad de instalar GNU/Linux.

### ETSII::Live Guachinche

Otra iniciativa que se ha llevado es conducente a paliar las dificultades que se encuentran los alumnos en la instalación de un entorno informático de trabajo, que incluya las aplicaciones utilizadas para la realización de prácticas. Esta tarea se encuentra agravada por los escasos conocimientos de los alumnos en administración de sistemas informáticos. Para ello en el presente curso se ha distribuido a cada alumno un CD Rom que contiene una distribución de GNU/Linux que denominamos ETSII::Live Guachinche [9]. Entre las características destacables está la inclusión de todas las aplicaciones de SL que se necesitan en el desarrollo de sus asignaturas, y que es posible arrancar dichas aplicaciones sin necesidad realizar ninguna instalación en el disco duro, pudiendo por tanto trabajar con ella en cualquier PC. Además dispone de una utilidad que permite instalarlo en el propio ordenador, con lo que se agiliza su uso.

La creación de esta distribución se ha llevado a cabo por los propios alumnos de cursos superiores de la ETSII, eligiendo las aplicaciones a incluir según las necesidades expresadas por los propios alumnos y los profesores. Durante su desarrollo se han utilizado las herramientas propias de gestión de proyectos en SL [Referencia], participando una gran parte de la comunidad universitaria en proponer sugerencias y validar las versiones previas. Además los propios alumnos y profesores a través de su portal web dan soporte a sus compañeros en todo lo referente a instalación, configuración y uso de este CD.

Esta iniciativa ha tenido muy buena acogida dentro de la ETSII y su entorno, agotándose las 500 copias disponibles en apenas dos días. El foro de soporte almacena unas 70 preguntas y respuestas, actualmente se mantiene una lista donde se recogen sugerencias para futuras versiones.

## Resultados

![Respuestas a la pregunta “¿Cuándo instalaste Linux por primera vez?”](assets/imagen1.png)

**Figura 4:** Respuestas a la pregunta “¿Cuándo instalaste Linux por primera vez?”

En la Figura 4 podemos ver como el número de alumnos que no ha instalado Linux se ha mantenido en torno a un 45%. Desde el curso 2003/2004 esta situación en ya no es tan grave debido a la utilización de Guachinche, que no necesita instalación. Por otro lado el número de alumnos que a comienzos de curso ya tenían instalado Linux se ha incrementado en este último curso.

![Respuestas a la pregunta “Valora los motivos de porqué no has instalado Linux”](assets/imagen3.png)

**Figura 5:** Respuestas a la pregunta “Valora los motivos de porqué no has instalado Linux”

Entre los motivos de por qué los alumnos no instalan Linux, Figura 5, podemos destacar la necesidad de expertos en instalación (A: “No se instalarlo”, C: “No he encontrado a nadie que me eche una mano” e I: “He intentado instalarlo pero no lo he conseguido”). Además, de la respuesta B (“No me atrevo a instalarlo”) se aprecia como los alumnos han ido perdiendo el miedo en el último año a la instalación del Linux, posiblemente debido al aumento de las facilidades para la instalación.

También es de destacar el incremento en el último curso los resultados de la respuesta G (“No creo necesario instalarlo”), creemos que es debido a las nuevas posibilidades de trabajar con Guachinche sin necesidad de instalación.

![Respuestas a la pregunta “Manera habitual en que trabajas las prácticas”](assets/imagen2.png)

**Figura 6:** Respuestas a la pregunta “Manera habitual en que trabajas las prácticas”

En cuanto a la manera de trabajar en el desarrollo de programas, Figura 6, las respuestas A (“Todo en Linux”) y B (“Primero compilo con el Free Pascal para Windows/dos, luego la paso al Free Pascal para Linux”) son las mas ortodoxas, mientras que las restantes (C, D y E) suponen utilizar compiladores que no son el Free Pascal (posiblemente de Borland). Se observa que en este último curso ha aumentado la proporción de alumnos que trabajan únicamente en Linux (hasta un 45%) mientras que los restantes aún han de pasar por Windows al menos en fase de edición.

![Respuestas a la pregunta “Cómo valoras los siguientes aspectos en la utilización del entorno de programación Linux”](assets/imagen4.png)

**Figura 7:** Respuestas a la pregunta “Cómo valoras los siguientes aspectos en la utilización del entorno de programación Linux”

Entre los aspectos mas valorados en del SL (Figura 7) podemos destacar el hecho de su gratuidad (E: “La gran cantidad de herramientas gratuitas existentes” y G: “El que Linux sea totalmente gratuito”). Como menos valorado tenemos la comodidad de uso y su utilidad en la calle (C y F).

![Respuestas a la pregunta “Valoración de los entornos de programación que conozcas”](assets/imagen5.png)

**Figura 8:** Respuestas a la pregunta “Valoración de los entornos de programación que conozcas”

Respecto a la valoración del entorno de programación Linux respecto al de Windows vemos como Linux ha venido ganando popularidad hasta llegar en el último curso a superar a Windows, ver Figura 8.

![Relación entre las respuestas a las preguntas “Manera habitual en que trabajas las prácticas” y “¿Qué nota (posiblemente) obtendrás en prácticas?”](assets/imagen6.png)

**Figura 9:** Relación entre las respuestas a las preguntas “Manera habitual en que trabajas las prácticas” y “¿Qué nota (posiblemente) obtendrás en prácticas?”

Para valorar si la manera de trabajar esta relacionada con la nota final de prácticas esperada se correlacionaron estos dos aspectos. Observándose que dentro del número de alumnos que obtienen notas altas hay mayor proporción de los que trabajan íntegramente en Linux (A), aunque las diferencias no son significativas.

Finalmente para comprobar si la migración ha afectado a los resultados académicos en la Figura 10, y las ya vistas Figuras 1 y 2, se muestran dichos resultados para los cursos desde 1998/1999 hasta 2002/2003 (aún no tenemos los resultados del presente curso). Se observa como apenas se producen ligeras diferencias entre aprobados, suspenso, no presentados con prácticas aptas (NP_y_PrNA) y no presentados con prácticas no aptas (NP_y_PrA).

![Proporcion de notas academicas entre los cursos 1998/1999 y 2002/2003](assets/imagen7.png)

**Figura 10:** Proporcion de notas academicas entre los cursos 1998/1999 y 2002/2003

## Conclusiones

A pesar de las dificultades planteadas en un inicio, podemos considerar como un éxito la migración efectuada. Hemos logrado avanzar hacia un entorno mucho mas homogéneo y útil en los distintos cursos de las titulaciones. También la Universidad y los propios alumnos han conseguido un ahorro considerable en gastos de licencias de software.

Las sociedad se encuentra aún mas retrasada que nosotros en la implantación de SL, pero como bien dijo Edsger Dijkstra, _no es tarea de la Universidad brindar lo que la sociedad pide, sino lo que la sociedad necesita_.

## Referencias

1. [http://www.etsii.ull.es/](http://www.etsii.ull.es/)
* [http://www.etsii.ull.es/~mtp1/](http://www.etsii.ull.es/~mtp1/)
* [http://osl.ull.es/Members/pgb/ijcticdu/oodocument_view](http://osl.ull.es/Members/pgb/ijcticdu/oodocument_view)
* [http://osl.ull.es/Proyectos/](http://osl.ull.es/Proyectos/)
* [http://www.freepascal.org/](http://www.freepascal.org/)
* [http://www.xemacs.org/](http://www.xemacs.org/)
* [http://www.gnu.org/software/ddd/](http://www.gnu.org/software/ddd/)
* [http://osl.ull.es/Members/pgb/encuestalinux/oodocument_view](http://osl.ull.es/Members/pgb/encuestalinux/oodocument_view)
* [http://guachinche.csi.ull.es/](http://guachinche.csi.ull.es/)


## Migración a software libre

### Antecedentes {#antecedentes}

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


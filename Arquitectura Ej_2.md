# Arquitectura Ej_2

<p>La construcción de un compilador involucra la división del proceso en una serie de fases que
variará con su complejidad. Generalmente estas fases se agrupan en dos tareas: el análisis
del programa fuente y la síntesis del programa objeto.</p>

<p>Análisis: Se trata de la comprobación de la corrección del programa fuente, e incluye las
fases correspondientes al análisis léxico (que consiste en la descomposición del programa
fuente en componentes léxicos), análisis sintáctico (agrupación de los componentes léxicos
en frases gramaticales) y análisis semántico (comprobación de la validez semántica de las
sentencias aceptadas en la fase de análisis sintáctico).</p>

<p>Síntesis: Su objetivo es la generación de la salida expresada en el lenguaje objeto y suele
estar formado por una o varias combinaciones de fases de generación de código
(normalmente se trata de código intermedio o de código objeto) y de optimización de
código (en las que se busca obtener un código lo más eficiente posible).</p>


<p>Desarrolle un modelo arquitectónico para un nuevo compilador del lenguaje Pascal que se
pretende realizar de manera que sea factible compilar código para diferentes plataformas.
Especifique qué estilo y/o mezcla de estilos usaría. Considere que el compilador debe 
proveer también una GUI para facilitar el uso del mismo, que permita editar y compilar los
programas. 
</p>

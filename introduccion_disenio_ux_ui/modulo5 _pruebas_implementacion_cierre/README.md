# Módulo 5 | Pruebas e Implementación - Cierre

Testing para comprobar las hipotesis y los contenidos.

---


## Contraste y Legibilidad


---


## Design system (Sistema de diseño )


Un Design System o Sistema de Diseño es un **lenguaje** centralizado que consta de un conjunto de patrones perceptuales y funcionales que están interconectados, traducidos en código y guiados por normas específicas para que se utilicen de manera coherente y eficaz sin perder el objetivo del producto digital. <br>

Se definen ciertos valores como los colores, las tipografías, las iconografías, son los componentes que se van creando en Software, como Figma, para que luego la compartirlo con el equipo de Desarrollo tengan todo para poder maquetar y programar (que puedan codear). <br>
Tienen las mismas estructuras, depende del diseñador como lo categorice, pero siempre son: tipografías, tamaños, colores, iconos, botones primarios / secundarios / de texto / con links, el tamaño de las imagenes, grilla que se ocupa, el ancho de columnas dentro de la grilla, cálculos con unidad minima de pixeles. <br>
Está relacionado con la ideantidad de la marca, los valores, el tono de color, como se expresan, la paleta de palabra, etc. <br>


Una manera de crear un Design System es basándonos en el concepto de **Atomic Design**. <br>
Este método, inspirado en los principios de la química, fue ideado por Brad Frost y nos permite construir productos complejos. <br>
Hacer una construcción desde lo mínimo hasta la maqueta que enviamos a desarrollo. Se piensan los componentes mínimo por separado (sería el átomo) que se combinan para crear pequeñas unidades de diseño (las moléculas). Entonces crea un componente más complejo formado por distintos componentes. <br>
Y luego se los ubica en la esructura general: donde van? qué lugar ocupan? Le sumamos el texto, todo el entorno para hacer todo el concepto, se suman en el template.<br>
Por ejemplo los puntitos de abajo del caruesel nos indican que hay más imagenes, o el menu hamburguesa nos avisa que hya un menu. Hay un texto, hay una imagen, las fotos reales, esta la idea de marca, con sus colores. <br>


---


## Introducción: Pruebas Ux (Ux Test)


El diseño Ux es la práctica del diseño que **se centra en el usuario y la usabilidad de
un producto para ofrecer la experiencia más satisfactoria**. <br>
Si bien algunos aspectos del diseño centrado en el usuario pueden ser intuitivos o depender de las mejores prácticas de UX, brindar una **excelente experiencia de usuario**
requiere una comprensión profunda de las **necesidades**, **objetivos** y **puntos
débiles del usuario**. Descubrir estos conocimientos requiere de pruebas UX. <br>
Para que la prueba de UX sea efectiva, debe involucrar a las personas más
importantes: sus **usuarios/clientes**. <br>
Decidir qué aspectos del producto probar y cómo es una gran tarea. <br>
Hay que definir el prototipo que se usa, cómo se va a hacer ese testeo. <br>


Un test de usuario es una **técnica o metodología de investigación** que se utiliza en el diseño centrado en el usuario y tiene como objetivo **evaluar un producto digital** tanto en una fase de diseño desde cero como en una fase de optimización. <br>



### ¿Qué son las Pruebas de Usabilidad?


-La actividad de **evaluar un producto o servicio probándolo con usuarios representativos**. <br>
Normalmente, durante una prueba, los participantes tratarán de completar tareas típicas mientras los observadores observan, escuchan y toman notas. <br>
El objetivo es identificar cualquier problema de usabilidad, recopilar datos cualitativos y cuantitativos y determinar la satisfacción del participante con el producto.-<br>
**Usability.gov** <br>


Uno de los puntos más importantes: llevar mucha información cualitativa y cuantitativa, para poder tomar decisiones. <br>


-La práctica de **probar lo fácil que un diseño es usar en un grupo de usuarios representativos**. <br>
Por lo general, implica **observar a los usuarios** cuando intentan **completar las tareas** y pueden realizarse para diferentes tipos de diseños, desde interfaces de usuario hasta productos físicos.<br>
Por lo general se realizan de manera constante, desde el desarrollo inicial hasta la liberación de un producto.- <br>
**Interaction Design Foundation** <br>


En esta etapa se tratan de hacer anotaciones y observar. Las pruebas no están atadas a productos digitales, puede ser algo físico, se desarrolla para todo, en este curso nos centramos a los productos digitales y sitios webs.<br>
Son empresas grandes, con bastantes recursos, que pueden probar los productos. <br>
Lo que si es importante al menos realizar las pruebas del producto final o hacer prototipos rápidos para poder testear. <br>



### ¿Por qué son importantes las Pruebas Ux?


   * Se pueden detectar problemas potenciales para ser corregidos antes de que el producto sea lanzado y por tanto, ahorrar tiempos y costos.
   
   * Nos ayudan a obtener insights sobre cómo la gente usa o usaría el producto para un fin determinado. Detectamos muchas cosas que nos pueden ser disparadores para uuna nueva función, una nueva estética, nuevas palabras.
   
   * Nos da una idea de qué errores son los más frecuentes para crear mecanismos de recuperación, o diseñar para minimizarlos. Hacer más eficiente nuestro producto.
   
   * Nos ayuda a entender cuánto hemos mejorado en términos de facilidad de uso, curva de aprendizaje, satisfacción, eficiencia, efectividad entre una versión y otra. Vemos si al usuario le cuesta o no relaizar una tarea, vemos cuán satisfecho termina, si es eficiente el nuevo producto. Se realizan las pruebbas A/B. 
   
   * Nos ayudan para generar un diagnóstico antes de tomar decisiones de rediseño. Se pueden hacer pequeños cambios.
   
   * Los hallazgos nos ayudan a compartir argumentos con stakeholders o personas involucradas en el diseño y desarrollo para la toma de decisiones. Si hay algo detectado en la prueba que vale la pena comentar se lo hacemos saber, damos un insight basado en pruebas.
   
   * Reducen el riesgo a fracasar con el producto usado.
   
   * Hace coincidir las decisiones de negocios con el uso en el mundo real.
   
   * Ayudan a entender los comportamientos de los usuarios, no sus actitudes. A veces el comportamiento del usuario no es exactamente la actitud que tiene, o lo que dice no lo representa, ppor eso hay que ver su expresión, su movimiento, para saber que es lo que siente. A veces responden cuestionarios o tienen entrevistas.




### Pruebas con usuarios en 10 pasos:

No hay una metodología pautada, hay muchas formas de llevarlo a cabo. Sugerimos estos pasos que cubren varios aspectos. <br>
Se pueden hacer hasta test remotos, con cámaras que graben cómo se comporta el dedo, qué recorridos hace, si surgen dudas, y otra cámara va a grabar el rostro para detectar las emosiones. <br>


**1. Definir los objetivos**  <br>

Es necesario **tener claro lo que queremos lograr con esta técnica** para poder enfocar los siguientes pasos hacia esos objetivos.<br>
De lo contrario, podemos llevar a cabo tests que no nos aporten los resultados necesarios para mejorar nuestro producto. <br>
Antes de hacer cualquier cosa, debemos tener claro que buscamos, que averiguamos. <br>


**2. Decidir el tipo de test**  <br>

Existen diferentes modalidades de tests con usuarios. <br>
En este punto, debemos decidir cómo va a ser nuestro test, en función de lo que pretendemos alcanzar, nuestros recursos y el tipo de usuarios que van a participar, entre otras cosas. <br>


**3. Disponer del producto a testar**  <br>

Dependiendo de lo que estemos buscando validar, de lo que queramos obtener y de los recursos con los que contemos, será mejor llevar a cabo la prueba con un tipo de producto u otro. <br>
Dependiendo de los recursos que tenemos vemos que evaluamos, siempre teniendo algo ya desarrollodo, sino no se puede testear. <br>



### Características y tipos de pruebas de usabilidad


### Formativas


Las pruebas formativas son aquellas en las que se está constantemente **revisando el producto o servicio para hacer ajustes que mejoren el resultado final**. <br>
El objetivo final es **probar todo antes de sacar a la luz**. <br>
Las preguntas que se responden en este tipo de evaluación son de carácter cualitativo, lo que nos permite conocer qué es lo que está pasando por la mente del participante durante las tareas y encontrar problemas de usabilidad: <br>

   * ¿ Cuáles son los principales problemas que evitan que el usuario complete su objetivo ?
   * ¿ Qué elementos o aspectos hacen sentir frustrado al usuario ?
   * ¿ Cuáles son los errores más frecuentes ?
   * ¿ Qué mejoras hubo entre una versión de diseño previa y la actual ?



### Sumativas

Las pruebas sumativas, **prueban el producto ya cuando fue lanzado**. <br>
Cuando hablamos de sumativas, hablamos de **medir el desempeño de algo**: tiempo, precisión, errores, etc (cuantitativo), para ser analizado más tarde con la totalidad de las pruebas realizadas. <br>
Puede medir errores, se mide con mejor precisión, se ven estadísticas. <br>

   * ¿ Se cumplieron los objetivos de usabilidad planteados ?
   * ¿ Cuál es la usabilidad general del producto ?
   * ¿ Cómo se compara nuestro producto frente al de la competencia ?



## Presenciales: Laboratorio o Guerrilla

Son pruebas presenciales.<br>
Las pruebas en laboratorio implican como su nombre lo dice, **estar en un set formal** en donde a través de un espejo (como si fuese la cámara gesell) **los stakeholders pueden presenciar en vivo lo que va aconteciendo** sin que el participante se sienta invadido. <br>
Estan para participar, para escuchar a los usuarios, ya que no son muy empáticos con el usuario, entonces no lo invaden. Y siempre todo punto de vista suma. <br>

Una técnica menos formal, práctica y que en definitiva no requiere mucho dinero, es la de **“guerrilla”**, o bien, conocida como **prueba de campo** o que puedes realizar en **espacio públicos** (como un café) o en **contextos reales** (ej. un supermercado) a cambio de alguna cortesía. <br>
Las pruebas de guerrilla suelen ser un recurso excelente para quién quiere **detectar problemas de usabilidad en etapas tempranas o a grandes rasgos**. <br>
Pueden tener menores costos, se pueden citar en espacios públicos o usar contexto real para usar el producto. <br>
No son tan preparadas, elaboradas. <br>



## Remotas: Moderadas o Automatizadas

En las moderadas hay una persona del otro lado pidiendo al usuario que realice una serie de tareas, puede ir guiando la sesión conforme el participante responde y puede hacer preguntas abiertas para fomentar la participación o recolectar más datos.<br>

Las automatizadas permiten recolectar pruebas donde los usuarios ponen su cámara para grabar su cara y se les pide acceso al micrófono para obtener voz. <br>
Además, los participantes pueden realizar la prueba con la ayuda de algún software especial que va pidiendo las tareas.<br>
Cuando el tamaño de la muestra es grande, es un excelente recurso para obtener datos cuantitativos. <br>
Un ejemplo puede ser un Google Form. <br>



**4. Identificar los tipos de perfiles de usuario**  <br>

Para ello, deberemos de tener en cuenta **múltiples características de nuestros usuarios**, como el tipo y nivel de uso del producto, la edad, el género (depende del producto, en algunos casos puede ser determinante) y su destreza tecnológica, entre otras. Tenemos que ver si queremos tener informaciónde un usuario de nuestro producto o de alguien que ni lo conoce, todo va a ir variando.<br>

Puede darse el caso de **estar buscando una muestra representativa de los potenciales usuarios del producto** para evitar obtener información sesgada. Algo grande, de muhcas personas, tener buenas métricas.<br>

Así como también podemos encontrarnos con situaciones en las que sólo queramos obtener **información de un tipo de perfil concreto**, por lo que tendremos que encargarnos de identificar bien a este perfil para poder reclutarlo y obtener la información que deseamos. Buecamos pocas personas, que respondan a nuestro perfil, van a ser los buyer personas, acáa nos centramos en reclutarlo<br>



**5. Diseñar las tareas y cuestiones**  <br>

Para empezar, hay que **detectar los puntos clave** acerca de los que deseamos obtener información y formular una **tarea** sobre ello. <br>

Es importante que las tareas estén **bien formuladas**, **sean realistas** y que **sean fácilmente comprensibles por lo usuarios**, pero no den pistas acerca de cómo se resuelve la tarea. <br>

También debemos de tener en cuenta a la hora de plantear las tareas del test, que no deben de ser excesivas para no alargar demasiado el test. Deberemos de tener en cuenta la complejidad de las tareas y el tiempo necesario para resolver cada una de ellas. <br>
Deben ser cortos, entretenidos, que el usuario se sienta cómodo, porque sino la persona pierde la atención..<br>

Por otro lado, en esta fase también debemos plantear las preguntas que queremos formular a los usuarios, a modo entrevista o cuestionario, tanto antes, como durante y después del test. <br>
¿ Cómo invito al usuario ? ¿Cómo lo recibo ? ¿Dónde lo recibo ? Si es entrevista, preparo todo, no hago preguntas cerradas, lo dejo hablar. <br>



**6. Seleccionar y captar a los usuarios**  <br>

Una vez que tenemos todo el plan del test definido y los perfiles con los que lo queremos realizar, es el momento de **determinar el número de usuarios para proceder a su captación**. <br>

Hay estudios que demuestran que **5 participantes revelan el 85% de los problemas de usabilidad** del producto que estamos testando. A partir de ahí, la cantidad de insights obtenidos crece muy levemente con cada usuario adicional. <br>
Esto igual debende de la prueba, si es que necesitamos una mayor muestra. <br>

Por supuesto, el número de participantes dependerá del producto que vamos a testar y de la cantidad de perfiles diversos con los que vayamos a contar. <br>



**7. Preparar el espacio y los materiales**  <br>

En este punto, lo primero que debemos hacer es escoger la **herramienta** con la que vamos a realizar los tests y registrar toda la información obtenida. <br>

Por otro lado, debemos preparar el **espacio** en el que vamos a llevar a cabo los tests: un espacio libre de ruidos en el que se encontrarán el usuario y el moderador del test. También necesitaremos contar con un espacio para el observador que se encargará de registrar la información que está viendo en tiempo real. <br>

Ambos espacios tendrán que estar equipados con todos los **elementos necesarios para cada tipo de test**: ordenador, móvil, cámara de vídeo, etc. <br>



**8. Elaborar una prueba piloto**  <br>

Antes de lanzar el test, es necesario que hagamos una **prueba piloto para comprobar que todo funciona correctamente** y, en su defecto, **poder corregir cualquier incidencia**. <br>
Por el contrario, si se produce cualquier tipo de problema durante la realización de los tests reales, los resultados pueden verse afectados. <br>
Esta prueba piloto la tendremos que realizar con una o dos personas ajenas al proyecto, para simular una situación lo más realista posible.<br>
Se hace una prueba del testeo, se ve que los microfonos funcionen, que esté todo preparado, que no falte nada. <br>



### Pruebas A/ B (A/B Testing)

La prueba A / B es un método para comparar dos versiones de una página web o aplicación entre sí para determinar cuál funciona mejor. La prueba AB es esencialmente un experimento en el que se muestran dos versiones de una página o aplicación a los usuarios de forma aleatoria y se utiliza un análisis estadístico para determinar qué variación funciona mejor para un objetivo de conversión determinado. <br>

Las pruebas eliminan las conjeturas y permiten decisiones basadas en datos que cambian las conversaciones comerciales de "pensamos" a "sabemos". Al medir el impacto que los cambios tienen en sus métricas, puede asegurarse de que cada cambio produzca resultados positivos. <br>

Se ve qué tan determinante es, como por ejemplo dónde ubico o con qué color tengo un Call to action, para que sea más efectivo, le ponemos una palabra más lamativa, cambiamos el tamaño, o el color y así nos aumentan las ventas. <br>



### ¿Cómo funcionan Pruebas A/B?

Se testean dos opciones para ver que funciona mejor. Se pueden testear un botón, donde va un banner, por ejemplo. <br>

Este método consiste en desarrollar dos versiones de un mismo elemento que vamos a lanzar al mercado (por ejemplo, un botón de CTA azul y uno amarillo), y luego utilizar las métricas de cada variación para evaluar cuál funciona mejor. <br>

En una prueba A / B, toma una página web o la pantalla de una aplicación y la modifica para crear una segunda versión de la misma página. La versión A puede ser la que se esté utilizando en un momento determinado (control), mientras que la versión B se modifica en algún aspecto concreto (variante). <br>

Este cambio puede ser tan simple como un solo título o botón, o ser un rediseño completo de la página. Luego, a la mitad de su tráfico se le muestra la versión original de la página (conocida como el control) y a la mitad se le muestra la versión modificada de la página (la variación). Asi el usuario ve las modificaciones y ve qué es lo que prefiere, que lo plasma en un questionario.<br>

Proceso de prueba A / B : **recopilar datos** que nos permitan generar una **hipótesis** para poder **crear varaibles**. **Ejecutamos la prueba** y al final **analizamos los resultados** apoyándonos en software de testeos.<br>


**9. Llevar a cabo el test**  <br>

Cuando llegue cada uno de los usuarios, es importante **transmitirle tranquilidad** y **explicarle todo con detalle**. Es probable que el usuario se encuentre algo nervioso ya que no sabe a lo que se enfrenta, por ello es importante que le hagamos sentir cómodo y le repitamos las veces que hagan falta que no les estamos evaluando a él/ella, sino al producto. <br>

Un ejemplo es el de los testers de viedeo juegos. Pero en otras ocasiones los test se hacen con personas que nunca participaron, entonces hay que hacerlos sentir cómodos, que no los evaluamos a ellos, sino el producto. <br>


Durante la ejecución del test, es importante que el observador registre el máximo de información posible, aunque la sesión se esté grabando y podamos consultar la información posteriormente. En general, no sólo debemos prestar atención a lo que el usuario hace y dice, sino también a sus expresiones y gestos, que nos revelarán mucha información acerca de cómo se siente en cada momento. <br>
Prestar atención al usuario, segirlo. <br>

Puede resultar muy interesante que esté presente algún miembro responsable del producto para que puedan ver de primera mano cómo los usuarios manejan su producto y los problemas que se encuentran <br>


**10. Analizar los resultados y proponer mejoras**  <br>

El concepto de usabilidad de un sistema considera que hay tres dimensiones principales que pueden medirse: **eficacia**, **eficiencia** y **satisfacción**. <br>
Por otra parte, la definición de experiencia de usuario señala que ésta depende de las percepciones y respuestas de los usuarios antes, durante y después del uso, lo cual amplía el abanico de variables psicológicas y comportamentales que pueden medirse<br>


**Eficacia**: ¿Pueden los usuarios conseguir su objetivo con el sitio web o la aplicación? <br>
Para medir la eficacia es necesario definir qué significa éxito y fracaso para el usuario en una tarea determinada. <br>
Hay tareas que tienen un fin muy claro (por ejemplo, reservar un vuelo concreto en la página web de una aerolínea) mientras que otras tienen un fin más abierto (por ejemplo, localizar el horario y precio más ajustados a nuestras necesidades). <br>

**Ejemplo** <br>
Test de usabilidad en el que participan 10 usuarios, cuya tarea es tratar de reservar un vuelo en dos aerolíneas diferentes (A y B). Una práctica común es asignar un 1 cuando el usuario completa la tarea, 0,5 cuando lo hace pero de manera incompleta, y 0 cuando no consigue finalizar la tarea. A partir de esta información se puede construir la métrica Tasa de éxito, como una media de puntuaciones de todos los participantes. <br>


**Eficiencia**: La eficiencia en el uso de un producto digital se refiere a **cuánto esfuerzo mental es necesario para realizar una tarea**. Se suelen medir los tiempos.<br>

**Ejemplo**:<br>
Volviendo al caso anterior, imaginemos que dos sitios web de aerolíneas tienen una tasa de éxito del 100% (todos los usuarios consiguen reservar el vuelo) pero a los usuarios, uno de los sitios les ha parecido mucho más difícil que el otro. <br>
¿Cómo podríamos medir la eficiencia con la que los usuarios pueden realizar su tarea en ambos sitios?<br>
Una posibilidad es **medir el tiempo** que tardan en hacer cada una de las tareas. <br>
Imaginemos que definimos un tiempo máximo de 2 minutos para realizar la tarea Existen otras posibilidades para medir la eficiencia, como son registrar el número de clicks que debe realizar el usuario para llegar a su objetivo, o emplear un cuestionario de esfuerzo cognitivo percibido. <br>


**Satisfacción** : En la mayoría de los casos, la satisfacción de los usuarios depende principalmente de **que puedan cumplir su objetivo con el mínimo esfuerzo**. <br>
En este sentido, si la eficacia y la eficiencia de un sistema es alta, también lo será su satisfacción.<br>
Pero si entendemos la satisfacción en un sentido más amplio, también va a depender de otros aspectos que influyen en la experiencia de usuario, como la calidad estética del sitio web o la aplicación. La identidad<br>
La manera más directa de evaluar la satisfacción es mediante el uso de cuestionarios de usabilidad percibida y experiencia de usuario. <br>

**Ejemplo** : La evaluación puede consistir en una sola pregunta que cada usuario responde en una escala del 1 al 10. <br>
¿Estoy satisfecho con el proceso de reserva? <br>
(1 – Totalmente en desacuerdo; 10 – Totalmente de acuerdo). <br>
HAciendolo en un gráfico de barras se ve bien si hay mucha gente la que está conforme o no. <br>

---

## Concepto de iteración

---

## Trabajando con desarrolladores



---

## Cierre del curso con una puesta en común sobre todo el proceso de diseño de un producto digital

---

## Caso de estudio para ver en la práctica todo lo aprendido


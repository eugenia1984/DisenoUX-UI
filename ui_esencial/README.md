# :book: Diseño de Interfaz (UI) esencial, curso de LinkedIn Learnign de Lucía Garza Ortegón

Amplía tus conocimientos sobre la disciplina de interfaz de usuario o UI. Identifica los factores importantes en el diseño e interacción con los productos y analiza e investiga la relación entre las características del producto y sus usuarios para generar así la mejor facilidad de uso. En definitiva, empieza a crear soluciones verdaderamente centradas en el usuario y sus necesidades.

---

## :star: Principios del diseño de interfaz

### ¿Que es el diseño de interfaz y en que se enfoca?

Desarrollar interfeces o elementos visuales que facilitan la interaccion entre el usuario y el servicio, s esentra en el usuario y la interaccion que tiene con el producto.

El producto debe ser con interaccion somoda y amigable.

Debe tener un **enfoque funcional** (flujo, navegacion, accesibilidad) y **enfoque estetico**(imagen, solor, fuente).

El producto debe ser agradable a la vista y facil de navegar.

debe tener estructura y jerarquis claras, debe ser facil la navegacion.

Las fuentes, el color y el contraste debe ayuda a la facil legibilidad.

En cambio en un **mal diseño de interfaz** faltan pistas de guia para que el usuario sepa donde o como navegar a  traves del producto, que no tenga jerarquia visual (poco claro) y fuentes erroneas, poco contraste.

Tanto **funcion** como **estetica** trabajan a la par para **mejorar la interacción entre el usuario y el dispositivo**.



### Los beneficios de una buena interfaz de usuario

El usuario interactua de manera natural con el producto, sin importar si se conecta por mobil, tablet o destktop.

Las etiquetas deben ser claras, para que los usarios encuentren lo que buscan facilmente.

Si hay buena jerarquia, y pistas visuales que los guien, navegan sin problemas.

En cada accion del usuario debe haber una reaccion, como cuando presiona un boton, o una pestaña que se abre.

El diseño de interfaz depende del producto y el hardware que cuenta con caracteristicas limitantes (puntos de interaccion, tamaño de pantalla, por ejemplo).

Personalidad del producto por medio de fuentes tipograficas, imagenes, iconos, paleta de colores, etc.


### Planeacion previa para un buen diseño de interfaz


Definir del producto:

- caracteristicas: hardware y software, tamaño de pantalla, interacicones esperadas por el usuario.

- funciones

- marca o referencia visual, su estilo visual, paleta de colores, fuentes tipograficas, estilos, una guia de estilo de la marca, etc.

Es importante la comunicacion con el cliente, posibles usuarios y el equipo de desarrollo para los entregables.

---

## :star: Practicas de buen diseño UI

### El diseño y su orientacion a la resolucion de problemas

Resuelve problemas ademas de crear imagenes, tiene la base de como interactua el usuario, que busca, para que, que desea resolver, etc; por esto es importante saber el comportamiento dle usuario, las predicciones (su navegacion, darle pistas visuales, accion-reaccion).

Preguntas claves:

- ¿cual es el proposito del diseño?

- ¿como debe ser recibido por el usuario?

- ¿por que es importante para el cliente y el usuario?


### Balance entre forma y funcion del producto

La **forma** se refiere a como se ve el producto (jerarquia visual, estetica, diseño) y la **funcion** se refiere a la utilidad dle producto, para que es (se compone derequerimientos, contenido, metas)

"La forma sigue a la funcion" - Lois Sullivan. Se enfoca en un diseño en base a la funcion, peor es una solucion limitada. Tiene en cuenta la funcion, recopila los requerimientos del producto a realizar, pero en cuanto a la forma, determina la estetica del UI basada solo en estos requerimientos, por lo que el resultado es que cumple con los requerimientos sin tomar en cuenta al usuario.

Debe ser util y usable (experiencia de usario).


La forma sigue a la funcion y sigue al usuario, ambas trabajan juntas,

### Desarrollo de producto con enfoque en el usuario


Es importante enfocarse en los resultados, entender al usuario y sus espectativas al usar la interfaz, debe cumplir sus metas.

Hay que entender las diferencias y similitudes entre el sistema y el modelo mental del usuario.

El modelo creado por el equipo de sistemas, se llama **modelo representativo**, dichos modelos mientras mas se asimilen al **modelo mental**(la vision del usaurio) van a ser mejores, y mientras mas se acerquen al **modelo de implementacion** (refleja la tecnologia) van a ser peores porque se alejan dle modelo del usaurio.

Los usuarios no quieren saber a fondo la funcinalidad, se centran en su experiencia.

Hay que conocer el elemento visual que los destaca de la diferencia, es lo que le da el valor agregado.


### Implementacion de la reticula en la composicion

Reticula (grid) tiene filas y columna que se separa en modulos, para organizar el contenido de manera armonica y jerarquica.

Beneficios:

- consistencia, hay elementos standar reutilizables, como : margenes entre elementos, altura, espacio entre botones

- claridad y coherencia, usando simetria, proximidad y continuidad, ademas de jerarquia y ritmo. Se ve visualmente coherente el contenido.

- simplifica el proceso de diseño

- facilita el desarrollo del producto, hay componentes reutilizables

Sistema de reticula en base a 8 puntos:

8 x 2

8 x 8

8 x 16

Deja un espacio de separacion de 16px

Tienen 64px entre el primer espacio y la columna, despues si quiero usar dos reticulas tomo 128px. Todo es multiplo de 8.

Las reticulas cambian acorde a si es...

... movil con 4 - 8 columnas y un margen de 16px

... tablet con 8 - 12 columnas y un margen de 24px

... desktop 12-16-18-24 columnas y un margen de 24px


---

## :star: Arquitectura de informacion para UI

### Principios de la arquitectura de informacion

La informacion que se organiza, categoriza y se le da estructura logica y facil de entender. Si hay concordancia entre los modelos de implementacion y los modelos mentales (de los usuarios). Y asi tendremos una interfaz de usuario de alta usabilidad.


### Estructura y jerarquia en UI

La estructura divide el contenido en secciones o categorias, agrupando elementos de acuerdo a caracteristicas similares.

La jerarquia ordena el contenido de acuerdo a su importancia, crea jerarquia visual, como por ejemplo el titulo que tiene una fuente distinta al del texto.

Hay varias formas de generar jerarquia visual:

- por tamaño, los mas grandes llaman la atencion, como titulo principal, subtitulo y texto

- contraste, cuando un color genera impacto

- proximidad, separar y agrupar elementos


### Principios de AI: objetos y opiniones

El contenido es un organismo vivio, tiene...

... un **tiempo de vida**, hay que ver si es un contenido estatico (como por ejemplo un domicilio) y un contenido que cambie.

... un **comportamiento** ¿como reaccionan ante el contenido?

... **atributos** ¿cuales son sus caracteristica? Cada objeto tiene sus atributos que lo identifican.

Hay opciones:

- productos con opciones significativos (usar nombre claros)

- el rango de opciones presentadas se enfoca en una tarea (como el menu de opciones)

- mayor esfuerzo congnitivo - mayor ansiedad


### Principios de AI: ejemplos y divulgacion

Hay que crear un balance entre las pistas que lo guian y la informacion.


Ejemplos:

- categorias o secciones, de un menu en el nav bar

- palabras clave, imagenes o iconos representativos

- identificar contenido en relacion a categorias del producto


Divulgacion:

- muestra solo la informacionnecesaria, da una idea

- el usuario puede optar por desplegar mas informacion, como en los acordeones, o cuando haces click en el icono + y se despliega una card.

- a menor ecantidad de informacion desplegada, menor esfuerzo congnitivo (si tiene mucha informacion se pierde y se va)


#### Principios de AI: clasificacion multiple y navegacion

Clasificacion multiple:

- navegacion de contenido a partir de varios puntos de inicio

- pistas que señalen puntos clave de navegacion

Se enfoca en la manera que el usuario navega a traves del sitio, que recorrido hace, si usa la parte de busqueda.

Navegacion enfocada:

- consistencia entre elementos que forman un menu

- menu se define por si contenido

- menu no se define por su ubicacion

- se puede utilizar manus secundarios


### Principios de AI: puertas de fachada y crecimiento

Puerta de fachada: 

- el usuario accede al producto desde cualquier punto externo

- cada seccion de producto debe ser correctamente etiquetada (pista visual como titulo de seccion) 

- seccion de navegacion general presenta a traves del producto

Un ejemplo es el buscador para acceder a cualquier parte del sitio.

Crecimiento: 

- como va a ir creciendo en el tiempo el contenido

- etiquetar contenido y secciones de producto

- estructura definida

- jerarquia visual y de estructura clara.

Por ejemplo un producto tiene 2 secciones principales y cada una tiene sus subsecciones

---

## :star: Manejo y organización del contenido


### La importancia de la organizacion: etiquetas y jerarquia

Etiquetas:

- contenido etiquetado claramente, que sea legible y facil de entender, no es igual como se ve un titulo, que un boton o un buscador.

- la jerarquia define la estructura del contenido.

- una estructura clara fomenta la navegacion, hace placentera la experiencia de usuario.

analisis de contenido -> definicion de jerarquia de contenido -> etiquetar secciones de contenido -> analisis de estructura de contenido


### La importancia de la organizacion: navegacion y busquedas

El usuario debe poder navegar comodamente y en forma agradable.

**navegacion** -> como el usuario de mueve a traves del contenido

**wayfinding** -> comunica al usuario en donde esta

**wireframing** -> combina ambar para desplegar informacion

Busqueda:

- la manera de encontrar informacion

- fundamental para productos con contenido dinamico

- importante conocer las caracteristicas de la informacion


Al realizar una busqueda, ve los resultados que deben poder ordenarse por relevancia, fecha, seccion, etc

El contenido debe contar con una estructura definida

Los puntos de navegacion deben ser definidos y guiar al usuario

Se puede maquetar un flujo de producto para confirmar su navegacion

Se puede agregar elementos de wayfinding en cada seccion


### Modelos de contenido: single page y flat

**single page** -> una sola pagina con todo el contenido, puede ser corta o lasga con scroll, de tener scroll es necesario un menu para llevarnos a una seccion. Es para paginas promocionales.

**flat** -> todas las paginas o secciones estan en el mismo nivel, se utilizan para pequeños sitios webs.

un modelo de estructura organiza el contenido de producto, cada producto es diferente, cuenta con distintas caracteristicas y necesidades.

El contenido dicta el modelo a utilizar, si hay poco contenido va a ser una single page.

Single Page es util para contenido con un solo proposito



### Modelos de contenido: index y daisy


**indice** -> seccion principal y subsecicones. Un indice o menu en cada seccion. Se puede expandir de acuerdo la contenido. Hay una pagina principal de inicio.

**daisy**-> procesos que inician y terminan en la misma seccion, se regresa al origen al completar los pasos. Un sitio de correo electronico, donde siempre vuelve a la bandeja de entrada.


### Modelos de contenido: jerarquias estricta y multidimensional

Lidian con más informacion, porque la pueden separa en subsecciones.

**jerarquia estricta** -> solo se llega a subsecicones a partir de la pagina padre. Obliga a que el usuario siga un proceso especifico. Es popular en plataformas educativas.

**jerarquia multidimensional** ->jerarquia que coexisten, se puede navegar de una seccion a otra, popular en sitios de ventas.


---

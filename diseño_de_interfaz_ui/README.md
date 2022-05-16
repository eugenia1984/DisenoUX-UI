# :book: Diseño de Interfaz (UI) Avanzado con Desire Marron Carmona (LinkedIn Learning)

La interfaz de usuario es el espacio donde se producen las interacciones entre seres humanos y máquinas. Es de vital importancia, pues supondrá el éxito o fracaso en la usabilidad de la solución. Durante el curso, aprenderás con ejemplos prácticos cómo se configuran los sistemas de diseño, qué son los componentes de diseño, sus principios y guías, entre otros conceptos imprescindibles a la hora de construir interfaces que cumplan con las expectativas de los usuarios y usuarias más exigentes en productos web o aplicaciones móviles.


---

## :star: Breve presentacion del diseño de interfaces

### El rol del diseñador de interfaces (UI)

Es un rol clave en el proceso de creacion y composicion de interfaces visuales, ya sea para productos digitales, productos graficos y en cualquier ambito del diseño para web y aplicaciones.

### Diferencia entre UI y UX

**UX** -> recolecta informacion, crea una audiencia, busca publico que de feedback del producto, construye la arquitectura de informacion

UX destaca en el ambito del ana;isis, recoleccion e investigacion de informacion util y diversa

**UI** -> valida y contruye la interfaz, contruye una interfaz util y accesible, crea componentes reutilizables.

UI destaca mucho en comunicacion visual, accesibilidad, usabilidad y composicion visual.

---

## :star: Los principios Gestalt en diseño UI

Todo lo que tenga relacion con la comunicacion entre personas usuarias tiene relacion tambien con la propia psicologia. En ambitos como experiencia de usuario, diseño o composicion de interfaces graficas, la psicologia, y en concreto los principios psicologicos sobre actitudes y personalidades de las personas, juegan un papel primordial.

La psicologia Gestalt se basa en una corriente psicologica que surgio en Alemania en el siglo XX, impulsada por Max Wertheimer, Wolfgang Kohler, Hurt Koffka y Kur Lewin. **Gestalt** no es un nombre qye orovenga de alguno de sus fundadores, sino que se trata de una palabra alemana que tiene varias interpretaciones, entre llas: **forma**, **figura** y **estructura**.

### Principio de semejanza

La mente tiende a crear grupos de elementos que visualmente se vean parecidos entre si, ya sea porque comparte forma, color o tamaño, entre otras.


### Principio de proximidad

Solemos agrupar elementos segun la distancia que hay entre ellos, percibiendo como un grupo, objetos que estan muy juntos y como diferentes grupos, objetos que tienene cierta distancia entre ellos.

Un ejemplo es la distancia entre las distintas secciones, cuando se le **da aire** (espaciado).


### Pricipio de continuidad

Todos los elementos de un dise˜õ deben mantener una direccion concreta y estar proximos y alineados entre si.

Por ejemplo cuando hay dos direcciones para distintos grupos de elementos.


### Pricipio de experiencia

Las personas utilizamos nuestra experiencia y nuestras vivencias personales a la hora de utilizar productos digitales y comprender como funcion su interfaz.

Un ejemplo es un menu con opciones como cuando alguien elije una herramienta.

Se suele tener el mimo patron en los distintos dispositivos.


### Pricipio de figura-fondo

Las personas no somos capaces de distinguir un mismo elemento como fondo y figura al mismo tiempo. Nuestra mente organiza el contenido visual por capas, y percibe el *fondo* como la capa mas alejada y menos importante pese a que tenga mucho peso visual.

Hay que diseñar en capaz, los fondos no deben distraer.


### Pricipio de igualdad

Pese a que visualmente las persona preferimos grupos de objetos que tengan la misma forma, color, tama˜õ y figura, podemso romper esa similitud y cambiar algunos de esos elementos para destacar unos sobre otros sin tener que sacarlos del grupo.

Se usa en los CTA, pero hay que destacar lo justo.


### Pricipio de cierre

Por defecto al ojo humano no le gustan las formas abiertas, y visualmente tenemos tendencia a cerrar todos los circuitos, figuras y formas abiertas que encontramos. Tendmos a añadir con nuestra mente los elementos que faltaran, para completar una figura que esta incompleta.

Un ejemplo son los carrusels (sliders).


---

## :star: Metodologias Atomic Design en Diseño UI

Cuando un proyecto se dise˜ã a mano y desde cero, y cada pantalla se crea independientemente de la anterior, puede ocurrir errores humanos que distorsionen, altere el dise˜õ o creen ligeros cambios que afectan visualmente un elemento.

**Brad Frost** creo una metodologia de dise˜õ llamada **Atomic Design**, con la cual pretende acabar con las inconsistencias creadas por el diseño individual de pantallas y con la idea de optimizar el proceso de diseño de productos digitales.

Se diseña las fases por **componentes**.

Hay 5 fases.

Se crea una linea de estilos consistentes y componentes reutilizables.


### Primera etapa: Atomos

Las unidades mas pequeñas, los elementos que ya poseen una utilidad por si mismos, por ejemplo:

- titulos

- parrafos (tipografia)

- colores

- iconos

- botones

- campos de formularios

Se crean a partir de **wire frames**, se usan colores reales y con distintos estados, como por ejemplo un campo seleccionado y sin seleccionar, o un boton y un boton en hover.

### Segunda etapa: Moleculas

Un conjunto de atomos. Son mas complejos, por ejemplo:

- iconos con un texto descriptivo

- campos de formularios acompañados de un titulo

- un avatar, junto a los datos y un boton.


### Terccera etapa: Organismos

Conjunto de moleculas, que a su vez son conjuntos de atomos.

Un ejemplo es un menu de inicio, y que se muestre como se ve seleciconando las distintas opciones.

Otro ejemplo es un registro, en sus varaiciones con los campos de textos seleccionados o sin seleciconar.

Son **reutilizables** y **facilmente modificables**.


### Cuarta etapa: Plantillas

Son conjuntos de moleculas distribuidas en el lugar correcto. Se las ve en el canvas, se hacen un par para elegir luego el diseño final. Estan listas para el diseño final, una vez validadas.

### Quinta etapa: Paginas

El ultimo paso del diseño, con todos los detalles (infografia, colores, imagenes).


---

## :star: Tendencias en diseño UI

### Flat Design

Nacio en el 2206.  Se caracteriza:

_ colores vivos

- sencilles

- armonia

- estructuras bien diferenciadas

- se prescinde de sombras

- hay una forma sencilla


### Diseño monocromatico

Se elige un color base y se utilizan colores mas claros y obscuros a partir del elegido.

Son versatiles, no llaman mucho la atencion y el usuario se centra en el contenido.

Simplifica diseños que parecen recargados.

Se pueden añadir el blanco y negro para resaltar titulos o texto.

AL utilizar una paleta nomocromatica se recomienda dividir en secicones.


### Diseño minimalista

Surge de la idea de que el usuario prefiere interfaz sencilla y no recargada.

Es **claro**, **sencillo** y **consistente**.

Las paletas de colores suelen ser monocromaticas o anallogicas, tambien pueden usar blanco-gris-negro.

La tipografia debe ser sencilla, clara, facil de leer.

Los iconos son simple, lineas, sin relleno ni forma.

### El skemorfismo

Su objetivo es que sus elementos de la interfaz se parezcan lo mas posible a al realidad. Son lo contraio al flat design.

El usuario no necesita traducir la usabilidad porque es similar al mundo fisico, un ejemplo seria tener una calculadora. 

Se utulizan texturas, brillos, degradados, para crear profundidas, tridimension.


### El neumorfismo

Una interfaz que imita al mundo real, simula un boton real, por ejemplo. Se caracteriza, por:

- fondos sombrios 

- formas sin bordes

- uso de sombras y lucaes para construir los elementos.

Es un diseño sobrio, destaca la funcionalidad. Pero no es apto para quien tiene inconveneintes visuales, lo que no lo hace accesible.


---

## :star: Disegn Systems en UI

Un **Sistema de disñõ** o *8Design System** es un conjunto de documentacion, reglas, pricipios y patrones definidos que conforman el conjunto de nuestro producto digital.

### Usados por varios departamentos

Estos sistemas de diseño no solo sirven a diseñadores, sino que el equipo de desarrollo dle producto acudira al sistema para consultar anchos, altos, tamaños de imagenes, ittulares y un gran etcetera durante la confeccion de la interfaz grafica.

### Ejemplos:

garden.zandesk.com -> pocos componentes, pero bien definidos. Comparte su libreria de codigo

polaris.shopify.com -> colores, tipografia, ilustraciones, etc

material.io -> para andriod, son componentes y con casos de estudio

Son una guia para quienes la usen.

---

## :star: UI en paginas web

### Ejemplos de wireframes

- se debe investigar y luego hacer los sketches (wireframes)

Un ejemplo es la pagina pricipal de un lugar de recetas, arriba a la derecha esta el menu, luego centrado un buscador de recetas, y como hero 6 cuadrados, distribuidos en dos filas con imagenes de recetas y los minutos que tiene cada uno.

Otro ejemplo es el perfil del usuario de dicha plataforma que tiene: fotografia, datos luego 4 cuadros con recetas y debajo los comentarios.

### Ejemplo de componentes de diseño para producto web

- una paleta de colores

- tipografias

- campos de texto: seleciconados / no seleccionados

- un avatar

- menu con las distintas opciones seleccionadas

- botones, de poco relevancia (sin relleno), con rlevancia (con relleno)

### Ejemplo de Mockup para producto we

Se implementan los componentes en el mockup.

La misma pagina de las recetas, pero ahora con las imagenes reales, la tipografia, los colores, etc.

### Ejemplo de prototipo para producto web

Un prototipo es una representacion visual, pero no funcional de como seria la navegacion de un producto digital.

Se marcan las conexiones, al hacer click me llevan a la pantalla que sigue, si hago click en el menu me lleva a la seccion.


---

## :star: UI en aplicacion movil

### Diferencias entre UI Andriod y UI IOS

IOS elementos que parecen tridimensional, luz sombra y brillo, eskemorfismo.

Andriod es mas simple, plano, entre flat design y minimal design, es el materioa design.

Cada uno tiene su kits de usuario. Muestran paletas de colores, tipogracias, espacios, iconos, crad,s botones, campos de texto, etc. Ayuda a acelerar el proceso de diseño.

Como son estilos binein diferenciados se diseñan por separado.


### Ejemplos de componentes de diseño aplicaicon movil: Android

Los componentes ubicados de forma visual, en escalas de grises, guiandose por la guia de estilos.

Similar al anterior, pero ahora con informacion y colores reales, siguiendo la guia visual del componente.


### Ejemplo de componentes de diseño aplicacion movil: IOS

Los componentes ubicados de forma visual, hay componentes moviles como la paleta de colores, una tipografia, iconos de accion, una card tipica de IOS y su mensajeria.

### Ejemplo de mockup para aplicacion movil : IOS

Voy poniendo los componentes correspondientes, por ejemplo arrastro el menu.

Cambio el menu de fondo, la tipografia, los colores, etc.

### Ejemplo de prototipo para aplicacio movil

Es la representacion visual, pero no funcional, al hacer click se va de una pantalla a otra.


---

## :star: Presentacion de proyecto UI

Hay herramientas para crear las presentaciones, como:

- Adobe XD

- Google presentaciones

- Figma

- Power Point

- Canva

- Photo Shop

### Que debo tener?

- pantalla principal

- pantalla de indice, con un titulo corto pero descriptivo

- como opcional podes poner la guia de estilo

- pantalla del problema

- pantallas de producto, por cada pantalla una presentacion, los mockups

- pantalla final, de contacto

### Tips:

- utiliza los mismos estilos que el producto que has creado

- no utilices lenguaje informal

- enviala en PDF

- coloca titulo y numera las pantalla

- agrega links a tus contactos

---


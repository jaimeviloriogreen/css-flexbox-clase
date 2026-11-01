# ¿Qué es Flexbox?

Flexbox (abreviatura de Flexible Box Layout) es un modelo de diseño de CSS3 diseñado para alinear, ordenar y distribuir el espacio entre los elementos dentro de un contenedor de forma flexible y sencilla, incluso cuando sus dimensiones son desconocidas o dinámicas

## ¿Para qué sirve?

- **Alineación sencilla**: Permite centrar elementos vertical y horizontalmente con pocas líneas de código (algo que antes era complejo con métodos tradicionales como float o position).

- **Diseño responsivo**: Facilita la adaptación de los elementos a diferentes tamaños de pantalla y dispositivos

- **Distribución automática**: Reparte el espacio libre sobrante entre los elementos o los separa de manera uniforme de forma automática.

- **Una sola dimensión**: Está optimizado para organizar elementos en una sola dimensión a la vez: ya sea en una fila (row) o en una columna (column) (para diseños en dos dimensiones con filas y columnas simultáneas, se utiliza CSS Grid).

## Conceptos clave

1. Contenedor Flex (Flex Container): Es el elemento padre al que se le aplica la propiedad display: flex; (o display: inline-flex;).

2. Elementos Flex (Flex Items): Son todos los hijos directos del contenedor flex, los cuales se ordenan bajo las reglas del modelo.

3. Ejes:

- Eje principal (Main axis): Es la dirección principal en la que se fluyen los elementos (definida por flex-direction, que puede ser horizontal o vertical).
- Eje transversal (Cross axis): Es el eje perpendicular al eje principal.

## Propiedades principales

**En el contenedor padre**:

- display: flex; (activa el modelo Flexbox).
- flex-direction: define la dirección (row, row-reverse, column, column-reverse).
- justify-content: alinea los elementos a lo largo del eje principal (ej. center, space-between, flex-start).
- align-items: alinea los elementos a lo largo del eje transversal (ej. center, stretch, flex-start).
- flex-wrap: controla si los elementos deben ajustarse en una sola línea o pasar a múltiples líneas si no caben.

**En los elementos hijos**:

- flex-grow: define la capacidad de un elemento para crecer si hay espacio disponible.
- flex-shrink: define la capacidad de un elemento para encogerse si falta espacio.
- flex-basis: establece el tamaño inicial de un elemento antes de repartir el espacio.
- order: cambia el orden visual en que aparecen los elementos respecto al código HTML

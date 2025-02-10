# Proyecto Final DIW

Este proyecto es una página web dedicada a la música, utilizando HTML, CSS, y algunos frameworks como Bootstrap para mejorar la usabilidad y la accesibilidad del sitio. El propósito de este proyecto es mostrar el contenido relacionado con música, como artículos, videos, blogs, y más.

## Estructura de la Página

La página se encuentra dividida en varias secciones: 

- **Index**: La página principal con una presentación visual y un diseño interactivo.
- **Blog**: Sección dedicada a artículos y publicaciones relacionadas con la música.
- **Entrada**: Páginas individuales para cada artículo o entrada del blog.
- **Videos**: Sección que muestra videos relacionados con música.

## Uso de Flexbox, Grid y Bootstrap

### Flexbox

**Flexbox** es un modelo de diseño en CSS que permite crear diseños más flexibles y eficientes. En este proyecto, hemos usado **Flexbox** principalmente en los siguientes casos:

- En el **header** y el **footer**: Para alinear los elementos en una fila, como los logotipos, enlaces y redes sociales.
- En las **secciones de contenido** (por ejemplo, `.contenido`, `.temas-i`, `.temas-d`): Para organizar las imágenes y textos en filas o columnas, lo que hace que la disposición sea dinámica y fluida.

Flexbox es útil porque se adapta al tamaño de la pantalla, lo que permite una visualización adecuada en dispositivos móviles y de escritorio.

### CSS Grid

**CSS Grid** es otro modelo de diseño que se usa para crear estructuras de página más complejas y con un control preciso de las filas y columnas. Lo utilizamos en:

- La **sección del blog**: Para organizar los artículos en una cuadrícula de 4 columnas en pantallas grandes y adaptarse a 2 columnas o una sola columna en pantallas más pequeñas.
- En las **secciones de artículos**: Para mostrar artículos y sus respectivas imágenes o contenidos de forma ordenada.

**Grid** es ideal para crear layouts más complejos sin necesidad de usar posiciones absolutas o flotar elementos, lo que mejora la estructura y mantenimiento del código.

### Bootstrap

**Bootstrap** es un framework CSS que ayuda a crear páginas web rápidas y responsive. En este proyecto, hemos incluido **Bootstrap** para aprovechar su grid system, que permite organizar el contenido en una cuadrícula flexible. Con **Bootstrap**, podemos:

- Utilizar clases prediseñadas para crear un diseño responsive, de modo que el sitio web se adapte automáticamente a diferentes tamaños de pantalla.
- Mejorar la consistencia del diseño sin tener que escribir mucho código CSS adicional.

### Diseño Responsive

El diseño **responsive** es un aspecto crucial del proyecto, ya que buscamos asegurar que la página se vea correctamente en dispositivos de cualquier tamaño, desde computadoras de escritorio hasta teléfonos móviles.

**Implementación del diseño responsive**:

- Utilizamos **media queries** para aplicar estilos CSS específicos según el tamaño de la pantalla.
- En pantallas más grandes (por ejemplo, en computadoras de escritorio), las secciones se organizan en columnas múltiples, mientras que en dispositivos más pequeños (como móviles y tablets), las columnas se reorganizan en una sola columna para mejorar la legibilidad y el acceso a la información.
- El uso de **Bootstrap** también facilita que los componentes y las secciones cambien de tamaño y se alineen correctamente según el dispositivo.

Algunos de los cambios clave para hacer la página responsive incluyen:

- **En el blog**, la cuadrícula de 4 columnas se ajusta a 2 columnas en tablets y a 1 columna en teléfonos móviles.
- **En el header y footer**, los elementos se reorganizan para que se vean bien tanto en pantallas grandes como pequeñas.
- **En las imágenes**, se ajustan al tamaño del contenedor para no desbordar en pantallas más pequeñas.

**Media Queries**:

- Se han establecido puntos de interrupción (breakpoints) para los siguientes rangos de tamaño:
  - Pantallas de escritorio grandes (mayores a 992px).
  - Pantallas de tablets (entre 768px y 992px).
  - Pantallas de móviles (menos de 768px).

### Ejemplo de Colores

A continuación se muestran algunos de los colores principales utilizados en el proyecto. Estos colores son importantes para la coherencia visual y el diseño atractivo del sitio web.

| Color           | Código Hexadecimal | Ejemplo Visual        |
|-----------------|--------------------|-----------------------|
| Rojo Principal  | #ff0000            | ![#ff0000](https://via.placeholder.com/50/ff0000/ff0000.png) |
| Blanco          | #f3f3f3            | ![#f3f3f3](https://via.placeholder.com/50/f3f3f3/f3f3f3.png) |
| Negro           | #000000            | ![#000000](https://via.placeholder.com/50/000000/000000.png) |
| Coral Claro     | #f08080            | ![#f08080](https://via.placeholder.com/50/f08080/f08080.png) |
| Violeta Oscuro  | #9400d3            | ![#9400d3](https://via.placeholder.com/50/9400d3/9400d3.png) |

### Conclusión

Este proyecto utiliza las mejores prácticas de diseño web, combinando Flexbox, Grid, Bootstrap y media queries para asegurar una experiencia de usuario fluida, accesible y estéticamente agradable. Flexbox y Grid nos permiten tener un diseño flexible y adaptable, mientras que Bootstrap facilita la creación de un sitio responsive rápidamente.
# Réplica de un Portfolio

Este proyecto consiste en una réplica de un portfolio visual que incluye una galería de imágenes, un menú de navegación y un diseño adaptable (responsive). El diseño está optimizado tanto para dispositivos móviles como para pantallas de escritorio grandes, utilizando HTML5 y CSS3.

## Descripción

Este proyecto imita un **portfolio visual** que presenta diferentes imágenes en un formato de cuadrícula. La cabecera del sitio incluye el logo del artista (Filip Hodas) y un menú de navegación con enlaces a secciones como "About", "Paintings" y "Links". La galería de imágenes se adapta automáticamente a diferentes tamaños de pantalla gracias al uso de técnicas **responsive**.

### Estructura

1. **Cabecera**:
   - Incluye el logo del artista, que está encapsulado dentro de un contenedor circular.
   - Menú de navegación con enlaces a diferentes secciones.
  
2. **Galería de imágenes**:
   - Las imágenes se muestran en una cuadrícula que se adapta al tamaño de la pantalla.
   - En pantallas pequeñas, las imágenes ocupan el 50% del ancho; en pantallas más grandes, se ajustan a 33.33% o 25% dependiendo del tamaño de la ventana.

## Características

- **Responsive Design**:
   - El diseño es adaptable a diferentes tamaños de pantalla, desde dispositivos móviles hasta pantallas grandes de escritorio.
   - Utiliza **media queries** para cambiar el comportamiento del diseño en dispositivos con anchos de pantalla de 960px o más, y de 1200px o más.

- **Galería de Imágenes**:
   - La galería contiene 10 imágenes, y estas se muestran en formato de cuadrícula que varía según el tamaño de la pantalla:
     - En pantallas pequeñas: 2 columnas (50% del ancho por imagen).
     - En pantallas medianas (960px o más): 3 columnas (33.33% del ancho por imagen).
     - En pantallas grandes (1200px o más): 4 columnas (25% del ancho por imagen).

- **Estilo Visual Limpio**:
   - La cabecera utiliza un fondo blanco con el logo centrado en la parte izquierda y el menú alineado a la derecha.
   - Los enlaces del menú tienen estilos sutiles con un cambio de color al pasar sobre ellos.
   - El diseño general tiene un fondo gris claro que resalta las imágenes de la galería.

## Estructura del Proyecto

- **index.html**: Contiene la estructura principal del sitio, con el logo, menú de navegación y galería de imágenes.
- **css/style.css**: Archivo de estilos que define el diseño del sitio, tanto en su versión móvil como de escritorio.
- **img/**: Carpeta que contiene las imágenes utilizadas para la galería y el logo.

## Tecnologías Utilizadas

- **HTML5**: Para la estructura semántica de la página.
- **CSS3**: Para el diseño, incluyendo flexbox para el posicionamiento de elementos y media queries para la adaptabilidad.
- **Responsive Design**: Para asegurar que la página se vea bien tanto en dispositivos móviles como en pantallas grandes.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone (https://github.com/Analucena53/modeloPortfolio.git)

2. Abre el archivo index.html en tu navegador preferido para ver la réplica del portfolio.

3. Puedes personalizar las imágenes de la galería simplemente reemplazando los archivos en la carpeta img.

Adaptabilidad
Pantallas pequeñas (menores a 960px):

El menú de navegación y el logo aparecen en la parte superior.
Las imágenes de la galería se organizan en dos columnas (cada imagen ocupa el 50% del ancho).
Pantallas medianas (960px o más):

El menú de navegación y el logo se colocan en una barra lateral a la izquierda.
Las imágenes se reorganizan en tres columnas (cada imagen ocupa el 33.33% del ancho).
Pantallas grandes (1200px o más):

Las imágenes se organizan en cuatro columnas (cada imagen ocupa el 25% del ancho).

Mejoras Futuras
Filtrado de imágenes: Incluir una funcionalidad para filtrar las imágenes por categorías.
Animaciones CSS: Añadir transiciones o animaciones al pasar el cursor sobre las imágenes.
Optimización de Imágenes: Reducir el peso de las imágenes para mejorar el rendimiento.

Créditos
Este proyecto es una réplica creada con fines educativos, inspirada en el trabajo de Filip Hodas.





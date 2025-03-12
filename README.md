# Liga_Bootstrap
Proyecto final de Bootstrap y Sass, realizado por Alejandro Sanchez Serrano y David Castro Lopez.

# Guía de Estilos de La Liga Nitro

## Tipografía

### Fuentes
- **Fuente Principal**: 
  - `Bootstrap`: Se utiliza la tipografía predeterminada de Bootstrap.
  - `Bootstrap Icons`: Se utilizan los iconos tipográficos de Bootstrap Icons.
  - **Fuente Personalizada**: `'Alislam'`
    ```css
    @font-face {
      font-family: 'Alislam';
      src: url('../../build/font/Alislam.woff2') format('woff2'),
           url('../../build/font/Alislam.woff') format('woff'),
           url('../../build/font/Alislam.otf') format('opentype');
    }
    ```

### Tamaños de Fuente
- **Título Principal**: `h1` con clase `fs-4` (font-size: 1.5rem)
- **Enlaces de Navegación**: clase `fs-5` (font-size: 1.25rem)
- **Títulos de Sección**: `h2` con `font-size: 2rem`
- **Texto General**: `16px`

### Peso de Fuente
- **Títulos (h1, h2, h3, h4)**: `bolder`
- **Texto General**: `normal`

## Colores

### Variables de Colores
- **Color de Fondo General**: `#f5f5f5`
- **Color de Fondo del Header**: `#ffff`
- **Color Principal**: `#ffdd00`
- **Color de Texto Principal**: `#0000`
- **Color de Enlaces**: `#f5f5f5`
- **Color de Enlaces Hover**: `#ffdd00`

### Colores de Fondo
- **Header y Footer**: `bg-white` (blanco)
- **Sección Equipos y Patrocinadores**: `bg-light` (gris claro)
- **Sección Partidos**: `bg-light` (gris claro)
- **Tabla de Clasificación**: `table-dark` (gris oscuro para el encabezado de la tabla)

### Colores de Texto
- **Texto Principal**: `text-black` (negro)
- **Enlaces de Navegación**: `text-dark` (gris oscuro)
- **Enlaces de Enlaces Importantes**: `text-dark` (gris oscuro)
- **Redes Sociales**: `text-dark` (gris oscuro)

## Espaciado

### Márgenes y Padding
- **Header y Footer**: Clase `py-5` (padding en el eje y: 3rem)
- **Secciones**: Clase `mt-4` (margen superior: 1.5rem)
- **Botón de Ver Más Detalles**: Clase `mt-3` (margen superior: 1rem)
- **Padding para Secciones**: `padding: 2rem 0;`

### Márgenes en Títulos de Sección
- **Títulos de Sección**: `margin-bottom: 1.5rem;`

## Altura de Línea
- **Texto General**: `line-height: 1.5;`

## Tablas
- **Ancho de la Tabla**: `100%`
- **Margen Inferior de la Tabla**: `2rem`
- **Alineación de Texto en la Tabla**: `center`
- **Color de Texto del Encabezado de la Tabla**: `blanco`
- **Color de Fondo de Filas Pares**: `#e9ecef`

## Tipografía de Títulos
- **Fuente de Títulos (h1, h2, h3, h4)**: `'Alislam', sans-serif`
- **Peso de Fuente de Títulos**: `bolder`

## Enlaces
- **Color de Enlaces**: `#f5f5f5`
- **Decoración de Texto de Enlaces**: `none`
- **Color de Enlaces al Hover**: `#ffdd00`

## Imágenes de Patrocinadores
- **Altura Máxima de Imágenes de Patrocinadores**: `100px`
- **Margen de Imágenes de Patrocinadores**: `0.5rem`

## Otros

### Imágenes
Usando enlaces de Google o subidas a Cloudinary (el logo esta de forma local)
- **Logo**: `max-height: 60px`
- **Imágenes del Carrusel**: Clase `d-block w-100` (display: block, width: 100%)
- **Imágenes de Patrocinadores**: Clase `sponsor-img`

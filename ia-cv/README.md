# Hoja de vida en HTML y CSS

Este archivo resume la estructura de la pagina ubicada en `ia-cv/index.html` y el estilo aplicado desde `assets/styles/ia.css`.

## Estructura general

La pagina usa una estructura semantica para ordenar la informacion de la hoja de vida:

- `main` contiene todo el contenido principal.
- `section` separa cada bloque importante.
- `article` agrupa tarjetas independientes dentro de la pagina.
- `figure` y `figcaption` presentan la foto de perfil con una descripcion corta.

## Etiquetas utilizadas

- `header` contiene la parte superior de la pagina.
- `h1` sirve para el titulo principal.
- `h2` y `h3` organizan los subtitulos de cada seccion.
- `p` muestra los parrafos descriptivos del perfil y la experiencia.
- `ul` y `li` se usan para listas de habilidades, educacion y certificaciones.
- `a` crea enlaces para botones y redes sociales.
- `img` inserta la imagen de perfil.
- `strong` resalta datos importantes como correo, telefono o cargos.

## Atributos aplicados

- `lang="es"` indica que el contenido esta en espanol.
- `charset="UTF-8"` permite mostrar correctamente los caracteres.
- `name="viewport"` hace que la pagina sea responsive en celular y escritorio.
- `href` enlaza la hoja de estilo externa.
- `alt` describe la imagen de perfil para accesibilidad.
- `id` marca secciones como `perfil` y `contacto` para navegar con enlaces internos.
- `class` asigna estilos reutilizables como `card`, `button` y `stats-grid`.
- `aria-label` mejora la comprension de los lectores de pantalla en el resumen rapido.

## CSS agregado

El archivo `ia.css` define el aspecto visual de la hoja de vida:

- Fondo con degradados y brillo suave para dar profundidad.
- Tarjetas tipo vidrio con bordes redondeados, sombra y efecto de desenfoque.
- Rejillas con `grid` para organizar el hero, estadisticas y secciones.
- Botones redondeados con estados `hover` para interaccion visual.
- Listas en forma de chips para habilidades y certificaciones.
- Ajustes con `@media` para que el contenido se adapte a pantallas pequenas.

## Resultado

La pagina final muestra una hoja de vida moderna, clara y responsive, con secciones de perfil, experiencia laboral, educacion, certificaciones, habilidades, contacto y redes sociales.

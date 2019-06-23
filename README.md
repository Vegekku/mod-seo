# mod-seo

Práctica del módulo de SEO

## Recomendaciones SEO que ya estaban en el original

- Un único menú identificado y responsive.
- Un único encabezado h1 que menciona al autor.
- El menú está maquetado en mayúscula desde CSS.
- Los diferentes apartados del CV están contenidos en `section`.
- Por motivos de maquetación, las `section` están contenidas dentro de divs.

## Modificaciones sobre original

- Se ha optimizado el title por nombre y profesión para las búsquedas.
- Se ha incluido un meta description.
- Se ha desplazado la carga del javascript al final del HTML, para optimizar la carga de la web.
- Se ha añadido el atributo title a todos los links.
- Se ha usado `<abbr>` para describir las abreviaturas usadas.
- Se han corregido los encabezados de las secciones de `h1` a `h2` en las distintas secciones del CV, y de `h2` a `h3` en las subsecciones anteriores.
- Se ha añadido un `<figcaption>` a `<figure>` de la imagen.
- Se han etiquetado las redes sociales dentro de `<address>`.
- Se han modificado los subtítulos que estaban con `span` por `p`.
- Se han añadido microdatos de schema.org, tomando como base el objeto de tipo `Person`.

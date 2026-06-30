---
title: 'Mi tercer post en Astro'
pubDate: 2026-06-30
description: 'En esta tercera entrega aprendemos a dar estilo a nuestro blog en Astro utilizando CSS global, componentes y Tailwind.'
author: 'Tu Nombre'
image:
    url: 'https://astro.build'
    alt: 'Código CSS en una pantalla.'
tags: ["astro", "css", "diseño"]
---

¡Hola a todos! En los artículos anteriores vimos cómo iniciar nuestro blog y cómo funciona la arquitectura de islas. 

Hoy nos enfocaremos en la estética: cómo dar estilo a nuestra web en **Astro** de forma eficiente y organizada.

## Opciones de estilado en Astro

Astro es increíblemente flexible y te permite trabajar con estilos de la forma que prefieras:

* **Estilos con alcance (Scoped CSS)**: Por defecto, las etiquetas `<style>` en un archivo `.astro` solo afectan a ese componente. Evita conflictos de nombres automáticamente.
* **Estilos globales**: Ideal para fuentes, variables de diseño y reseteos tipográficos que afectan a toda la web.
* **Integración con frameworks**: Puedes añadir herramientas como Tailwind CSS, Sass o Styled Components con un solo comando.

## Ejemplo de CSS con alcance

Escribir estilos específicos para un componente es tan sencillo como hacer esto dentro de tu archivo `.astro`:

```astro
---
// Tu código JavaScript o Frontmatter aquí
---
<button class="btn-principal">Haz clic aquí</button>

<style>
  /* Este estilo solo se aplicará a este botón en este componente */
  .btn-principal {
    background-color: #4f46e5;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 0.25rem;
  }
</style>
```

## Próximos pasos para el blog

Ahora que el blog tiene un aspecto increíble, el siguiente paso lógico es la optimización y la automatización. 

En la próxima entrega veremos cómo automatizar la distribución de nuestro contenido. ¡Nos vemos en el próximo artículo!
<a href="/"> volver</a>
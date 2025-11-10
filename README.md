# demo-media-query
Primer proyecto demostrativo mobile  first
demo-media-query
Descripción del Proyecto

Este proyecto es una demostración práctica del uso de Media Queries en CSS, aplicando el enfoque Mobile First para crear diseños web responsivos y adaptativos.
¿Qué son las Media Queries?

Las Media Queries son una característica de CSS3 que permite aplicar estilos específicos según las características del dispositivo donde se visualiza la página web, como:

    Ancho y alto de la pantalla
    Orientación del dispositivo (horizontal o vertical)
    Resolución de la pantalla
    Tipo de medio (pantalla, impresión, etc.)

Enfoque Mobile First

El enfoque Mobile First es una estrategia de diseño web que consiste en:

    Diseñar primero para dispositivos móviles: Se comienza con el diseño más simple y optimizado para pantallas pequeñas
    Expandir progresivamente: Se agregan estilos y funcionalidades adicionales para pantallas más grandes mediante media queries
    Optimización del rendimiento: Los dispositivos móviles cargan solo los estilos esenciales, mejorando la velocidad de carga

Ventajas del Mobile First

    Mejora la experiencia de usuario en dispositivos móviles
    Optimiza el rendimiento y velocidad de carga
    Simplifica el código CSS
    Se adapta mejor a la tendencia actual de tráfico web mayormente móvil

Media Queries en la Práctica
Sintaxis Básica

/* Estilos base para móviles */
.contenedor {
  width: 100%;
  padding: 10px;
}

/* Estilos para tablets y superiores */
@media (min-width: 768px) {
  .contenedor {
    width: 750px;
    margin: 0 auto;
  }
}

/* Estilos para escritorio */
@media (min-width: 1024px) {
  .contenedor {
    width: 1000px;
  }
}

Breakpoints Comunes

    Móviles pequeños: < 576px
    Móviles grandes: ≥ 576px
    Tablets: ≥ 768px
    Escritorio: ≥ 1024px
    Escritorio grande: ≥ 1200px

Objetivo del Proyecto

Este proyecto demostrativo tiene como objetivo:

    Enseñar el uso práctico de media queries
    Demostrar la implementación del enfoque Mobile First
    Mostrar cómo crear layouts adaptativos que funcionen en diferentes dispositivos
    Servir como referencia y punto de partida para proyectos responsivos

Tecnologías

    HTML5
    CSS3 (Media Queries)
    Diseño Responsivo

Primer proyecto demostrativo mobile first

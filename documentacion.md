# Documentación: Header con Menú de Navegación para PC (sin media queries)

Este documento describe paso a paso la estructura y los estilos de un header básico con navegación, pensado para escritorio y sin uso de media queries. Está diseñado con pocas líneas de código y explicado en detalle para facilitar su comprensión.

---

## 1. Objetivo

Crear un encabezado de página con:

- Un **título del sitio** a la izquierda.
- Un **menú de navegación** alineado a la derecha.
- Un diseño limpio, horizontal y simple, sin adaptabilidad móvil (sin `@media`).

---

## 2. Estructura HTML

```html
<header>
  <h1>Mi Sitio</h1>
  <nav>
    <a href="#">Inicio</a>
    <a href="#">Servicios</a>
    <a href="#">Contacto</a>
  </nav>
</header>
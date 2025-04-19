Perfecto, acá tenés todo el contenido como un único archivo .md, sin explicaciones por fuera. Todo está dentro del bloque Markdown, como me pediste:

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

Explicación:

<header>: contenedor principal del encabezado.

<h1>: título del sitio, se ubica a la izquierda.

<nav>: contiene los enlaces de navegación.

<a>: enlaces a diferentes secciones del sitio.



---

3. Estilos CSS

header {
  background: #333;
  padding: 10px 20px;
  color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 15px;
}

nav a:hover {
  text-decoration: underline;
}


---

4. Explicación de cada propiedad CSS

header


---

nav a


---

nav a:hover


---

5. Consideraciones

Este diseño está pensado únicamente para escritorio.

No contiene media queries, por lo que no se adapta a pantallas pequeñas.

Ideal para maquetación básica, prototipos o sitios estáticos simples.

Puede servir como base para agregar diseño responsive más adelante si se desea.



---

6. Instrucciones de uso

1. Copiar el HTML y CSS en un archivo .html.


2. Guardarlo y abrirlo con un navegador de escritorio.


3. Se visualizará un encabezado con el título a la izquierda y enlaces a la derecha.




---

7. Créditos

Documentación creada por ChatGPT para uso educativo, con explicaciones claras de propósito y función de cada parte del código.




# 2. HTML, CSS y JavaScript

Cuando construimos una página web, normalmente utilizamos tres tecnologías principales:

- HTML
- CSS
- JavaScript

Cada una tiene una responsabilidad diferente dentro de una página web.

## HTML

HTML significa **HyperText Markup Language** y se utiliza para crear la estructura y organizar el contenido de una página web.

Con HTML podemos crear elementos como:

- Títulos
- Párrafos
- Imágenes
- Enlaces
- Listas
- Formularios
- Botones
- Secciones

## CSS

CSS significa **Cascading Style Sheets** y se utiliza para definir la apariencia y el diseño de los elementos HTML.

Con CSS podemos modificar:

- Colores
- Tamaños
- Tipografías
- Espaciados
- Bordes
- Fondos
- Posición de los elementos
- Distribución de la página

Ejemplo:

h1 {
color: blue;
}

En este caso, HTML define el título y CSS define parte de su apariencia.

## JavaScript

JavaScript es un lenguaje de programación que permite agregar comportamiento e interactividad a una página web.

Con JavaScript podemos:

- Responder a acciones del usuario.
- Validar formularios.
- Modificar elementos HTML.
- Realizar cálculos.
- Obtener información de APIs.
- Mostrar u ocultar contenido.
- Crear aplicaciones web interactivas.

Ejemplo:

button.addEventListener("click", () => {
console.log("Hiciste clic");
});

En este ejemplo, JavaScript permite ejecutar una acción cuando el usuario hace clic en un botón.

## ¿Cómo trabajan juntos?

HTML, CSS y JavaScript tienen responsabilidades diferentes, pero trabajan juntos para construir una página web.

Podemos imaginar una página web como una casa:

- HTML = estructura de la casa.
- CSS = apariencia y decoración.
- JavaScript = comportamiento e interacción.

Una forma sencilla de recordarlo:

HTML = estructura

CSS = apariencia

JavaScript = comportamiento

Ejemplo

Una página puede tener un botón creado con HTML:

<button id="boton">Haz clic</button>

CSS puede modificar su apariencia:

button {
font-size: 20px;
padding: 10px;
}

Y JavaScript puede darle comportamiento:

const boton = document.querySelector("#boton");

boton.addEventListener("click", () => {
alert("¡Hiciste clic!");
});

En este caso:

HTML crea el botón.
CSS modifica cómo se ve.
JavaScript determina qué ocurre cuando hacemos clic.
Concepto clave

HTML, CSS y JavaScript no cumplen la misma función.

HTML estructura el contenido.

CSS define su presentación.

JavaScript agrega comportamiento e interactividad.

# 4. Etiquetas, elementos y atributos

En HTML existen tres conceptos fundamentales que debemos conocer:

- Etiquetas
- Elementos
- Atributos

Comprender la diferencia entre ellos es importante para poder escribir HTML correctamente.

## Etiquetas

Las **etiquetas** indican al navegador qué tipo de contenido estamos creando.

Normalmente se escriben utilizando los símbolos "<" y ">".

Ejemplo:

html

<h1> </h1>

La etiqueta <h1> indica que estamos creando un encabezado de nivel 1.

Muchas etiquetas tienen una etiqueta de apertura y una de cierre:

<p>Este es un párrafo.</p>

En este caso:

<p> es la etiqueta de apertura
</p> es la etiqueta de cierre

El contenido está entre ambas etiquetas.

Aquí te dejo algunas etiquetas comunes:

<h1>Título</h1>

<p>Párrafo</p>

<a>Enlace</a>

<button>Botón</button>

<ul>Lista</ul>

<li>Elemento de lista</li>

Acá [www.w3schools.com](https://www.w3schools.com/TAGs/default.asp) puedes encontrar todas las etiquetas por orden afabético, te recomiendo que les eches un vistazo.

## Elementos

Un elemento HTML está formado por la etiqueta de apertura, el contenido y la etiqueta de cierre, cuando corresponde.

Por ejemplo:

<p>Hola, mundo</p>

Podemos dividirlo así:

<p>          → etiqueta de apertura
Hola, mundo  → contenido
</p>         → etiqueta de cierre

Todo esto en conjunto es un elemento HTML.

## Atributos

Los atributos proporcionan información adicional sobre un elemento HTML.

Se escriben dentro de la etiqueta de apertura.

Por ejemplo:

<a href="https://www.google.com">Google</a>

En este caso:

- <a> es la etiqueta
- href es un atributo.
- "https://www.google.com" es el valor del atributo.
- Google es el contenido.

**Todo junto forma un elemento HTML.**

Los atributos normalmente tienen esta estructura:

- nombre="valor"

## Atributo id

El atributo id permite identificar de manera única un elemento dentro de una página.

<p id="descripcion">Este es un párrafo.</p>

En este ejemplo:

id → atributo
"descripcion" → valor del atributo

## Atributo class

El atributo class permite asignar una o varias clases a un elemento.

Es muy utilizado junto con CSS y JavaScript.

<p class="texto-principal">Hola, mundo</p>

En este caso:

- class → atributo
- "texto-principal" → valor del atributo

## Atributo src

El atributo src indica la ubicación de un recurso, como una imagen.

<img src="imagen.jpg" alt="Una imagen">

Aquí:

- src indica dónde se encuentra la imagen.
- alt proporciona un texto alternativo para la imagen.

## Atributo href

El atributo href se utiliza principalmente en los enlaces para indicar la dirección a la que deben llevar.

<a href="https://www.google.com">Visitar Google</a>

El navegador utiliza el valor de href para saber cuál es el destino del enlace.

Elementos con múltiples atributos

Un elemento puede tener varios atributos,

Por ejemplo:

<img src="gato.jpg" alt="Gato sentado" class="imagen-gato">

Este elemento tiene tres atributos:

- src
- alt
- class

Cada uno proporciona información diferente.

## Elementos sin etiqueta de cierre

No todos los elementos HTML necesitan una etiqueta de cierre.

Por ejemplo:

<img src="gato.jpg" alt="Gato">

También podemos encontrar:

<br>
<hr>
<meta charset="UTF-8">

Estos elementos no contienen contenido entre una etiqueta de apertura y una de cierre.

Se conocen comúnmente como elementos vacíos.

## Diferencia entre etiqueta, elemento y atributo

Podemos resumirlo de esta manera:

ETIQUETA
↓

<p>

ELEMENTO
↓

<p>Hola, mundo</p>

ATRIBUTO
↓

<p class="texto">Hola, mundo</p>
             ↑
          atributo

En el último ejemplo:

<p class="texto">Hola, mundo</p>
<p> → etiqueta.
class="texto" → atributo.
<p class="texto">Hola, mundo</p> → elemento completo.

## Concepto clave

Es importante no confundir estos tres conceptos:

Etiqueta → define el tipo de contenido.

Elemento → es la estructura HTML completa.

Atributo → proporciona información adicional sobre un elemento.

Ejemplo:

<a href="https://www.google.com">Google</a>

<a> = etiqueta

href="https://www.google.com" = atributo

<a href="https://www.google.com">Google</a> = elemento

#5 — Títulos y textos en HTML

Objetivo del módulo

En este módulo aprenderemos a:

Crear títulos y subtítulos.
Organizar la información mediante una jerarquía.
Crear párrafos.
Realizar saltos de línea.
Destacar texto importante.
Dar énfasis a determinadas palabras.
Combinar diferentes etiquetas HTML.

1.  Títulos en HTML

HTML tiene seis niveles de títulos:

<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Subtítulo de nivel 3</h3>
<h4>Subtítulo de nivel 4</h4>
<h5>Subtítulo de nivel 5</h5>
<h6>Subtítulo de nivel 6</h6>

La jerarquía es:

<h1> → más importante
<h2>
<h3>
<h4>
<h5>
<h6> → menos importante
¿Qué significa la h?

La h viene de heading, que significa "encabezado" o "título".

El número indica el nivel de importancia:

<h1> → Heading 1
<h2> → Heading 2
<h3> → Heading 3
2.  El <h1>

El <h1> representa el título principal de una página.

Ejemplo:

<h1>Mi página web</h1>

Podemos imaginar que nuestra página tiene esta estructura:

Mi página web

El <h1> debería representar el tema principal de la página.

Ejemplo

<h1>Mi tienda de ropa</h1>
3. 🥈 El <h2>

El <h2> se utiliza para crear secciones principales dentro de nuestra página.

Ejemplo:

<h1>Mi tienda de ropa</h1>

<h2>Ropa de mujer</h2>

<h2>Ropa de hombre</h2>

<h2>Accesorios</h2>

La estructura sería:

<h1> Mi tienda de ropa

    <h2> Ropa de mujer

    <h2> Ropa de hombre

    <h2> Accesorios

4.  El <h3>

El <h3> se utiliza para crear subsecciones dentro de un <h2>.

Ejemplo:

<h1>Mi tienda de ropa</h1>

<h2>Ropa de mujer</h2>

<h3>Poleras</h3>

<h3>Pantalones</h3>

<h3>Vestidos</h3>

La jerarquía sería:

<h1> Mi tienda de ropa
│
└── <h2> Ropa de mujer
    │
    ├── <h3> Poleras
    ├── <h3> Pantalones
    └── <h3> Vestidos
5. 🔢 Los títulos <h4>, <h5> y <h6>

También existen niveles inferiores:

<h4>Subsección</h4>

<h5>Subsección menor</h5>

<h6>Subsección muy específica</h6>

Por ejemplo:

<h1>Mi tienda</h1>

<h2>Ropa</h2>

<h3>Poleras</h3>

<h4>Poleras manga corta</h4>

<h5>Poleras estampadas</h5>

<h6>Poleras estampadas de verano</h6>

No siempre necesitaremos utilizar los seis niveles.

Lo importante es mantener una estructura lógica.

6. No debemos elegir los títulos solamente por su tamaño

Una idea importante:

Los títulos HTML no deberían utilizarse solamente para hacer que un texto se vea grande.

Por ejemplo, no deberíamos hacer esto:

<h1>Texto pequeño</h1>

<h6>Texto que quiero que se vea grande</h6>

Los títulos representan la importancia y estructura del contenido, no solamente el tamaño visual.

Más adelante, cuando aprendamos CSS, podremos modificar el tamaño, color, tipo de letra, etc.

7.  Párrafos con <p>

La etiqueta <p> viene de paragraph, que significa "párrafo".

Se utiliza para escribir texto:

<p>Hola, estoy aprendiendo HTML.</p>

Podemos tener varios párrafos:

<p>Este es mi primer párrafo.</p>

<p>Este es mi segundo párrafo.</p>

<p>Este es mi tercer párrafo.</p>

Cada etiqueta <p> representa un párrafo independiente.

8.  Ejemplo con títulos y párrafos
<h1>Mi página personal</h1>

<h2>Sobre mí</h2>

<p>
    Hola, mi nombre es María y estoy aprendiendo desarrollo web.
</p>

<h2>Mis hobbies</h2>

<p>
    Me gusta aprender cosas nuevas y pasar tiempo con los animales.
</p>

<h2>Mis objetivos</h2>

<p>
    Quiero aprender a crear páginas web.
</p>

La estructura sería:

<h1> Mi página personal

    <h2> Sobre mí
        <p> Información sobre mí

    <h2> Mis hobbies
        <p> Información sobre mis hobbies

    <h2> Mis objetivos
        <p> Información sobre mis objetivos

9.  Saltos de línea con <br>

La etiqueta <br> sirve para realizar un salto de línea.

br viene de break, que significa "salto".

Ejemplo:

<p>
    Hola, soy María.<br>
    Estoy aprendiendo HTML.
</p>

El resultado será aproximadamente:

Hola, soy María.
Estoy aprendiendo HTML. 10. <br> no necesita cierre

A diferencia de etiquetas como <p>:

<p>Texto</p>

<br> no necesita una etiqueta de cierre.

Correcto:

<br>

No es necesario escribir:

<br></br> 11. Diferencia entre <p> y <br>
Usando <p>

<p>Primer párrafo.</p>

<p>Segundo párrafo.</p>

Estamos creando dos párrafos diferentes.

Usando <br>

<p>
    Primera línea.<br>
    Segunda línea.
</p>

Seguimos teniendo un mismo párrafo, pero hacemos un salto de línea.

12. Texto importante con <strong>

La etiqueta <strong> sirve para indicar que un texto tiene importancia.

Ejemplo:

<p>
    Este texto es <strong>muy importante</strong>.
</p>

Normalmente el navegador mostrará:

muy importante

Otro ejemplo:

<p>
    Recuerda <strong>guardar tu archivo</strong>.
</p>
13.  Énfasis con <em>

La etiqueta <em> sirve para dar énfasis a una parte del texto.

Ejemplo:

<p>
    Estoy <em>muy emocionada</em> por aprender HTML.
</p>

Normalmente el navegador mostrará el texto en cursiva:

muy emocionada \*

Otro ejemplo:

<p>
    Es <em>muy importante</em> practicar.
</p>
14.  Combinar <strong> y <em>

Podemos utilizar ambas etiquetas:

<p>
    HTML es <strong>muy importante</strong> y
    <em>muy interesante</em>.
</p>

También podemos aplicarlas al mismo texto:

<p>
    Esto es <strong><em>muy importante</em></strong>.
</p>
15. Combinar títulos, párrafos y otras etiquetas

Podemos crear una página completa utilizando las etiquetas que hemos aprendido.

<h1>Mi página personal</h1>

<h2>Sobre mí</h2>

<p>
    Hola, mi nombre es María.
    Estoy aprendiendo desarrollo web.
</p>

<h2>Mis intereses</h2>

<h3>Animales</h3>

<p>
    Me encantan los animales.
</p>

<h3>Tecnología</h3>

<p>
    Me interesa mucho la tecnología y la programación.
</p>

<h2>Mi objetivo</h2>

<p>
    Quiero aprender <strong>HTML, CSS y JavaScript</strong>
    para crear mis propios proyectos.
</p>
16.  Jerarquía de una página

Una página puede tener una estructura similar a esta:

<h1> Página principal
│
├── <h2> Sobre mí
│   └── <p> Información
│
├── <h2> Mis hobbies
│   ├── <h3> Animales
│   │   └── <p> Información
│   │
│   └── <h3> Tecnología
│       └── <p> Información
│
└── <h2> Mi objetivo
    └── <p> Información

Esta organización nos permite crear una página con una estructura clara.

17. Etiquetas aprendidas
Etiqueta Significado Uso
<h1>	Heading 1	Título principal
<h2>	Heading 2	Sección principal
<h3>	Heading 3	Subsección
<h4>	Heading 4	Subnivel
<h5>	Heading 5	Subnivel
<h6>	Heading 6	Subnivel menor
<p>	Paragraph	Párrafo
<br>	Break	Salto de línea
<strong>	Strong importance	Texto importante
<em>	Emphasis	Texto con énfasis
18. Ejemplo completo

Aquí tenemos un ejemplo que combina todo lo aprendido:

<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Mi presentación</title>
</head>

<body>

    <h1>¡Hola! Soy María</h1>

    <h2>Sobre mí</h2>

    <p>
        Hola, mi nombre es María y estoy aprendiendo
        desarrollo web con HTML.
    </p>

    <p>
        Me gusta aprender cosas nuevas y desarrollar
        nuevas habilidades.
    </p>

    <h2>Mis intereses</h2>

    <h3>Animales</h3>

    <p>
        Me encantan los animales y disfruto mucho
        pasar tiempo con ellos.
    </p>

    <h3>Tecnología</h3>

    <p>
        Me interesa la tecnología y la programación.
    </p>

    <h2>Mi objetivo</h2>

    <p>
        Mi objetivo es aprender
        <strong>desarrollo web</strong> y crear
        mis propios proyectos.
    </p>

    <p>
        Estoy aprendiendo paso a paso.<br>
        Lo importante es practicar.
    </p>

</body>

</html>
19.  Ejercicio práctico

Ahora intenta crear una página sobre ti.

La página debe tener:

Título principal

Utiliza:

<h1>

Incluye tu nombre.

Sección "Sobre mí"

Utiliza:

<h2>

Después agrega un párrafo:

<p>
Sección "Mis hobbies"

Utiliza:

<h2>

Después crea al menos dos subsecciones:

<h3>

Cada una debe tener un párrafo:

<p>
Sección "Mi objetivo"

Utiliza:

<h2>

Agrega un párrafo y utiliza <strong> para destacar una parte importante.

Utiliza también <br>

Crea un párrafo que tenga al menos un salto de línea.

20. Resultado esperado

Tu código debería tener una estructura parecida a esta:

<h1>Mi nombre</h1>

<h2>Sobre mí</h2>

<p>
    Información sobre mí.
</p>

<h2>Mis hobbies</h2>

<h3>Hobby 1</h3>

<p>
    Información sobre mi primer hobby.
</p>

<h3>Hobby 2</h3>

<p>
    Información sobre mi segundo hobby.
</p>

<h2>Mi objetivo</h2>

<p>
    Mi objetivo es <strong>...</strong>.
</p>

<p>
    Primera línea.<br>
    Segunda línea.
</p>
 Conceptos clave para recordar
1. Los títulos tienen jerarquía
h1
 ↓
h2
 ↓
h3
 ↓
h4
 ↓
h5
 ↓
h6
2. <p> crea párrafos
<p>Este es un párrafo.</p>
3. <br> crea un salto de línea
Primera línea<br>
Segunda línea
4. <strong> indica importancia
<strong>Texto importante</strong>
5. <em> indica énfasis
<em>Texto con énfasis</em>
📝 Resumen

En este módulo aprendimos a crear y organizar textos en HTML.

Las etiquetas principales son:

<h1> Título principal
<h2> Sección
<h3> Subsección
<h4> Subnivel
<h5> Subnivel
<h6> Subnivel
<p>  Párrafo
<br> Salto de línea
<strong> Texto importante
<em> Texto con énfasis

HTML se encarga de estructurar el contenido.

Más adelante, con CSS, aprenderemos a cambiar su apariencia:

HTML → estructura
CSS → diseño y apariencia
JavaScript → comportamiento e interacción
Reto final

Crea una página titulada:

"Mi página personal"

Debe contener:

Un <h1>

Al menos tres <h2>

Al menos dos <h3>

Al menos cuatro <p>

Un <strong>

Un <em>

Un <br>

Una estructura jerárquica ordenada

No te preocupes todavía por colores, tamaños o diseños.

En este módulo el objetivo es aprender a estructurar correctamente el contenido HTML.

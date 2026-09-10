# 3. Estructura básica de HTML

Un documento HTML tiene una estructura básica que permite al navegador interpretar correctamente el contenido de la página.

La estructura mínima de un documento HTML es:

html

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi página web</title>
</head>
<body>

    <h1>Hola, mundo</h1>
    <p>Esta es mi primera página web.</p>

</body>
</html>

## Partes principales de un documento HTML

# <!DOCTYPE html>

- Indica al navegador que el documento utiliza HTML5.

No es una etiqueta HTML, sino una declaración que debe colocarse al comienzo del documento.

# <html>

Es el elemento raíz del documento HTML.

Todos los demás elementos HTML se encuentran dentro de este elemento.

<html lang="es">

</html>

El atributo lang="es" indica que el idioma principal del documento es español.

# <head>

Contiene información sobre el documento que normalmente no se muestra directamente como contenido de la página.

Dentro de <head> podemos encontrar:

- Metadatos
- El título de la página
- Enlaces a archivos CSS
- Configuraciones para el navegador
- Información utilizada por motores de búsqueda

Ejemplo:

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi página web</title>
</head>

Ahora vamos a ver desmenuzar el head:

 <meta charset="UTF-8">

Indica la codificación de caracteres utilizada por el documento.

UTF-8

permite representar una gran cantidad de caracteres y símbolos, incluyendo caracteres utilizados en español como:
á - é - í - ó - ú - ñ

 <meta name="viewport">

Permite configurar cómo se adapta la página a diferentes tamaños de pantalla, especialmente en dispositivos móviles.

Una configuración habitual es:

 <meta name="viewport" content="width=device-width, initial-scale=1.0">

width=device-width indica que el ancho de la página debe adaptarse al ancho del dispositivo.

initial-scale=1.0 establece el nivel de zoom inicial.

 <title>

Define el título del documento que aparece, por ejemplo, en la pestaña del navegador.

<title>Mi página web</title>

### <body>

Contiene el contenido visible de la página web.

Dentro de <body> podemos colocar elementos como:

- Títulos
- Párrafos
- Imágenes
- Enlaces
- Listas
- Formularios
- Botones
- Tablas
- Secciones

Ejemplo:

<body>

    <h1>Bienvenidos</h1>
    <p>Esta es mi página web.</p>

</body>
Estructura completa

Podemos representar la estructura de esta manera:

<!DOCTYPE html>

        │
        ▼
     <html>
       │
       ├── <head>
       │     ├── <meta>
       │     ├── <meta>
       │     └── <title>
       │
       └── <body>
             ├── <h1>
             ├── <p>
             └── otros elementos


Estructura básica para recordar

Una forma sencilla de recordar la estructura es:

HTML
│
├── HEAD
│ └── Información sobre el documento
│
└── BODY
└── Contenido visible de la página
Concepto clave

Un documento HTML tiene una estructura jerárquica.

El elemento <html> contiene a <head> y <body>.

<head> contiene información sobre el documento, mientras que <body> contiene el contenido que se muestra en la página.

La estructura básica puede resumirse así:

<!DOCTYPE html> → declara HTML5

<html> → elemento raíz

<head> → información del documento

<body> → contenido visible

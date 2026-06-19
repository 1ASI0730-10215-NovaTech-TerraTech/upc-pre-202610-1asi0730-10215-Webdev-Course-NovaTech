# Introducción al Desarrollo Web

## Resumen del Curso

Este curso de **60 minutos** introduce a estudiantes de secundaria a la creación de sitios web sencillos utilizando **HTML** y **CSS**.

**¡No requiere descargas!** Solo necesitas un navegador web moderno.

- **Duración total:** 60 minutos
- **Público objetivo:** Estudiantes de 12 a 17 años sin experiencia en programación
- **Prerrequisitos:** Ninguno
- **Herramientas necesarias:** Navegador web (Chrome, Firefox, Edge o Safari)
- **Plataforma de práctica:** CodePen
- **Repositorio de código fuente:** https://tinyurl.com/49u7xbh7

---

## Secuencia de Lecciones

### Lección 1: ¿Qué es el desarrollo web? (5 minutos)
- **Descripción**: Introducción a los conceptos básicos del desarrollo web: qué es un sitio web, diferencia entre frontend y backend, y las tecnologías que se usarán (HTML y CSS). Se motiva a los estudiantes mostrando ejemplos de páginas sencillas que podrán crear.
- **Enlaces**: https://www.youtube.com/watch?v=SBVMB9KsMso
- **Consejos Clave**:
    - El desarrollo web es como construir una casa: HTML es la estructura y CSS es la decoración.
    - El frontend es lo que ves en la pantalla, el backend es lo que hace que todo funcione detrás de escena.
    - No necesitas ser un experto para empezar a crear tus propias páginas web; con HTML y CSS puedes hacer cosas increíbles desde el primer día. 

### Lección 2: Introducción a HTML (5 minutos)
- **Descripción**: HTML como lenguaje de marcado para estructurar contenido. Se explica el concepto de etiquetas, apertura y cierre, y se escribe el primer “Hola mundo” directamente en CodePen.
- **Enlaces**: https://www.youtube.com/watch?v=XEFlbn94NM0
- **Consejos Clave**:
    - HTML no es un lenguaje de programación, es un lenguaje de marcado que le dice al navegador cómo organizar el contenido.
    - Las etiquetas HTML se escriben entre `<` y `>`, y la mayoría tienen una etiqueta de cierre con `/`.
    - El primer código que escribas en HTML debe ser `<!DOCTYPE html>` para indicar que estás usando la versión más reciente del lenguaje.

### Lección 3: Estructura de un documento HTML (5 minutos)
- **Descripción**: Anatomía de una página web: `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>` y `<body>`. Los estudiantes crean la estructura vacía de su primera página.
- **Enlaces**: https://www.youtube.com/watch?v=d7rkgX1rGfU
- **Consejos Clave**:
    - El `<!DOCTYPE html>` es como el título de un libro, le dice al navegador qué tipo de documento es.
    - El `<head>` es donde van los metadatos y enlaces a estilos, mientras que el `<body>` es donde va todo lo que quieres mostrar en la página.
    - El `<title>` es lo que aparece en la pestaña del navegador, así que ponle un nombre divertido a tu página.

### Lección 4: Texto y encabezados en HTML (5 minutos)
- **Descripción**: Etiquetas de encabezado (`<h1>` a `<h6>`), párrafos (`<p>`), negrita (`<strong>`) y cursiva (`<em>`). Los estudiantes redactan un pequeño artículo con título y párrafos usando estas etiquetas.
- **Enlaces**: https://www.youtube.com/watch?v=Nmt3taroCIc
- **Consejos Clave**:
    - Recuerda: los encabezados no solo hacen el texto más grande, **organizan el contenido** como los títulos de un libro.
    - Usa `<strong>` para dar importancia y `<em>` para énfasis; evita `<b>` e `<i>`, que solo cambian la apariencia.
    - Siempre cierra los párrafos con `</p>`, es una buena costumbre.
    - No saltes niveles de encabezado: después de un `<h1>` usa `<h2>`, no `<h3>`.
- **Material de Apoyo**:
  ```html
  <h1>Lección 4</h1>
  <h2>Introducción</h2>
  <p>Hoy aprendremos sobre <strong>HTML</strong>, el lenguaje que da estructura a las páginas web.</p>
  <p> Es muy <em>fácil</em> y divertido. </p>
  <h2>Desarrollo</h2>
  <p>Los encabezados van del 1 al 6 y los párrafos se crean con la etiqueta "p". </p>

  ```

### Lección 5: Enlaces e imágenes (5 minutos)
- **Descripción**: Uso de la etiqueta `<a>` con el atributo `href` para crear hipervínculos, y de `<img>` con `src` y `alt` para insertar imágenes. Crean una página con un enlace a su sitio favorito y una imagen desde una URL pública.
- **Enlaces**: https://www.youtube.com/watch?v=JwXJwNCbLRc
- **Consejos Clave**:
    - Asegúrate de incluir `https://` en el atributo `href` para sitios externos.
    - No olvides el atributo `alt` en las imágenes: describe la imagen para accesibilidad y cuando no carga.
    - Las imágenes no se insertan, se enlazan desde una URL que termina en `.jpg`, `.png`, etc.
    - Puedes hacer una imagen clickeable rodeándola con un enlace: `<a href="..."><img src="..."></a>`.
- **Material de Apoyo**:
  ```html
  <h1> Lección 5</h1>
  <p> Lugar </p>
  <img src="https://images.pexels.com/photos/34585923/pexels-photo-34585923.jpeg" alt= "Imagen" width="300" >

  <p>Pagina web: </p>
  <a href="https://developer.mozilla.org/es/docs/Web/HTML" target="_blank">PaginaEjemplo</a>

  <h2> Video Ejemplo: </h2>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/SOWrp6ksPAQ?si=h79m78YqX0TozNpS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
  ```

### Lección 6: Listas en HTML (5 minutos)
- **Descripción**: Listas ordenadas (`<ol>`) y desordenadas (`<ul>`) con elementos `<li>`. Los estudiantes elaboran una lista de sus pasatiempos o una lista de pasos para realizar una tarea.
- **Enlaces**: https://www.youtube.com/watch?v=jA4pVl5fhmg
- **Consejos Clave**:
    - Dentro de `<ul>` o `<ol>` solo coloca elementos `<li>`.
    - Las listas ordenadas (`<ol>`) numeran automáticamente; no escribas los números a mano.
    - Puedes anidar listas para crear subcategorías, como recetas o menús.
    - Usa `<ol>` cuando el orden importa (pasos) y `<ul>` cuando no (hobbies, ingredientes).
    - El aspecto visual se personaliza después con CSS; HTML ya define la estructura.
- **Material de Apoyo**:
  ```html
  <h1>Lección 6</h1>
  <ul>
    <li>Jugar videojuegos</li>
    <li>Dibujar</li>
    <li>Escuchar música</li>
  </ul>

  <h2>Pasos para hacer un sándwich</h2>
  <ol>
    <li>Tomar dos rebanadas de pan</li>
    <li>Untar mayonesa</li>
    <li>Agregar jamón y queso</li>
    <li>Cerrar y disfrutar</li>
  </ol>

  <h3>Lista de la compra por categorías</h3>
  <ul>
    <li>Frutas
      <ul>
        <li>Manzanas</li>
        <li>Plátanos</li>
      </ul>
    </li>
    <li>Lácteos
      <ol>
        <li>Leche</li>
        <li>Queso</li>
      </ol>
    </li>
  </ul>
  ```

### Lección 7: Introducción a CSS (5 minutos)
- **Descripción**: Qué es CSS y cómo se aplica: estilos en línea y bloque `<style>`. Propiedades básicas: `color`, `background-color`, `font-size`. Los estudiantes cambian el color del texto y el fondo de su página.
- **Enlaces**: https://www.youtube.com/watch?v=adt98v97w88
- **Consejos Clave**:
- **Material de Apoyo**:
```html
<h1>Leccion 7 </h1>

<p>Mi primer texto con CSS </p>
 ```
```css
h1 {
  color : blue;
  background-color : green;
  font-size: 50px;
}

p {
  color : #ffffff;
}

body {
  background-color: black;
}
```

### Lección 8: Selectores y clases (5 minutos)
- **Descripción**: Selectores de elemento, clase (`.nombre`) e id (`#identificador`). Cómo asignarlos en HTML. Los estudiantes aplican distintos colores y estilos a elementos usando clases.
- **Enlaces**: https://www.youtube.com/watch?v=1nyPR2RRTeM
- **Consejos Clave**:
- **Material de Apoyo**:
```html
<h2>Mis Peliculas favoritas </h2>
<p class="destacado">El Seor de los Anillos </p>
<p class="destacado">Matrix </p>

<p id= "favorita-absoluta">Interestellar</p>
```

```css
.destacado {
  color: blue;
  background: purple;
}

#favorita-absoluta {
  color: blue;
  background: green;
  font-size: 30px;
}
```

### Lección 9: Modelo de caja y espaciado (5 minutos)
- **Descripción**: Concepto de margen (`margin`), relleno (`padding`) y borde (`border`). Los estudiantes ajustan los espacios entre elementos de su página para mejorar la presentación.
- **Enlaces**: https://www.youtube.com/watch?v=dwodC3ETDYM
- **Consejos Clave**:
- **Material de Apoyo**:
```html
<div class="caja-1">Soy la primera caja</div>

<div class="caja-2">Soy la segunda caja, estoy abajo</div>
```

```css
.caja-1 {
  background-color :lightblue;
  border: 3px solid black;
  padding: 20px;
  margin-bottom: 30px;
}

.caja-2 {
  background-color :blue;
  border: 3px solid black;
  padding: 20px;
}
}
```

### Lección 10: Proyecto final – Mi primera página web (15 minutos)
- **Descripción**: Actividad integradora que combina todos los conocimientos adquiridos. Los estudiantes crean una página personal con título, imagen, breve descripción y uso de buenas prácticas. Se comparte el resultado final en CodePen.
- **Enlaces**: https://www.youtube.com/watch?v=cDp6npNB4u0
- **Consejos Clave**:
    - Nombrar las clases de etiquetas en formato kebab-case.
    - Dividir `body` en las 3 etiquetas semanticas principales: `header`, `main` y `footer`.
    - Uso de variables dentro de CSS para estandarizar y facilitar el uso de propiedades.
- **Material de Apoyo**:

*Estructura básica de un proyecto HTML, implementando etiquetas semanticas*

```
<!DOCTYPE html>
<html>
<head lang="es">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>test project</title>
  <link href="style.css" rel="stylesheet">
</head>
<body>
  <header>
    <h1>encabezado</h1>
  </header>

  <main>
    <h2>contenido principal</h2>
  </main>

  <footer>
   <p>pie de página</p>   
  </footer>
</body>
</html>
```
*Estructura básica de un proyecto CSS, implementando variables*

```
:root {
  --primary-color: #2c3e50;
  --font-size: #3498db;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: var(--primary-color);
  font-size: var(--font-size);
}
```

---

## Recursos Adicionales

### Código Fuente Completo

- Repositorio GitHub: https://tinyurl.com/49u7xbh7

### Actividades Prácticas

| Nro. de Lección | Actividad | Empezar a Programar |
|----------------|-----------|---------------------|
| 1 | Conceptos básicos del desarrollo web | https://codepen.io |
| 2 | Mi primer “Hola mundo” en HTML | https://codepen.io/Fabri-Facemaker/pen/QwGQzWN |
| 3 | Estructura de la página | https://codepen.io/Fabri-Facemaker/pen/KwNQbKg |
| 4 | Encabezados y párrafos | https://codepen.io/Guillermo-Howard/pen/OPWNBGp |
| 5 | Enlaces e imágenes | https://codepen.io/Guillermo-Howard/pen/azpNRxx |
| 6 | Creando listas | https://codepen.io/Guillermo-Howard/pen/EaZKdJM |
| 7 | Primeros pasos con CSS | https://codepen.io/Breithner-Perez/pen/GgrrrqV |
| 8 | Coloreando con clases | https://codepen.io/Breithner-Perez/pen/XJppwdb |
| 9 | Jugando con márgenes y relleno | https://codepen.io/Breithner-Perez/pen/rajjgde |
| 10 | Página personal completa | https://tinyurl.com/uuj4freu |

---

## Distribución del Equipo

| Integrante | Lecciones Asignadas |
|------------|---------------------|
| Aguilar Untiveros, Rodrigo Fabrizio | Lecciones 1, 2, 3 |
| Howard Robles, Guillermo Arturo | Lecciones 4, 5, 6 |
| Perez Encarnación, Breithner Rodolfo | Lecciones 7, 8, 9 |
| Retuerto Rodríguez, Jorge Manuel | Lección 10 |

---

## Elaboración

**Universidad Peruana de Ciencias Aplicadas (UPC)**

**Facultad de Ingeniería**

**Periodo Académico:** 202610

**Curso:** 1ASI0730 - Aplicaciones Web

**NRC:** 10215

**Desarrollado por:** NovaTech - TerraTech

**Líder:** Howard Robles, Guillermo Arturo

## Integrantes del Equipo

| Apellidos y Nombres | Código |
|--------------------|---------|
| Aguilar Untiveros, Rodrigo Fabrizio | U202318309 |
| Howard Robles, Guillermo Arturo | U202222275 |
| Perez Encarnación, Breithner Rodolfo | U202418577 |
| Retuerto Rodríguez, Jorge Manuel | U202318612 |

**Fecha de Entrega:** 18/06/2026

---

**¡Gracias por completar el curso de Introducción al Desarrollo Web!**

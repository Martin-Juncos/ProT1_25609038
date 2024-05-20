# Talentos Digitales

El objetivo de esta actividad es familiarizarse con los conceptos CSS y etiquetas HTML e integración con la herramienta de versionado GIT.

## Conceptos:

- Estilos en cascada.
- Elementos básicos de CSS3.
- Uso de selectores.
- Etiquetas semánticas de Html5.

## Ejercicio 1: Uso de estilo interno

1. Crear una carpeta contenedora del proyecto Tramo 1, identificándose con tu nro de DNI.
   - Ejemplo: ProT1_23222111 (Dentro de la misma realizar las páginas, css, y demás componentes)
2. Crear un archivo `principal.html`:
   a. Insertar un estilo interno para un párrafo existente. En el caso de no contener párrafo, incorporar uno.
   b. Se emplea la etiqueta `<style>` de HTML y solamente se pueden incluir en la cabecera del documento (sólo dentro de la sección `<head>`).
   c. El estilo interno consistirá en darle un color al párrafo.
   - Ejemplo de párrafo:
   ```html
   <p>
     Somos una empresa que se dedica a la venta de relojes de mesa y pared con
     diseños únicos e innovadores. Utilizamos materia prima de calidad.
     Elaboramos productos a la medida del cliente.
   </p>
   ```

d. Comprobar en el navegador el cambio producido.

## Ejercicio 2: Hoja de estilo externa

a. Crear un archivo CSS llamado `miestilo.css`.
b. En el archivo CSS escribir el siguiente estilo para la etiqueta `<body>`:

```css
body {
  background-color: #eaf2e3;
  color: #333;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
```

c. En la página HTML se enlaza el archivo CSS externo (`miestilo.css`), mediante la etiqueta `<link>`. Ver material teórico sobre CSS.
d. Comprobar en el navegador el cambio producido.

## Ejercicio 3: Uso de clases

a. En el archivo CSS creado, utiliza el selector de clase para crear una clase en la hoja de estilo de tal manera que el párrafo quede centrado, negrita y cursivo.
b. Comprobar en el navegador el cambio producido.

## Ejercicio 4: Uso de secciones

En el archivo `principal.html`:

1. Agregar una etiqueta `<div>` que incluya el párrafo creado anteriormente.
2. Agregar otro párrafo dentro de la misma división.
3. Dar estilo a toda la división empleando una clase.
4. Comprobar en el navegador el cambio producido.

## Ejercicio 5: Uso de etiquetas semánticas de HTML

1. Modificar la estructura del archivo HTML agregando las etiquetas semánticas de HTML5:
   ```html
   <header></header>
   <nav></nav>
   <section></section>
   <footer></footer>
   ```
2. Incluir la etiqueta incorporada por HTML5 correspondiente al pie de página:
   ```html
   <footer></footer>
   ```
3. Comentar el estilo anterior en el archivo CSS e insertar este nuevo estilo:
   ```css
   header {
     background-color: #69bd45;
     color: #fff;
     text-align: center;
     padding: 20px;
   }
   section {
     padding: 20px; /* espaciado para la sección de 20 pixeles */
   }
   footer {
     background-color: #4caf50; /* Color de fondo del footer */
     color: #fff;
     padding: 20px 0;
   }
   .footer-content {
     max-width: 800px; /* Ancho máximo del contenido del footer */
     margin: 0 auto; /* Centrar el contenido del footer horizontalmente */
     text-align: center;
   }
   ```
4. Comprobar en el navegador el cambio producido.

## Ejercicio 6

a. Agregar en la página `principal.html` una etiqueta HTML5 para crear un menú de navegación:

```html
<nav></nav>
```

Agregar este estilo para la etiqueta `<nav>` dentro de tu hoja de estilos:

```css
/* Estilos para el nav y enlaces de ul y li */
nav {
  background-color: #4caf50;
  padding: 10px;
}
nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  text-align: center;
}
nav ul li {
  display: inline-block;
  margin-right: 20px;
}
nav ul li a {
  color: #fff;
  text-decoration: none;
  padding: 8px 16px;
  border-radius: 5px;
}
nav ul li a:hover {
  background-color: #2f8247;
}
```

b. En dicho menú crear enlaces a páginas externas como: Google, Yahoo y [Talentos Digitales](https://talentosdigitales.ar/).
c. Puede mejorar el estilo del menú empleando los conceptos adquiridos, por ejemplo, que cambie de color al pasar el mouse.
d. Agregar un logo de la empresa y alguna imagen con la etiqueta `<img>`. Darle estilo a la imagen:

```css
/* Estilos para las imágenes */
img {
  display: block; /* Para eliminar el espacio adicional que algunos navegadores agregan a las img. */
  margin: 0 auto; /* Centrar las imágenes horizontalmente */
  max-width: 100%; /* Asegurar que las imágenes no excedan el ancho del contenedor */
  border: 3px solid #69bd45; /* Contorno de 3px con un color verde (#69bd45) alrededor de la img.*/
  border-radius: 10px; /* Borde redondeado de 10px para suavizar el contorno */
}
```

e. También puedes seleccionar colores de tu agrado.

**Nota:** Se deja un ejemplo de la página que se ajusta a la hoja de estilos que se les proporcionó como ejemplo. Seleccionar colores pertinentes a la página creada.

**Ejemplo de página principal.html**

## Ejercicio 7: Actividad de versionado en Git- Crear repositorio Github

Después de ver el vídeo tutorial de GIT publicado (ver video) realizar las siguientes actividades:
a. Crear un repositorio git con el proyecto entregado en el tramo 1. Recuerda lo indicado en el Ejercicio 1 (Nombrar como ProT1_dni).
b. Subir el proyecto a un repositorio remoto público en Github. Para realizar la entrega de la tarea enviar un archivo de texto con el enlace al repositorio.
**Nota:** Deben estar TODOS los archivos en la carpeta. El .html, el .css y recursos (imágenes) utilizados.

**Ejemplo de enlace de entrega:**
[https://github.com/usuarioalumno/ProT1_23111111](https://github.com/usuarioalumno/ProT1_23111111)

# Manual de Usuario para Edición de Contenido

Este manual te guiará sobre cómo actualizar el contenido de tu sitio web personal (`index.html`) de manera sencilla, sin necesidad de realizar cambios complejos en el código.

**Importante:** Siempre haz una copia de seguridad del archivo `index.html` antes de realizar cualquier cambio.

---

## 1. Acceder al Archivo `index.html`

El archivo principal que contiene el contenido de tu sitio web es:
`david_medina_website/index.html`

Puedes abrir este archivo con cualquier editor de texto simple (como Notepad en Windows, TextEdit en Mac, o editores de código como VS Code).

---

## 2. Secciones Editables

A continuación, se detallan las secciones principales que puedes editar y cómo encontrarlas en el archivo `index.html`.

### 2.1. Sección Principal (Hero Section)

Esta es la primera sección que ven los visitantes.

*   **Tu Nombre:**
    *   Busca: `<h5 class="hero-sub-title"> David Medina </h5>`
    *   Edita el texto "David Medina".
*   **Roles Profesionales (Texto Animado):**
    *   Busca: `<span class="typed-strings">`
    *   Dentro de esta etiqueta, encontrarás líneas como:
        *   `<span class="type_color">Desarrollador de IA</span>`
        *   `<span class="type_color">Ingeniero de Datos</span>`
        *   `<span class="type_color">Fundador</span>`
    *   Puedes editar los textos "Desarrollador de IA", "Ingeniero de Datos", "Fundador" o añadir nuevas líneas siguiendo el mismo formato.
*   **Descripción Corta:**
    *   Busca: `<div class="header-description"> <p> +20 años en tecnología... </p> </div>`
    *   Edita el texto dentro de la etiqueta `<p>`.
*   **Imagen de Perfil:**
    *   La imagen es `assets/img/profile-pic.png`. Para cambiarla, reemplaza este archivo en la carpeta `david_medina_website/assets/img/` con tu nueva imagen. Asegúrate de que el nombre del archivo sea `profile-pic.png` y que tenga un tamaño y formato adecuados (ej. PNG, JPG).

### 2.2. Sección "Sobre Mí" (About Me)

*   **Título "Sobre Mí":**
    *   Busca: `<h5 class="about-sub-title"> Sobre Mí </h5>`
    *   Edita el texto "Sobre Mí".
*   **Título Principal:**
    *   Busca: `<h2 class="about-title"> Hola, soy David Medina </h2>`
    *   Edita el texto "Hola, soy David Medina".
*   **Subtítulo:**
    *   Busca: `<h5 class="about-title-3"> Emprendedor, Desarrollador y Líder Comunitario </h5>`
    *   Edita el texto "Emprendedor, Desarrollador y Líder Comunitario".
*   **Párrafos de Descripción:**
    *   Busca las etiquetas `<p>` dentro de `<div class="about-txt mb-30">`.
    *   Edita el contenido de estos párrafos.
*   **Botones "Descargar CV" / "Imprimir CV":**
    *   Busca: `<a href="#" class="tm-btn-2"> Descargar CV <i class="fas fa-arrow-down"></i> </a>`
    *   Para el botón "Descargar CV", puedes cambiar `#` por la URL de tu CV.
    *   Para el botón "Imprimir CV", puedes cambiar `#` por la URL de tu CV o dejarlo como está si no tienes una función de impresión específica.

### 2.3. Sección "Servicios" (Services)

*   **Títulos de Servicios:**
    *   Busca: `<h4>Inteligencia Artificial</h4>`, `<h4>Power BI</h4>`, etc.
    *   Edita el texto de cada servicio.
*   **Descripciones de Servicios:**
    *   Debajo de cada título `<h4>`, busca la etiqueta `<p>`.
    *   Edita el contenido de estos párrafos.
*   **Iconos de Servicios:**
    *   Busca: `<img src="assets/img/02_koyta_img/icon/1.png" alt="thumb">`
    *   Puedes cambiar la ruta `assets/img/02_koyta_img/icon/1.png` por la ruta de un nuevo icono si lo deseas, o reemplazar los archivos de imagen existentes en esa carpeta.

### 2.4. Sección "Habilidades" (Skills)

*   **Títulos de Habilidades:**
    *   Busca: `<h5>Inteligencia Artificial & Machine Learning <span class="pull-right">95%</span></h5>`
    *   Edita el texto de la habilidad (ej. "Inteligencia Artificial & Machine Learning").
*   **Porcentajes de Habilidades:**
    *   Dentro de la misma línea, edita el número `95%` y el atributo `data-width="95"` para ajustar la barra de progreso.

### 2.5. Sección "Contacto" (Contact)

*   **Información de Contacto (Email, Agendar Reunión, LinkedIn):**
    *   Busca las etiquetas `<h4>` para los títulos (Email, Agendar Reunión, LinkedIn).
    *   Busca las etiquetas `<span>` o `<a href="...">` para los valores correspondientes y edítalos.
*   **Formulario de Contacto:**
    *   **Título:** Busca `<h4>Enviar Mensaje</h4>`.
    *   **Placeholders:** Busca `placeholder="Nombre Completo*"` o `placeholder="Tu Email*"` y edita el texto dentro de las comillas.
    *   **Botón:** Busca `button type="submit" id="submit" class="tm-btn-2"> Enviar Mensaje </button>` y edita el texto "Enviar Mensaje".

### 2.6. Pie de Página (Footer)

*   **Texto de Copyright:**
    *   Busca: `<p>@ 2025 David Medina. Todos los derechos reservados.</p>`
    *   Edita el año o el nombre si es necesario.
*   **Enlaces a Redes Sociales:**
    *   Busca las etiquetas `<a href="...">` dentro de `<ul class="footer-social">`.
    *   Cambia la URL (`href`) por la de tus perfiles de redes sociales.

---

## 3. Modificación de la Paleta de Colores

Los colores principales del sitio web se definen mediante variables en un archivo SASS. Modificar estos colores te permite cambiar la apariencia general del sitio sin editar cada elemento individualmente.

**Archivo a Modificar:**
`david_medina_website/sass/component/_variable.scss`

**Variables de Color Clave:**

Dentro de este archivo, encontrarás un bloque `:root` con variables CSS como las siguientes:

```css
:root {
    --clr-heading: #111135;   /* Color para títulos */
    --clr-body: #565656;      /* Color para el texto principal */
    --clr-def: #ff508e;       /* Color de acento principal (ej. botones, enlaces) */
    --clr-def-2: #d450ff;     /* Color de acento secundario (ej. gradientes) */
    --clr-white: #fff;        /* Blanco */
    --clr-black: #000;        /* Negro */
    /* ... otras variables ... */
}
```

**Cómo Cambiar los Colores:**

1.  **Edita el archivo `_variable.scss`:** Abre `david_medina_website/sass/component/_variable.scss` con un editor de texto.
2.  **Modifica los valores:** Cambia los códigos hexadecimales (ej. `#ff508e`) por los nuevos colores que desees. Puedes usar cualquier formato de color CSS (RGB, HSL, nombres de color).
    *   Por ejemplo, para cambiar el color de acento principal a un azul:
        `--clr-def: #007bff;`
3.  **Compila SASS a CSS:** Después de guardar los cambios en `_variable.scss`, es **crucial** compilar los archivos SASS a CSS. Esto generará un nuevo archivo `style.css` que el navegador utilizará.
    *   **Si tienes un compilador SASS configurado:** Ejecuta el comando de compilación (ej. `sass david_medina_website/sass/style.scss david_medina_website/style.css`).
    *   **Si no tienes un compilador SASS:** Puedes editar directamente el archivo `david_medina_website/style.css`. Sin embargo, ten en cuenta que cualquier cambio futuro en los archivos SASS sobrescribirá tus ediciones directas en `style.css`. Para cambios permanentes y mantenibles, se recomienda configurar un compilador SASS.

---

## 4. Guardar Cambios

Después de realizar tus ediciones, guarda el archivo `index.html` (y `_variable.scss` si lo modificaste y compilaste SASS). Luego, puedes abrirlo en tu navegador web para ver los cambios.

Si tienes alguna duda o necesitas realizar cambios más complejos, no dudes en contactarme.
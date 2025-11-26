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

## 3. Guardar Cambios

Después de realizar tus ediciones, guarda el archivo `index.html`. Luego, puedes abrirlo en tu navegador web para ver los cambios.

Si tienes alguna duda o necesitas realizar cambios más complejos, no dudes en contactarme.
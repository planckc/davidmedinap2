# 2. Guía de Desarrollo Técnico

Este documento contiene la información técnica necesaria para trabajar en el proyecto.

## 2.1. Stack Tecnológico
*   **Lenguajes:** HTML5, CSS3, JavaScript
*   **Framework CSS:** Bootstrap
*   **Preprocesadores:** Sass (código fuente ubicado en la carpeta `sass` de la plantilla)
*   **Librerías JS:** jQuery
*   **Fuentes de Iconos:** Font Awesome, Flaticon
*   **PHP:** Para el formulario de contacto.

## 2.2. Plantilla Seleccionada
*   **Nombre:** `koyta-two`
*   **Ubicación:** `templates/koyta-personal-portfolio/Main-Koyta/koyta-two/`
*   **Razón de la elección:** Diseño moderno, limpio y con una estructura ideal para un portafolio personal.

## 2.3. Fuente del Contenido
*   **Regla de Oro:** La carpeta `Input/` y todo su contenido son **intocables**. Nunca se debe modificar ningún archivo dentro de ella.
*   La única fuente de verdad para el contenido del sitio es la carpeta `Input/DME/`.
*   Todo el contenido (textos, imágenes, CVs, etc.) debe ser extraído de `Input/DME/`. No se debe usar contenido de demostración en la versión final.

## 2.4. Comandos y Servidor
*   Al ser un proyecto estático, no requiere un proceso de construcción (build) complejo.
*   Para visualizar los cambios, simplemente abre el archivo `index.html` de la plantilla en un navegador web. Se recomienda usar una extensión de servidor en vivo (como Live Server en VSCode) para reflejar los cambios automáticamente.

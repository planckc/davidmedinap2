# 3. Registro de Decisiones del Proyecto

Este documento registra las decisiones clave tomadas durante el desarrollo del sitio web personal de David Medina.

---

### Decisión 1: Selección de la Plantilla Base

*   **Fecha:** 26 de noviembre de 2025
*   **Decisión:** Se ha seleccionado la plantilla **`koyta-two`** como la base para el desarrollo del sitio web.
*   **Justificación:**
    *   Se analizaron las dos plantillas disponibles: `koyta-one` y `koyta-two`.
    *   Aunque ambas son funcionalmente similares, `koyta-two` ofrece un diseño más moderno y una presentación más directa para un portafolio personal.
    *   La principal diferencia visual está en la sección de inicio: `koyta-two` utiliza un diseño de pantalla dividida que permite mostrar una foto de perfil junto al título profesional, lo cual es una tendencia actual que favorece la marca personal. En contraste, `koyta-one` usa un enfoque más clásico con una imagen de fondo completa.
    *   Se optó por `koyta-two` para lograr un impacto visual más limpio, organizado y contemporáneo.

---

### Decisión 2: Creación de Carpeta de Salida y Manual de Usuario

*   **Fecha:** 26 de noviembre de 2025
*   **Decisión:**
    1.  Todo el trabajo de desarrollo se realizará en una nueva carpeta de salida llamada `david_medina_website`, para no modificar nunca la plantilla original en la carpeta `templates`.
    2.  Se generará un `USER_MANUAL.md` como parte de la entrega final, que explique al usuario cómo realizar cambios básicos en su sitio web.
*   **Justificación:**
    *   Separar el trabajo en una carpeta de salida asegura que la plantilla original permanezca intacta para futuros proyectos, siguiendo las buenas prácticas de desarrollo.
    *   El manual de usuario es un entregable clave para que el cliente final (David Medina) pueda autogestionar su sitio sin necesidad de conocimientos técnicos profundos.

---

### Decisión 3: Nueva Estructura de Input y Plan Multi-idioma

*   **Fecha:** 26 de noviembre de 2025
*   **Decisión:**
    1.  La fuente de contenido del proyecto se centraliza en la carpeta `Input/DME/`. La antigua carpeta `input_dme` queda obsoleta.
    2.  Se establece como regla crítica que la carpeta `Input/` y todo su contenido son **inmutables (intocables)**.
    3.  El sitio web será multi-idioma (español, inglés, francés), pero el desarrollo inicial se centrará exclusivamente en la versión en español. La traducción se abordará en una fase posterior.
*   **Justificación:**
    *   La centralización del contenido en `Input/DME/` simplifica la gestión de los archivos de origen.
    *   La inmutabilidad de la carpeta `Input/` garantiza la integridad de los datos originales.
    *   Abordar un solo idioma primero (español) permite un desarrollo iterativo y ágil, simplificando la fase inicial del proyecto.

---

### Decisión 4: Selección del Diseño de la Página de Inicio

*   **Fecha:** 26 de noviembre de 2025
*   **Decisión:** Se ha seleccionado el archivo **`index-6.html`** como la plantilla definitiva para la página de inicio.
*   **Justificación:**
    *   Se realizó un análisis de las 9 variantes de `index-*.html` disponibles. Las 3 mejores opciones para el perfil profesional fueron:
        1.  **`index-6.html` (Parallax + Texto Animado):** Combina un fondo con efecto de profundidad y una animación de "máquina de escribir" para el título. Es la opción más dinámica y efectiva para comunicar roles técnicos clave.
        2.  **`index-2.html` (Solo Parallax):** Más sobrio que la opción 1, ofrece un diseño elegante y moderno sin la animación de texto.
        3.  **`index.html` (Estático):** La opción más limpia y minimalista, pero potencialmente demasiado simple para un perfil tecnológico.
    *   Se eligió `index-6.html` por ser la que mejor equilibra profesionalismo con un toque dinámico y tecnológico, permitiendo destacar las habilidades del perfil de forma inmediata y atractiva.

---

### Decisión 5: Reorganización de la Carpeta `Input/DME`

*   **Fecha:** 26 de noviembre de 2025
*   **Decisión:** Se reorganizará la carpeta `Input/DME` para agrupar todo el contenido por idioma y separar los recursos compartidos.
*   **Justificación:** La estructura anterior mezclaba archivos de diferentes idiomas y tipos. La nueva estructura (`es/`, `en/`, `fr/`, `shared/`) mejora la claridad, la escalabilidad y facilita la localización del sitio en el futuro, siguiendo las mejores prácticas de gestión de contenido.


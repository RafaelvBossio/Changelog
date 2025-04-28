# Changelog Personalizado con HTML y CSS

Este repositorio contiene un ejemplo de un Changelog estilizado utilizando únicamente HTML y CSS. Es una alternativa sencilla para aquellos proyectos que no requieren una generación automática de Changelog pero desean una presentación visual atractiva de sus cambios.

## Estructura del Proyecto

El proyecto consiste en los siguientes archivos:

* `index.html`: Contiene la estructura HTML del Changelog.
* `style.css`: Define los estilos CSS para la presentación del Changelog.

## Cómo Utilizarlo

1.  **Descarga los archivos:** Clona este repositorio o descarga los archivos `index.html` y `styles.css`.
2.  **Edita `index.html`:** Abre el archivo `index.html` con un editor de texto. Dentro de la sección `<body>`, encontrarás la estructura básica para las entradas del Changelog. Cada entrada sigue un patrón similar:

    ```html
    <div class="version">
        <h3>Versión 1.0.0 - <span class="date">2025-04-26</span></h3>
        <ul>
            <li><span class="feature">Nuevo:</span> Descripción de la nueva funcionalidad.</li>
            <li><span class="fix">Corrección:</span> Descripción de la corrección de errores.</li>
            <li><span class="improvement">Mejora:</span> Descripción de la mejora realizada.</li>
            <li><span class="breaking">Cambio drástico:</span> Descripción del cambio que puede romper la compatibilidad.</li>
        </ul>
    </div>
    ```

# Changelog Personalizado con HTML y CSS

Este repositorio contiene un ejemplo de un Changelog estilizado utilizando únicamente HTML y CSS. Es una alternativa sencilla para aquellos proyectos que no requieren una generación automática de Changelog pero desean una presentación visual atractiva de sus cambios.

## Estructura del Proyecto

El proyecto consiste en los siguientes archivos:

* `index.html`: Contiene la estructura HTML del Changelog.
* `styles.css`: Define los estilos CSS para la presentación del Changelog.

## Cómo Utilizarlo

1.  **Descarga los archivos:** Clona este repositorio o descarga los archivos `index.html` y `styles.css`.
2.  **Edita `index.html`:** Abre el archivo `index.html` con un editor de texto. Dentro de la sección `<body> <main>`, encontrarás la estructura básica para las entradas del Changelog. Cada entrada sigue un patrón similar:

    ```html
    <section id="v1.0.0">
        <div>
            <h2>Version 1.0.0</h2>
            <div class="release-info">
                <p>Release date: <span>2023-01-01</span></p>
                <p>Initial release of the application.</p>
            </div>
        </div>
        <ul>
            <li><a href="#"><i class="fas fa-check"></i>Feature A implemented.</a></li>
            <li><a href="#"><i class="fas fa-check"></i>Feature B implemented.</a></li>
            <li><a href="#"><i class="fas fa-bug"></i>Bug fix for issue #1.</a></li>
        </ul>
    </section>
    ```
[Enlace al Proyecto](https://roadmap.sh/projects/changelog-component)

Este repositorio contiene un ejemplo de un Changelog estilizado utilizando únicamente HTML y CSS...

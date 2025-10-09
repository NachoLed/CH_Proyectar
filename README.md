# Proyectar Construcciones - Landing Page

Este repositorio contiene el proyecto **Proyectar Construcciones**, una landing page desarrollada como entrega para el curso de Desarrollo Web de CoderHouse.
El foco está en la correcta maquetación, adaptabilidad y estética, cumpliendo con los siguientes requisitos:

<img width="1920" height="917" alt="image" src="https://github.com/user-attachments/assets/a038aaee-c32b-49c8-95e4-0fa9da650da8" />


## Características principales

- **Maquetación avanzada** en todos los archivos HTML, utilizando **Flexbox**, **Grid** y **Bootstrap** (solamente su sistema de columnas y hasta 3 componentes permitidos) para la vista desktop.
- **Adaptabilidad móvil**: al menos dos páginas presentan un diseño específico para dispositivos móviles usando media queries, Flexbox, Grid y el sistema de columnas de Bootstrap. La apariencia varía claramente entre desktop y mobile.
- **No se utilizan clases utilitarias de Bootstrap** para la maquetación (por ejemplo: `d-flex`, `flex-row`, `text-center`, `border`, `text-light`, etc.).
- **Todo el CSS de maquetación es propio**, evitando clases de Bootstrap para la disposición y estructura.
- **GitHub Pages** está activo para visualización y corrección online.

## Estructura del proyecto

El proyecto está compuesto principalmente por archivos **HTML** y **CSS**.

### Páginas y requisitos cumplidos

| Página           | Maquetación Desktop | Maquetación Mobile | Sistema de maquetación utilizado |
|------------------|:------------------:|:-------------------:|:-------------------------------:|
| `index.html`     |        ✔️          |        ✔️          | Flexbox                        |
| `projects.html`  |        ✔️          |        ✔️          | Grid                           |
| `contacts.html`  |        ✔️          |        ❌          | Flexbox + Sistema de columnas de Bootstrap |

- **index.html** y **contacts.html**: Se adaptan a mobile con media queries y muestran una disposición distinta respecto a desktop.
- **projects.html**: Utiliza Grid para la disposición en desktop.
- **contacts.html**: Utiliza Flexbox y el sistema de columnas de Bootstrap para la disposición.
- **Bootstrap**: Sólo se emplean componentes permitidos, sin clases utilitarias para maquetado.
- **CSS**: Toda la estructura y disposición está realizada con hojas de estilo propias.

## Visualización

Puedes ver el proyecto en línea a través de [GitHub Pages](https://nacholed.github.io/CH_Proyectar/).

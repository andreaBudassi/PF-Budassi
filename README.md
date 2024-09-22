# Proyecto: @burger_sessions 🍔

Este proyecto fue desarrollado como parte del curso de HTML y CSS en CoderHouse. A lo largo del desarrollo, se aplicaron conceptos clave como diseño responsivo con media queries, grid y flexbox, así como la implementación de **Bootstrap** para mejorar la estructura del proyecto. 

## Tecnologías Utilizadas

- **HTML5**: Para la estructura y el contenido del sitio.
- **CSS3**: Para el diseño visual del sitio, con un enfoque en **grid**, **flexbox** y **media queries** para lograr un diseño responsivo.
- **Bootstrap**: Se utilizó para implementar componentes predefinidos y asegurar una mejor compatibilidad móvil.
- **Sass**: Utilizado como preprocesador de CSS para mejorar la gestión de los estilos del proyecto. Con Sass, se optimizó el código utilizando variables, mixins y funciones, lo que permitió un mantenimiento más sencillo y una estructura modular de los estilos. Además, Sass facilitó la creación de un diseño escalable y organizado mediante la utilización de parciales, agrupando estilos en archivos específicos para una mejor legibilidad y reutilización del código.
- **Google Fonts**: Se importaron fuentes personalizadas desde Google Fonts.
- **Diseño Responsivo**: Adaptación del sitio para dispositivos móviles, tabletas y escritorios.
- **GitHub**: Repositorio del proyecto.

## Estructura del Proyecto

El proyecto tiene la siguiente estructura de carpetas y archivos:
├── css 
│ └── style.css
├── scss
│ ├── base
│ │   └── _reset.scss 
│ │   └── _fonts.scss
│ ├── components
│ │   └── _buttons.scss
│ │   └── _navbar.scss
│ │   └──_maps.scss
│ │   └──_menu.scss
│ │   └── _texts.scss
│ │   └── _mediaqueries.scss
│ │   └── _forms.scss 
│ ├── layout
│ │   └──_header.scss
│ │   └── _main.scss
│ │   └── _footer.scss
│ ├── utils
│ │   └── _variables.scss
│ │   └── _mixins.scss
│ └── style.scss
├── fonts 
│ └── DimitriSwank.woff2 
│ └── DimitriSwank.woff 
├── img 
│ └── imagenes
├── pages 
│ └── sucursales.html 
│ └── contacto.html 
│ └── nosotros.html 
│ └── nuestrasBurgers.html 
├── index.html 
└── README.md

### Archivos Principales

1. **index.html**: Página principal con información introductoria sobre `@burger_sessions` y botones de navegación a otras secciones del sitio.
2. **nuestrasBurgers.html**: Página dedicada al menú de hamburguesas de la empresa.
3. **nosotros.html**: Información sobre la historia de la empresa.
4. **sucursales.html**: Información sobre las sucursales de la empresa.
5. **contacto.html**: Formulario de contacto para comunicarse con la empresa.
6. **style.css**: Archivo CSS donde se incluye todo el estilo personalizado del proyecto, incluyendo diseño responsivo.

## Diseño Responsivo

El diseño del sitio se adapta automáticamente a diferentes tamaños de pantalla. Esto se logró utilizando **media queries** que ajustan el contenido de manera eficiente en dispositivos móviles y tabletas. Se usó **Flexbox** y **Grid** para organizar el contenido de una manera flexible y fluida.

### Media Queries Aplicadas

```css
@media (max-width: 768px) {
    /* Reglas específicas para pantallas móviles */
}
```

### Uso de Bootstrap
Bootstrap se implementó principalmente en la estructura del header, utilizando su sistema de rejilla para una disposición fluida en diferentes tamaños de pantalla. Además, se usó el botón de navegación `navbar-toggler` para mejorar la experiencia en dispositivos móviles.

También se utilizó un **carrusel de Bootstrap** en la página del menú de la hamburguesería para mostrar las hamburguesas de manera dinámica y atractiva.

## Cómo Ejecutar el Proyecto
Clonar el repositorio:
git clone https://github.com/andreaBudassi/burgerSessions.git

## Créditos
Este proyecto fue creado como parte de las actividades del curso HTML y CSS en CoderHouse, aplicando los conocimientos adquiridos sobre maquetación web y diseño responsivo.

<p align="center">
  <img src="img/logo.png" alt="Logo de Burger Sessions" width="200">
</p>

# Proyecto Módulo 3 - SmartBudget

Este es mi proyecto final para el módulo "Desarrollo de la Interfaz de Usuario Web". Es una *landing page* responsiva para una aplicación de finanzas llamada SmartBudget.


## Tecnologías utilizadas
- HTML5
- SASS (SCSS)
- CSS3 (Flexbox)
- Bootstrap 4.6
- Font Awesome 5 (Íconos)

## Justificación Metodológica

Para armar este proyecto, tomé las siguientes decisiones prácticas basándome en lo aprendido en el curso:

**1. Organización de SASS**
En lugar de usar el patrón 7-1 completo, que me parecía demasiado grande para una sola página, decidí simplificar la estructura en tres carpetas principales:
- `/base`: Para reset, tipografías y variables de color.
- `/layout`: Para las secciones grandes de la página (header, hero, footer).
- `/components`: Para los elementos pequeños que se repiten (botones, tarjetas).

**2. Metodología BEM**
Utilicé BEM (Block, Element, Modifier) para nombrar mis clases de CSS. Esto me ayudó mucho a mantener el orden en el código y asegurarme de que mis estilos no chocaran con los que trae Bootstrap por defecto.

**3. Uso de Bootstrap**
Aproveché Bootstrap 4 principalmente para la estructura responsiva (el sistema de grillas) y para los componentes más complejos de armar desde cero, como el menú de navegación que colapsa en celulares, el carrusel de testimonios y la ventana modal del botón "Ver demo". 

**4. Diseño visual**
Me basé en el boceto base del proyecto, pero decidí aplicar una paleta de colores con tonos claros y azules, además de incorporar íconos gratuitos, para que la página se viera más limpia y parecida a una aplicación financiera real.

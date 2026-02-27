# SmartBudget - Proyecto Módulo 3

## Objetivo
Desarrollar una landing page responsiva para SmartBudget aplicando:
- HTML5 semántico
- Metodología CSS: BEM
- SASS modular
- Layout responsivo priorizando Flexbox
- Integración de Bootstrap 4 (componentes)

## Metodología CSS (BEM)
Se utilizó BEM para mantener orden y escalabilidad:
- Bloque: sb-hero
- Elemento: sb-hero__title
- Modificador: sb-card--dark

## Estructura SASS
Estructura modular por carpetas:
- base: variables, mixins, reset, globals
- layout: secciones principales
- components: piezas reutilizables (botón, card, form, mock)

Se emplea @use/@forward (estándar actual de Sass), evitando la deprecación de @import.

## Layout Responsivo
- Secciones implementadas principalmente con Flexbox (display:flex + wrap).
- Bootstrap se usa para navbar, cards, grid (row/col) y componentes (modal/carrusel/form).

## Bootstrap 4 (componentes usados)
- Navbar (header)
- Cards (soluciones)
- Carousel (testimonios)
- Modal (demo)
- Form controls (contacto)

## Compilación SASS
Compilación en modo watch, sin sourcemap:
sass --watch scss/main.scss css/styles.css --no-source-map
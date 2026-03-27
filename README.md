# Cafe Aurora

Sitio web de una cafeteria de especialidad, desarrollado como proyecto final del curso de **Desarrollo Web** en CoderHouse.

## Demo

[Ver sitio en vivo](https://mcornejov.github.io/coderhouse-dw-final/)

## Paginas

| Pagina | Descripcion |
|--------|-------------|
| `index.html` | Inicio: carousel hero, sobre nosotros, especialidades, experiencia, musica |
| `pages/nosotros.html` | Nosotros: historia, filosofia, equipo y valores |
| `pages/menu.html` | Menu: cafes, pasteleria, origenes, maridajes, recomendados del barista |
| `pages/galeria.html` | Galeria: fotos del espacio, eventos, actividades y cifras |
| `pages/contacto.html` | Contacto: formulario, preguntas frecuentes, ubicacion y horarios |

## Tecnologias

- HTML5 semantico
- SASS/SCSS (arquitectura modular 7-1)
- CSS3 compilado desde SCSS
- Bootstrap 5.3 (CDN — navbar y carousel)
- Google Fonts (Playfair Display + Lato)
- Responsive design (mobile-first, media queries propias)
- SEO on-page (meta description, Open Graph, keywords)

## Estructura

```
├── index.html
├── pages/
│   ├── nosotros.html
│   ├── menu.html
│   ├── galeria.html
│   └── contacto.html
├── scss/
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   ├── _reset.scss
│   │   ├── _typography.scss
│   │   └── _utilities.scss
│   ├── components/
│   │   ├── _navbar.scss
│   │   ├── _buttons.scss
│   │   ├── _cards.scss
│   │   ├── _carousel.scss
│   │   ├── _forms.scss
│   │   ├── _accordion.scss
│   │   ├── _blockquote.scss
│   │   ├── _tables.scss
│   │   └── _page-hero.scss
│   ├── layout/
│   │   ├── _grid.scss
│   │   ├── _sections.scss
│   │   ├── _footer.scss
│   │   └── _aside.scss
│   ├── pages/
│   │   ├── _home.scss
│   │   ├── _nosotros.scss
│   │   ├── _menu.scss
│   │   ├── _galeria.scss
│   │   └── _contacto.scss
│   ├── vendors/
│   │   └── _bootstrap-overrides.scss
│   └── main.scss
├── css/
│   └── styles.css
└── img/
    ├── hero.jpg
    ├── local.jpg
    ├── logo.svg
    ├── producto-1.jpg
    ├── producto-2.jpg
    └── ambiente.mp3
```

## SCSS

Arquitectura modular SASS con:

- **Variables**: paleta de colores, tipografia, breakpoints, spacing
- **Mixins**: `respond-to()`, `button-variant()`, `flex-center()`, `card-hover()`, `section-heading()`
- **Nesting** con `&` para BEM y pseudo-clases
- **@extend** con placeholders (`%btn-base`)
- **@each** para generar clases dinamicas de color y espaciado
- **Operadores** aritmeticos para escalas de spacing
- **@if/@else** en mixins condicionales
- **Animaciones**: `fadeInUp`, `fadeInLeft`, `scaleIn` con soporte `prefers-reduced-motion`

## SEO

- Meta descriptions en todas las paginas
- Open Graph tags (og:title, og:description, og:image, og:type)
- Keywords relevantes por pagina
- Alt text descriptivo en todas las imagenes
- Estructura semantica (header, nav, main, section, article, aside, footer)
- Atributos `lang`, `aria-*`, y heading hierarchy correcta

## Creditos

- Imagenes: [Freepik](https://www.freepik.es/)
- Musica: "Autumn Is Coming (Piano)" — Monument_Music ([Pixabay](https://pixabay.com/music/))

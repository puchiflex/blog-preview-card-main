# Frontend Mentor - Blog preview card solution

Esta es mi solución al desafío de [Blog preview card en Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

El objetivo era replicar el diseño de una tarjeta de previsualización de blog, logrando que sea responsiva y que tenga los estados activos (hover) correctos.

### Screenshot

<img width="1365" height="595" alt="Captura de pantalla 2026-02-24 220233" src="https://github.com/user-attachments/assets/24431e55-e8ed-43bc-95be-70b5331379ab" />


#### Mi solución

### Links

- Solution URL: [GitHub](https://github.com/puchiflex/blog-preview-card-main)


### Built with

- Semantic HTML5 markup
- CSS custom properties (Variables)
- Flexbox
- Neo-brutalism design (sombras sólidas)

### What I learned

Lo más importante que aprendí en este proyecto fue a lidiar con el **Box Model** y los elementos de línea. Aprendí que para que un elemento respete los márgenes `top` y `bottom` sin dejar de estar alineado con otros elementos, la propiedad `display: inline-block` es clave:

```css
.learning {
    display: inline-block;
    margin: .9rem 0;
    padding: .4rem .55rem;
}
```
### AI Collaboration

Para este proyecto utilicé a **Gemini** como mentor de aprendizaje. En lugar de pedirle que escribiera el código por mí, lo usé para:
- **Debugging:** Entender por qué los márgenes verticales no funcionaban en elementos `inline` (como la etiqueta `<strong>`).
- **Conceptos de CSS:** Aprender la diferencia entre `inline`, `block` e `inline-block`.
- **Diseño:** Recibir pistas sobre cómo lograr una sombra sólida de estilo neo-brutalista usando `box-shadow` con un valor de blur en 0.

## Author

- Frontend Mentor - [@tu-usuario-de-FM]
- GitHub - [tu-usuario-de-github]

## Acknowledgments

Un agradecimiento a la comunidad de Frontend Mentor por el desafío.

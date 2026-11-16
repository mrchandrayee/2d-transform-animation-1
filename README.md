# 2D Transform Animation — Complete Runnable Project

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/2d-transform-animation-1/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

Recreated from the supplied 15.8-second screen recording titled **2D Transform Animation**.

## Effects visible in the video

1. **Translate** — `transform: translate(60px, -30px);`
2. **Rotate** — `transform: rotate(360deg);`
3. **Scale** — `transform: scale(1.5);`
4. **Skew** — `transform: skew(15deg, 10deg);`
5. **Combined** — `translateY(-30px) rotate(15deg) scale(1.2)`
6. **Auto Animation** — `animation: spin 3s linear infinite;`

## Extracted CSS snippets

### Translate
```css
.translate:hover {
    transform: translate(60px, -30px);
}
```

### Rotate
```css
.rotate:hover {
    transform: rotate(360deg);
}
```

### Scale
```css
.scale:hover {
    transform: scale(1.5);
}
```

### Skew
```css
.skew:hover {
    transform: skew(15deg, 10deg);
}
```

### Combined
```css
.combo:hover {
    transform: translateY(-30px)
               rotate(15deg)
               scale(1.2);
}
```

### Auto Animation
```css
.auto {
    animation: spin 3s linear infinite;
}

@keyframes spin {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
}
```

## Run
Extract the ZIP and open `index.html` in a modern browser. No npm install, build process, or external dependency is required.

## Project files
- `index.html` — six transform demonstrations and visible code examples
- `style.css` — dark visual theme, gradient tiles, hover transforms and spin keyframes
- `script.js` — intentionally minimal; CSS handles all interactions
- `README.md` — extracted snippets and run instructions

## Source fidelity
The CSS transform declarations shown in the recording are transcribed above. The recording does not show the complete page HTML or all base styling declarations, so the surrounding page structure, responsive layout, and visual styling have been reconstructed to provide a complete runnable project. The transform values and labels follow the visible source.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)

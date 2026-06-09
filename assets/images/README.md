# Beatriz Terreu — Portfolio Profesional

Portfolio de Beatriz Terreu.

🌐 **Live site:** [beatrizterreu.github.io/portfolio](https://beatrizterreu.github.io/portfolio/)

## Stack

HTML5 · CSS3 (custom, no frameworks) · Vanilla JavaScript

## Estructura

```
/
├── index.html              # Página principal
├── projects/
│   ├── colvin.html         # Caso de estudio: Colvin
│   ├── talenty.html        # Caso de estudio: Talenty
│   ├── theknot.html        # Caso de estudio: The Knot Worldwide
│   └── devmatters.html     # Caso de estudio: DevMatters
├── assets/
│   └── images/             # Imágenes del portfolio
├── styles/
│   ├── main.css            # Estilos principales + design tokens
│   └── projects.css        # Estilos para páginas de proyectos
└── .github/
    └── workflows/
        └── deploy.yml      # CI/CD → GitHub Pages
```

## Despliegue automático

Cualquier push a `main` despliega automáticamente en GitHub Pages.

**Para configurar:**
1. Ve a Settings → Pages en tu repositorio
2. En "Source" selecciona **GitHub Actions**
3. Guarda los cambios

A partir de entonces, cada commit en `main` → nuevo deploy automático. ✅

## Añadir imágenes reales

Para reemplazar los placeholders por imágenes reales:

1. Agrega las imágenes en `/assets/images/`
2. En los archivos HTML, reemplaza los `<div class="...placeholder">` por:
```html
<img src="../assets/images/tu-imagen.jpg" alt="Descripción" loading="lazy" />
```

## Contacto

📧 bterreu@gmail.com
💼 [linkedin.com/in/beatrizterreu](https://www.linkedin.com/in/beatrizterreu/)
🐙 [github.com/beatrizterreu](https://github.com/beatrizterreu)

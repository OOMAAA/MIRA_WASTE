# MIRA WASTE — Sitio Web

## Estructura de archivos

```
mirawaste/
├── index.html          ← Página principal
├── css/
│   └── styles.css      ← Todos los estilos
├── js/
│   └── main.js         ← Interactividad (partículas, animaciones, scroll)
├── img/
│   └── favicon.svg     ← Ícono del sitio
└── README.md
```

## Funcionalidades implementadas

- **Partículas animadas** de fondo (canvas, red neuronal)
- **Typing effect** en el hero
- **Contadores animados** para estadísticas al hacer scroll
- **Scroll reveal** suave para cada sección
- **Tilt 3D** sutil en cards al hover
- **Navbar** que cambia al hacer scroll + menú mobile hamburguesa
- **Línea de scan** ambiental en el hero
- **WhatsApp** como canal de contacto principal (sin formulario)
- **SEO completo**: meta tags, Open Graph, Twitter Card, JSON-LD
- **Responsive** desde 320px hasta 4K
- **Accesibilidad**: roles ARIA, labels, reduced-motion

## Para publicar

1. Reemplaza el número de WhatsApp en `index.html` (busca `56912345678`)
2. Reemplaza `hola@mirawaste.cl` con el email real
3. Actualiza los enlaces de LinkedIn
4. Agrega imágenes reales en la carpeta `/img/`
5. Sube a tu hosting (Netlify, Vercel, GitHub Pages, etc.)

## Tecnologías

- HTML5 semántico
- CSS3 (variables, grid, animaciones, glassmorphism)
- Vanilla JavaScript (ES6+, IntersectionObserver, Canvas API)
- Google Fonts (Rajdhani + Inter + Space Mono)

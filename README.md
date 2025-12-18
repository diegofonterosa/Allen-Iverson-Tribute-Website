# 🏀 Allen Iverson - The Answer | Sitio Web Biográfico

Sitio web responsive dedicado a la leyenda del baloncesto Allen Iverson, desarrollado con HTML5 y CSS3 puro. Presenta biografía completa, estadísticas de carrera, galería multimedia y diseño moderno optimizado para todos los dispositivos.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green)
![Netlify](https://img.shields.io/badge/Deployed%20on-Netlify-00C7B7)

## 📋 Descripción

Sitio web tributo a Allen Iverson desarrollado completamente con tecnologías frontend (HTML5 y CSS3 puro, sin frameworks). El proyecto implementa diseño responsive mobile-first, navegación fluida mediante anclas internas, integración multimedia con YouTube, galería de imágenes con efectos hover y estructura semántica optimizada para SEO y accesibilidad.

## ✨ Características

- 📱 **Diseño Responsive**: Adaptable a móviles, tablets y escritorio
- 🎨 **CSS3 Avanzado**: Flexbox, Grid, transiciones y animaciones
- 📄 **HTML5 Semántico**: Estructura clara con etiquetas semánticas
- 🖼️ **Galería de Imágenes**: 8 fotografías históricas con overlays informativos
- 🎥 **Videos Integrados**: 3 videos de YouTube embebidos responsivamente
- 📊 **Tabla de Estadísticas**: Datos completos de su carrera en la NBA
- 🔍 **SEO Optimizado**: Meta tags, keywords y structured data
- ♿ **Accesibilidad**: Alt text, labels, contraste adecuado
- ⚡ **Optimización**: Lazy loading en imágenes, assets comprimidos
- 🎯 **Navegación Suave**: Menú sticky con scroll suave

## 🛠️ Tecnologías utilizadas

- **HTML5** - Estructura y contenido semántico
- **CSS3** - Estilos, layouts (Flexbox/Grid), animaciones
- **Font Awesome 6.4.0** - Iconos de redes sociales
- **Google Fonts** (si aplica) - Tipografía personalizada
- **Netlify** - Hosting y despliegue continuo

## 📦 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación ni dependencias

## 🚀 Instalación y uso

### Ver online
🌐 **Demo en vivo**: [https://proyecto-html-css-prometeo.netlify.app/](https://proyecto-html-css-prometeo.netlify.app/)

### Ejecutar localmente

1. **Clonar el repositorio**
```bash
git clone https://github.com/diegofonterosa/allen-iverson-tribute.git
cd allen-iverson-tribute
```

2. **Abrir en navegador**
```bash
# Opción 1: Doble clic en index.html
# Opción 2: Usar Live Server en VS Code
# Opción 3: Servidor local simple con Python
python -m http.server 8000
```

3. **Navegar a**
```
http://localhost:8000
```

## 📁 Estructura del proyecto
```
allen-iverson-tribute/
│
├── index.html              # Página principal
├── styles.css              # Hoja de estilos principal
├── assets/                 # Recursos multimedia
│   ├── favicon-32x32.png
│   ├── allen-iverson-dribbling...webp
│   ├── iverson-universidad.jpg
│   ├── iverson-llegada-phili.jpeg
│   ├── iverson-allstar.jpg
│   ├── iverson-madre.jpeg
│   ├── iverson-lue-foto.jpg
│   ├── iverson-mvp.webp
│   ├── iverson-usa.jpeg
│   └── iverson-denver.jpeg
└── README.md               # Este archivo
```

## 🎯 Secciones del sitio

### 1. Hero Section
Imagen destacada de Allen Iverson con efecto visual impactante

### 2. Biografía
- **Introducción**: Impacto cultural de Iverson
- **Primeros años**: Infancia en Hampton, Virginia
- **Llegada a la NBA**: Draft 1996, Philadelphia 76ers
- **Carrera profesional**: 14 años en la NBA, MVP 2001
- **Impacto cultural**: Revolución del estilo urbano en la NBA
- **Vida personal**: Desafíos y vulnerabilidad pública
- **Legado**: Influencia duradera en jugadores y cultura

### 3. Estadísticas de Carrera
Tabla completa con datos destacados:
- 914 partidos jugados
- 26.7 puntos por partido (promedio)
- 11 selecciones All-Star
- MVP de la NBA 2001
- 4 títulos de máximo anotador

### 4. Videos
- Mejores jugadas de su carrera
- Entrevista polémica "Practice" (2002)
- Recepción del trofeo MVP

### 5. Galería
8 fotografías históricas con efectos hover y descripciones:
- Universidad de Georgetown
- Draft NBA 1996
- All-Star Game
- Momentos icónicos de carrera

### 6. Contacto
Formulario con campos de nombre, email y mensaje

## 💻 Características técnicas implementadas

### HTML5
- ✅ Estructura semántica (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- ✅ Meta tags SEO (description, keywords, author)
- ✅ Viewport meta para responsive
- ✅ Lazy loading en imágenes de galería
- ✅ Atributos alt descriptivos
- ✅ Links externos con `target="_blank"` y `rel="noopener"`

### CSS3
- ✅ Flexbox para layouts
- ✅ CSS Grid para galería
- ✅ Variables CSS (custom properties)
- ✅ Media queries para responsive design
- ✅ Transiciones y animaciones suaves
- ✅ Pseudo-elementos (::before, ::after)
- ✅ Overlays con efectos hover
- ✅ Gradientes y sombras

### Accesibilidad
- ✅ Contraste de colores WCAG AA
- ✅ Alt text en todas las imágenes
- ✅ Labels asociados a inputs
- ✅ Estructura de headings jerárquica (h1, h2, h3)
- ✅ Focus visible en elementos interactivos

### Performance
- ✅ Imágenes optimizadas (WebP para hero)
- ✅ Lazy loading implementado
- ✅ CSS y HTML minificados en producción
- ✅ CDN para Font Awesome

## 🎨 Paleta de colores
```css
:root {
  --primary-color: #1d428a;      /* Azul 76ers */
  --secondary-color: #ed174c;    /* Rojo 76ers */
  --accent-color: #ffc72c;       /* Dorado */
  --text-dark: #1a1a1a;
  --text-light: #ffffff;
  --background: #f5f5f5;
  --overlay: rgba(0, 0, 0, 0.7);
}
```

## 📱 Responsive Breakpoints
```css
/* Mobile: 320px - 767px (por defecto) */
/* Tablet: 768px - 1023px */
@media (min-width: 768px) { ... }

/* Desktop: 1024px+ */
@media (min-width: 1024px) { ... }
```

## 🔧 Posibles mejoras futuras

- [ ] Implementar JavaScript para scroll suave
- [ ] Añadir modo oscuro/claro
- [ ] Integrar backend para formulario de contacto
- [ ] Añadir más estadísticas con gráficos (Chart.js)
- [ ] Implementar lightbox para galería
- [ ] Añadir sección de logros y premios
- [ ] Comparativa con otros jugadores históricos
- [ ] Timeline interactiva de su carrera
- [ ] Integración con API de NBA Stats
- [ ] Blog o sección de noticias

## 📖 Aprendizajes del proyecto

Este proyecto permitió practicar y consolidar:
- Estructura HTML5 semántica profesional
- Layouts complejos con Flexbox y Grid
- Diseño responsive mobile-first
- Optimización de imágenes y performance
- Accesibilidad web (a11y)
- SEO on-page básico
- Integración de contenido multimedia
- Best practices de frontend

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 👤 Autor

**Diego Pérez Fonterosa**
- GitHub: [@diegofonterosa](https://github.com/diegofonterosa)
- LinkedIn: [Diego Pérez Fonterosa](https://linkedin.com/in/diegoperezfonterosa)
- Instagram: [@diegofonterosa](https://instagram.com/diegofonterosa)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

## 📞 Contacto

Para preguntas o sugerencias:
- Email: diegofonterosa@gmail.com
- LinkedIn: https://linkedin.com/in/diegoperezfonterosa

## 🙏 Créditos

- **Imágenes**: NBA Photos, Getty Images (uso educativo)
- **Videos**: YouTube (embebidos con permiso de la plataforma)
- **Iconos**: Font Awesome
- **Inspiración**: Pasión por el baloncesto y respeto por la leyenda de Allen Iverson

---

⭐ Si te gustó este proyecto, ¡dale una estrella en GitHub!

**#NBA #AllenIverson #TheAnswer #WebDevelopment #HTML5 #CSS3**
```

---

html5
css3
responsive-design
frontend
web-development
nba
tribute-page
mobile-first
flexbox
css-grid
netlify
portfolio-project

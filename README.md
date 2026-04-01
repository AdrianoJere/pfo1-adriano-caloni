# Portafolio Personal – Adriano Caloni

![HTML5](https://img.shields.io/badge/HTML5-markup-orange?logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-styles-blue?logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-yellow?logo=javascript)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-Syne_+_JetBrains_Mono-red?logo=google)
![Vercel](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)

🌐 **Demo:** [Ver en Vercel](https://pfo1-adriano-caloni.vercel.app/)
📁 **Repo:** [Ver en GitHub](https://github.com/AdrianoJere/pfo1-adriano-caloni)

---

## Sobre el proyecto

PFO1 de la materia **Desarrollo de Sistemas Web (Front End)** – IFTS N.º 29.

La consigna era hacer una landing page de portafolio personal con HTML y CSS. Aproveché para armar algo que realmente me represente: tengo más de 7 años trabajando en tecnología, actualmente como Líder de Soporte Digital en Banco Coinag y cofundador de Alcana Labs, una emprendimiento de desarrollo web que arrancamos con mi socia. El primer producto que lanzamos es Mentor+, una plataforma de mentorías académicas que ya está en producción en mentormas.com.ar.

El diseño es dark tech, con tipografía geométrica y detalles en verde neón. Sin frameworks, todo CSS puro con variables, Grid, Flexbox y animaciones.

---

## 🗂️ Estructura

```
pfo1-adriano-caloni/
├── index.html
├── README.md
├── css/
│   └── styles.css
└── img/
    ├── avatar.jpg
    ├── mentor-logo.png
    ├── alcana-logo.png
    ├── coinag-logo.png
    └── lasegunda-logo.png
```

---

## 🛠️ Tecnologías

| Tecnología | Uso |
| --- | --- |
| HTML5 semántico | Estructura completa con `header`, `nav`, `main`, `footer` |
| CSS3 | Variables, Grid, Flexbox, animaciones, media queries |
| JavaScript vanilla | Menú mobile y fade-in con IntersectionObserver |
| Google Fonts | Syne (títulos) + JetBrains Mono (código/etiquetas) |

---

## ✅ Checklist – PFO1

### Estructura del Proyecto
- [x] `index.html` en la raíz
- [x] Carpeta `css/` con `styles.css`
- [x] Carpeta `img/` con recursos gráficos
- [x] `README.md` con descripción y checklist

### Repositorio y Publicación
- [x] Repositorio en GitHub creado y proyecto subido
- [x] Publicado en Vercel
- [x] 🌐 **Demo:** [Ver en Vercel](https://pfo1-adriano-caloni.vercel.app/)

### Google Fonts
- [x] Enlace incluido en el `head`
- [x] Tipografía aplicada en todo el sitio
- [x] **¿Por qué estas fuentes?**  
  Trabajo todos los días en un entorno de desarrollo — terminales, editores, documentación técnica. Quería que el portafolio se sintiera como parte de ese mundo. Syne es una display font geométrica que se usa mucho en diseño tech moderno. JetBrains Mono la conozco bien porque es la fuente que uso en el IDE, así que ponerla en etiquetas y tags del portafolio fue una decisión natural.

### HTML
- [x] `<!DOCTYPE html>` y `lang="es"`
- [x] Metaetiquetas `charset` y `viewport`
- [x] Título descriptivo
- [x] CSS y Google Fonts vinculados en el `head`
- [x] Nav con 5 enlaces (Sobre mí, Proyectos, Habilidades, Contacto, Películas)
- [x] `#sobre-mi` con párrafo e imagen
- [x] `#tarjetas` con 4 tarjetas en Grid
- [x] `#habilidades` con tabla de stack técnico
- [x] `#contacto` con formulario (Nombre, Apellido, Email, Teléfono + submit)
- [x] `#peliculas` con 3 películas
- [x] Footer con redes y contacto
- [x] 5 comentarios explicativos con ideas de mejora futura

### CSS
- [x] `styles.css` con estilos personalizados
- [x] Selectores por clases e IDs
- [x] Google Fonts aplicada en todos los elementos
- [x] **¿Grid o Flexbox?**  
  Usé CSS Grid para la sección de proyectos con `repeat(3, 1fr)` — nunca lo había usado antes de esta materia y me resultó mucho más potente que Flexbox para layouts de 2 dimensiones. Para el resto (hero, formulario, habilidades) seguí con Flexbox que ya manejaba. Combinar los dos fue lo más interesante del trabajo.
- [x] Tablas, botones, enlaces y formularios personalizados
- [x] Unidades relativas: `rem`, `%`, `vh`, `vw`, `clamp()`
- [x] **¿Qué animaciones implementaste?**  
  Cinco en total: hover en tarjetas con elevación (`translateY`), ticker corriendo con las tecnologías del stack, anillo giratorio alrededor del avatar, fade-in de secciones al hacer scroll con IntersectionObserver, y un badge pulsante de disponibilidad. Las que más me gustaron son el ticker y el fade-in — el ticker porque le da vida a la hero section sin ser invasivo, y el fade-in porque aprendí a usar IntersectionObserver que no conocía.

### Consideraciones Adicionales
- [x] Responsivo en mobile, tablet y desktop
- [x] Atributos `alt` en todas las imágenes, `label` en todos los campos
- [x] Comentarios describiendo decisiones y mejoras futuras en cada sección

---

## 🔗 Links

- [LinkedIn](https://www.linkedin.com/in/adriano-jeremias-caloni/)
- [GitHub](https://github.com/settings/profile)
- [Mentor+](https://mentormas.com.ar/login)
- [Alcana Labs](https://www.instagram.com/alcanalabs/)

---

*PFO1 – Desarrollo de Sistemas Web (Front End) · IFTS N.º 29 · 2026*

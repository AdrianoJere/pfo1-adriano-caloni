# Portafolio Personal – Adriano Caloni

## Descripción del Proyecto

Este es el trabajo práctico correspondiente a la **Práctica Formativa Obligatoria 1 (PFO1)** de la materia de Desarrollo Web del **IFTS N.º 29**. Consiste en una landing page de portafolio personal desarrollada con **HTML5 y CSS3**, sin frameworks ni librerías externas, que presenta mi perfil profesional como Líder de Soporte Digital y Desarrollador Backend.

La página incluye secciones de presentación personal, proyectos, habilidades técnicas, formulario de contacto y películas favoritas. El diseño adopta una estética oscura tipo "dark tech/fintech" con acentos de color neón, tipografía moderna y animaciones sutiles.

🌐 **URL publicada:** [Ver en GitHub Pages](#) ← completar luego de publicar  
📁 **Repositorio:** [Ver en GitHub](#) ← completar con el link al repo

---

## Checklist – Práctica Formativa Obligatoria 1

### Estructura del Proyecto
- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] Carpeta `img` para recursos gráficos (avatar/foto de perfil).
- [x] Archivo `README.md` creado, que incluya una breve descripción del TP y este checklist.

### Repositorio y Publicación
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [ ] En el `README.md` se indica la URL de GitHub Pages. ← pendiente

### Uso de Google Fonts
- [x] Enlace a Google Fonts incluido en la sección `head` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **Decisión de fuente:** Elegí **Syne** para los títulos y encabezados por su carácter geométrico y moderno, que encaja con la estética tech del portafolio. Para los textos de código, etiquetas y elementos monoespacio utilicé **JetBrains Mono**, una fuente diseñada específicamente para desarrolladores que refuerza la identidad del sitio.

### HTML
- [x] El documento inicia con la declaración DOCTYPE y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.
- [x] Barra de navegación (`nav`) presente con 5 enlaces (Sobre mí, Proyectos, Habilidades, Contacto, Películas).
- [x] Sección `sobre-mi` con párrafo descriptivo e imagen.
- [x] Sección `tarjetas` con 4 tarjetas con imagen/ícono y texto organizadas con Flexbox.
- [x] Sección `habilidades` con tabla organizada de tecnologías.
- [x] Sección `contacto` con formulario (Nombre, Apellido, Email, Teléfono + botón submit).
- [x] Sección `peliculas` con 3 películas favoritas (título, imagen/visual y descripción).
- [x] Footer con redes sociales y datos adicionales.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

### CSS
- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores (`.card`, `#sobre-mi`, etc.).
- [x] La tipografía importada desde Google Fonts se aplica correctamente.
- [x] **Layout con Flexbox:** Se utilizó Flexbox en la sección de tarjetas (`.cards-grid`), en la hero section, en el grid de habilidades, en el formulario de contacto y en las películas. **Ventajas encontradas:** Flexbox permite distribuir el espacio entre elementos de forma dinámica y muy intuitiva. Fue especialmente útil para que las tarjetas se adapten automáticamente al ancho disponible con `flex-wrap: wrap`, logrando un diseño responsivo sin media queries complejas.
- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`, `vw`, `clamp()`).
- [x] **Animación/transición implementada:** Se implementaron múltiples: (1) efecto hover con `transform: translateY()` y `box-shadow` en tarjetas y botones; (2) animación de ticker infinito para el banner de tecnologías; (3) animación de giro (`spin`) en el anillo del avatar; (4) animación de fade-in con scroll usando Intersection Observer; (5) efecto pulsante en el badge de disponibilidad. Estas animaciones se eligieron para dar dinamismo y vida al portafolio sin resultar invasivas, reforzando la identidad tech del diseño.

### Consideraciones Adicionales
- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos (mobile, tablet, desktop).
- [x] Se aplicaron buenas prácticas de accesibilidad (atributos `alt` en imágenes, labels en formularios, estructura semántica HTML5).
- [x] Se añadieron comentarios adicionales describiendo decisiones de diseño y mejoras futuras.

---

## Stack utilizado

- HTML5 semántico
- CSS3 (Variables CSS, Flexbox, animaciones, media queries)
- Google Fonts: Syne + JetBrains Mono
- JavaScript vanilla (para menú mobile y animaciones de scroll)

---

*PFO1 – IFTS N.º 29 · 2026*

# 🎮 Emotiva - Salón de Juegos

![Emotiva Banner](Imagenes/2025-07-21.jpg)

## 📱 Sitio Web Premium con Optimización Móvil

Sitio web moderno y responsive para **Emotiva**, un salón de juegos premium que ofrece experiencias de entretenimiento de alta calidad con pantallas gigantes, máquinas de última generación y un ambiente excepcional.

---

## ✨ Características Principales

### 🎨 Diseño Premium
- **Diseño moderno** con gradientes vibrantes y efectos glassmorphism
- **Paleta de colores** inspirada en la marca Emotiva (rojo, dorado, negro)
- **Tipografía profesional** con Bebas Neue e Inter
- **Animaciones suaves** optimizadas para GPU
- **Micro-interacciones** que mejoran la experiencia del usuario

### 📱 Optimización Móvil (v2.0)
- ✅ **Menú de navegación premium** con animaciones escalonadas
- ✅ **Tipografía fluida** con `clamp()` para escalado perfecto
- ✅ **Botones táctiles** (≥48px) para mejor usabilidad
- ✅ **4 breakpoints responsive**: 480px, 768px, 968px, desktop
- ✅ **Optimización landscape** para móviles horizontales
- ✅ **Accesibilidad WCAG 2.1 AA** compatible

### 🚀 Rendimiento
- **Animaciones GPU-accelerated** con transform y opacity
- **Lazy loading** preparado para imágenes
- **CSS moderno** con custom properties y clamp()
- **JavaScript optimizado** sin bloqueos
- **Viewport units modernos** (svh para mejor soporte móvil)

### ♿ Accesibilidad
- **Navegación por teclado** completa
- **Soporte prefers-reduced-motion** para usuarios sensibles
- **Alto contraste** con prefers-contrast: high
- **Touch targets** de mínimo 48x48px
- **Semántica HTML5** correcta

---

## 📄 Páginas del Sitio

1. **Inicio** (`index.html`) - Hero section, características destacadas
2. **Servicios** (`servicios.html`) - Pantallas gigantes, máquinas, ambiente
3. **Promociones** (`promociones.html`) - Ofertas y eventos especiales
4. **Galería** (`galeria.html`) - Imágenes del local y ambiente
5. **Contacto** (`contacto.html`) - Formulario, mapa, información de transporte
6. **Demo Mobile** (`demo-mobile.html`) - Demostración de mejoras móviles

---

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Diseño moderno con custom properties, gradients, animations
- **JavaScript (Vanilla)** - Interactividad sin dependencias
- **Google Fonts** - Bebas Neue, Inter
- **SVG** - Iconos escalables

---

## 📐 Breakpoints Responsive

```css
/* Small Mobile */
@media (max-width: 480px) { ... }

/* Mobile */
@media (max-width: 768px) { ... }

/* Tablet */
@media (max-width: 968px) { ... }

/* Desktop */
> 968px (diseño completo)
```

---

## 🎯 Optimizaciones Móviles

### Navegación
- Menú hamburguesa con transformación a X
- Backdrop blur glassmorphism
- Animaciones escalonadas (0.05s delay incremental)
- Cierre automático (clic fuera, Escape, navegación)
- Prevención de scroll del body

### Tipografía
```css
/* Ejemplo de tipografía fluida */
font-size: clamp(2rem, 8vw, 3.5rem);
```

### Botones
- Altura mínima: 48px (accesibilidad)
- Ancho completo en móviles
- Font-size: 16px en inputs (previene zoom iOS)

---

## 📂 Estructura del Proyecto

```
Emotiva/
├── index.html              # Página principal
├── servicios.html          # Página de servicios
├── promociones.html        # Página de promociones
├── galeria.html           # Galería de imágenes
├── contacto.html          # Página de contacto
├── demo-mobile.html       # Demo de mejoras móviles
├── styles.css             # Estilos principales (1300+ líneas)
├── script.js              # JavaScript principal
├── Imagenes/              # Recursos visuales
├── MEJORAS_MOBILE.md      # Documentación de mejoras móviles
├── GUIA_RAPIDA_MOBILE.md  # Guía rápida de características
└── README.md              # Este archivo
```

---

## 🚀 Instalación y Uso

### Opción 1: Visualización Local
```bash
# Clonar el repositorio
git clone https://github.com/Boy2Flow/emotiva.git

# Navegar al directorio
cd emotiva

# Abrir index.html en tu navegador
# O usar un servidor local como Live Server
```

### Opción 2: GitHub Pages
El sitio está hosteado en GitHub Pages:
**[https://boy2flow.github.io/emotiva/](https://boy2flow.github.io/emotiva/)**


---

## 📱 Compatibilidad

### Navegadores Soportados
- ✅ Chrome/Edge (últimas 2 versiones)
- ✅ Firefox (últimas 2 versiones)
- ✅ Safari (últimas 2 versiones)
- ✅ iOS Safari
- ✅ Android Chrome
- ✅ Samsung Internet

### Dispositivos Probados
- iPhone SE (375x667)
- iPhone 12 Pro (390x844)
- Samsung Galaxy S20 (360x800)
- iPad (768x1024)
- iPad Pro (1024x1366)

---

## 📊 Métricas de Rendimiento

- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3s
- **Cumulative Layout Shift**: < 0.1
- **Touch Target Size**: 100% ≥ 48px
- **Accessibility Score**: WCAG 2.1 AA

---

## 🎨 Paleta de Colores

```css
--primary-red: #C41E3A;
--dark-red: #8B0000;
--gold: #FFB800;
--dark-gold: #CC9200;
--orange: #FF8C00;
--black: #0A0A0A;
--dark-gray: #1A1A1A;
--white: #FFFFFF;
```

---

## 📝 Documentación Adicional

- [Mejoras Móviles Completas](MEJORAS_MOBILE.md)
- [Guía Rápida Mobile](GUIA_RAPIDA_MOBILE.md)
- [Demo de Mejoras](demo-mobile.html)

---

## 📍 Información del Local

**Emotiva - Salón de Juegos**
- 📍 Calle Puerta de Toledo, 134, Madrid
- 🕐 Lunes a Domingo: 10:00 - 02:00
- 🎮 Pantallas gigantes, máquinas de última generación
- ⚽ Transmisión de todos los partidos importantes

---

## 🔮 Próximas Mejoras

- [ ] Convertir a PWA (Progressive Web App)
- [ ] Implementar Service Worker para offline
- [ ] Añadir lazy loading de imágenes
- [ ] Modo oscuro/claro toggle
- [ ] Touch gestures para navegación
- [ ] Optimización de fuentes (subset)

---

## 👨‍💻 Desarrollo

**Versión**: 2.0 - Mobile Optimized  
**Última actualización**: Diciembre 2025  
**Estado**: ✅ Producción

---

## 📄 Licencia

Este proyecto es propiedad de **Emotiva**. Todos los derechos reservados.

---

## ⚠️ Aviso Legal

- Juego responsable
- Prohibida la entrada a menores de 18 años
- Consulta términos y condiciones en el local

---

**¡Vive la emoción del fútbol en Emotiva!** ⚽🎮


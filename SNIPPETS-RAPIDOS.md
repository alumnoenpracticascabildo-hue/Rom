# ⚡ Snippets Rápidos - Copy & Paste

Fragmentos de código para personalizar los widgets sin editar HTML completo.

---

## 🎨 Cambiar Paleta de Colores

### Azul Completo
Reemplaza en **todos los widgets**:

```css
/* Buscar y reemplazar (Ctrl+H en editor) */

De:  #0d1f3c → A: #TU_AZUL_OSCURO
De:  #1a56db → A: #TU_AZUL_MEDIO
De:  #3b82f6 → A: #TU_AZUL_CLARO
De:  #f8f9fc → A: #TU_GRIS_FONDO
```

**Ejemplo (Verde corporativo):**
```css
--primary-dark: #0f5c42;     /* Verde oscuro */
--primary-blue: #2a9f6e;     /* Verde medio */
--light-blue: #4ab38f;       /* Verde claro */
```

---

## ✏️ Cambiar Textos (Búsqueda Rápida)

### Hero Section
```html
<!-- Buscar estos textos y cambiar -->

<h1>Rigor de peritación al servicio de la justicia</h1>
<p class="tagline">La evidencia no miente</p>
<p>Director de la Escuela Nacional de Peritos...</p>

<div class="stat-number" data-target="25">25</div>
<div class="stat-label">AÑOS EXPERIENCIA</div>
```

### Service Cards
```html
<h3 class="service-title">Peritación de Automoción</h3>
<p class="service-description">Análisis exhaustivo...</p>
```

### Testimonials
```html
<p class="testimonial-text">"Trabajo impecable..."</p>
<h4>Juan Carlos</h4>
<p>Abogado Especializado</p>
```

---

## 🖼️ Cambiar Imágenes

### En Hero Section
```html
<!-- Buscar: -->
<img src="https://via.placeholder.com/500x600/0d1f3c/ffffff?text=Romana+Alvarez"
     alt="Romana Álvarez Perito">

<!-- Reemplazar por tu URL: -->
<img src="https://tu-dominio.com/romana-alvarez.jpg"
     alt="Romana Álvarez Perito">
```

---

## 🎬 Ajustar Velocidad de Animaciones

### En cualquier `<style>`

```css
/* Buscar y cambiar duración (en segundos) */

/* Más rápido (0.3s en lugar de 0.8s) */
animation: slideInLeft 0.3s ease-out;

/* Más lento (1.5s en lugar de 0.8s) */
animation: slideInLeft 1.5s ease-out;

/* Sin animación (al instante) */
animation: none;
```

### Delay de Animaciones

```css
/* Reducir delay (sin stagger) */
animation-delay: 0s;

/* Aumentar delay (entrada más lenta) */
animation-delay: 0.5s;
```

---

## 📱 Ajustar Breakpoints Responsive

```css
/* Cambiar breakpoint de móvil (actual 768px) */

/* Buscar: */
@media (max-width: 768px) {

/* Cambiar a: */
@media (max-width: 1024px) {    /* Más grande */
@media (max-width: 600px) {     /* Más pequeño */
```

---

## 🔤 Cambiar Tipografía

### Usar Google Fonts Diferentes

```css
/* Actual en widgets */
font-family: 'Playfair Display', serif;  /* Títulos */
font-family: 'Inter', sans-serif;        /* Cuerpo */

/* Alternativas profesionales */
font-family: 'Montserrat', sans-serif;
font-family: 'Poppins', sans-serif;
font-family: 'Lato', sans-serif;
font-family: 'Roboto', sans-serif;

/* Serif alternativas */
font-family: 'Lora', serif;
font-family: 'Merriweather', serif;
font-family: 'Crimson Text', serif;
```

**Nota:** Google Fonts se cargan automáticamente en los estilos CSS.

---

## 📝 Cambiar Textos de Botones

```html
<!-- Hero & CTA buttons -->

<!-- Buscar: -->
<a href="#contacto" class="btn btn-primary">Solicitar Peritación</a>

<!-- Reemplazar por: -->
<a href="#contacto" class="btn btn-primary">Agendar Cita</a>
<a href="#contacto" class="btn btn-primary">Contactar Ahora</a>
<a href="#contacto" class="btn btn-primary">Más Información</a>
```

---

## 🎯 Cambiar URLs de Enlaces

```html
<!-- Buscar todas las: -->
href="#contacto"

<!-- Reemplazar por: -->
href="#formulario"      /* Si cambiaste el ID */
href="/contacto"        /* URL absoluta */
href="https://tu-mail.com"  /* Email directo */
```

---

## 🔢 Cambiar Números (Stats)

```html
<!-- En Stats Counter widget -->

<div class="stat-number" data-target="5000">5000</div>
<!-- Cambiar 5000 a: -->
<div class="stat-number" data-target="10000">10000</div>

<div class="stat-value">PERITACIONES</div>
<!-- Cambiar etiqueta -->
<div class="stat-value">PROYECTOS</div>
```

---

## 📦 Cambiar Numero de Columnas

```css
/* En Service Cards (actual: 3 columnas) */

/* Buscar: */
grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));

/* Cambiar a 2 columnas: */
grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));

/* O a 4 columnas: */
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
```

---

## 🎨 Cambiar Espaciado (Padding/Margin)

```css
/* Más espacio (padding aumentado) */
padding: 100px 40px;  → padding: 120px 60px;

/* Menos espacio (padding reducido) */
padding: 100px 40px;  → padding: 60px 20px;

/* Cambiar gap entre elementos */
gap: 40px;            → gap: 20px;   /* Más cerca */
gap: 40px;            → gap: 60px;   /* Más lejos */
```

---

## 🔴 Cambiar Color de Botones

```css
/* Botón Primario */

/* Buscar: */
.btn-primary {
  background: var(--light-blue);
}

/* Reemplazar el background: */
background: #ff6b6b;        /* Rojo */
background: #ffc93c;        /* Amarillo */
background: #00d99f;        /* Verde */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);  /* Gradiente */
```

---

## ⚙️ Cambiar Bordes (Border-Radius)

```css
/* Más redondeado */
border-radius: 8px;   → border-radius: 16px;
border-radius: 12px;  → border-radius: 20px;

/* Menos redondeado */
border-radius: 12px;  → border-radius: 4px;

/* Bordes cuadrados */
border-radius: 0px;
```

---

## 🌥️ Cambiar Sombras

```css
/* Sombra más fuerte */
box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
→ box-shadow: 0 10px 40px rgba(0, 0, 0, 0.2);

/* Sombra más suave */
box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
→ box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);

/* Sin sombra */
box-shadow: none;
```

---

## 🎬 Cambiar Easing de Animaciones

```css
/* Actual */
transition: all 0.3s ease;

/* Alternativas */
transition: all 0.3s ease-in;        /* Lento al inicio */
transition: all 0.3s ease-out;       /* Lento al final */
transition: all 0.3s ease-in-out;    /* Lento en ambos */
transition: all 0.3s linear;         /* Velocidad constante */
transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);  /* Custom */
```

---

## 📧 Cambiar Form ID (Formspree)

```javascript
/* En Contact Form widget */

/* Buscar: */
fetch('https://formspree.io/f/YOUR_FORM_ID', {

/* Reemplazar YOUR_FORM_ID por tu Form ID real: */
fetch('https://formspree.io/f/mzvwdkpq', {
```

---

## 🔗 Cambiar Links

```html
<!-- Buscar href actual -->
<a href="#contacto">Texto</a>

<!-- Cambiar destino -->
<a href="/nueva-pagina">Texto</a>
<a href="https://ejemplo.com">Texto</a>
<a href="mailto:email@ejemplo.com">Email</a>
<a href="tel:+34666777888">Llamar</a>
```

---

## 📐 Cambiar Ancho Máximo

```css
/* En cualquier contenedor */

/* Actual */
max-width: 1200px;

/* Más ancho */
max-width: 1400px;

/* Menos ancho */
max-width: 1000px;

/* Pantalla completa */
max-width: 100%;
```

---

## 🎓 Cambiar Peso de Fuente

```css
/* Más bold */
font-weight: 700;   → font-weight: 900;

/* Menos bold */
font-weight: 600;   → font-weight: 500;

/* Light */
font-weight: 300;

/* Normal */
font-weight: 400;
```

---

## 📊 Quick Reference

| Elemento | Buscar | Reemplazar |
|----------|--------|-----------|
| Color primario | `#0d1f3c` | Tu color |
| Color acento | `#3b82f6` | Tu color |
| Títulos | `Playfair Display` | Tu font |
| Cuerpo | `Inter` | Tu font |
| Padding | `100px 40px` | Tu espaciado |
| Border-radius | `8px` | Tu curvatura |
| Sombra | `0 4px 20px rgba...` | Tu sombra |
| Animación | `0.8s ease-out` | Tu timing |

---

## ✅ Checklist de Cambios

```
□ Cambié los colores principales
□ Actualicé los textos
□ Cambié las imágenes
□ Ajusté animaciones si fue necesario
□ Cambié los links
□ Configuré Formspree (si usas formulario)
□ Probé en móvil
□ Probé en navegadores diferentes
```

---

**Tip:** Usa la herramienta "Buscar y Reemplazar" (Ctrl+H) de tu editor para cambios globales.

**Nota:** Siempre haz una copia antes de cambios masivos.

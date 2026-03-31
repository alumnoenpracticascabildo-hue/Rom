# Widgets Romana Álvarez - Versión 2 (Enhanced)

## 📋 Descripción General

Versión mejorada de los widgets HTML para el sitio de Romana Álvarez con **animaciones avanzadas**, **efectos de hover mejorados**, **stagger animations** y **micro-interacciones** profesionales.

Cada widget es **100% independiente** y puede ser usado como contenedor HTML en Elementor Free sin requerir CSS externo.

---

## 📦 Widgets Disponibles

### **01 - Hero Section v2** (`01-hero-section-v2.html`)
**Sección hero con animaciones avanzadas y efectos visuales.**

#### ✨ Características:
- Floating background elements con animaciones suaves
- Reveal animations secuenciales para titulo, subtítulo y botones
- Botones con efecto ripple dinámico (mouse tracking)
- Stats badge con bounce animation
- Foto con efecto float en hover
- Responsive 2-column → 1-column

#### 🎨 Animaciones:
- `slideInLeft` - Contenido entra desde la izquierda
- `slideInRight` - Imagen entra desde la derecha
- `scaleX` - Decorative underline en el título
- `bounceInUp` - Stats badge con bounce curvado
- `floatImage` - Foto flota en hover

#### 📱 Breakpoints:
- Desktop: 2 columnas
- Tablet (1024px): 1 columna
- Mobile (768px): Ajustes de padding y font size
- Small (480px): Hero sin altura mínima

---

### **02 - Logos Band v2** (`02-logos-band-v2.html`)
**Marquee animado de colaboraciones y medios.**

#### ✨ Características:
- Marquee continuo sin saltos (duplicado de logos)
- Pausa en hover suave
- Gradient overlays en los extremos (fade effect)
- Logos con escala y desaturación en hover
- Animación de carga escalonada
- Support para touch events (mobile)

#### 🎨 Animaciones:
- `marquee` - Desplazamiento continuo 40s
- `fadeInDown` - Label aparece desde arriba
- `fadeInUp` - Logos aparecen desde abajo (stagger)
- `scaleX`, `grayscale` - Efectos en hover

#### 📱 Responsive:
- Mask gradients para fade suave
- Gap y tamaños adaptativos
- Toque intuitivo en mobile

---

### **03 - Servicios v2** (`03-servicios-v2.html`)
**Grid de 6 servicios con hover effects profesionales.**

#### ✨ Características:
- Grid 3 columnas → 2 → 1 (responsive)
- Animaciones stagger (0.1s delay entre cards)
- Glow effect radial en hover
- Icon rotatorio con escala en hover
- Service bar que expande de 2rem a 100%
- Background gradient animado

#### 🎨 Animaciones:
- `slideBackground` - Background mueve 20s infinito
- `fadeInDown` - Header aparece desde arriba
- `fadeInUp` - Cards entran escalonadas
- `scaleX` - Service bar expande con easing bouncy

#### 🎯 Hover State:
```
- Card: translateY(-8px) + glow radial
- Icon: scale(1.15) rotate(10deg) + gradient bg
- Bar: width 100% + gradient + box-shadow
```

---

### **04 - Cobertura Nacional v2** (`04-cobertura-nacional-v2.html`)
**Sección de cobertura geográfica con cards interactivas.**

#### ✨ Características:
- Grid 4 cards → 2 → 1 (responsive)
- Animaciones stagger escalonadas (0.3s a 0.6s)
- Madrid alliance section separada con layout flexible
- Dark booking banner con icon rotatoria
- Glow effects avanzados en cards
- Icons que rotan en hover

#### 🎨 Animaciones:
- `float` - Fondo flota suavemente (15s, 18s inverso)
- `slideInLeft` - Header texto entra desde izquierda
- `fadeInUp` - Cards entran con delay escalonado
- `scaleX` - Link underline se expande

#### 🎯 Interacciones:
```
- Card hover: translateY(-6px) + glow + border cambio
- Icon hover: rotate(10deg) + scale(1.1)
- Link hover: color blanco + underline 100%
```

---

### **05 - Testimonios v2** (`05-testimonios-v2.html`)
**Grid de testimonios con ratings y avatares.**

#### ✨ Características:
- Grid 3 cards → 2 → 1
- Stagger animations (0.2s, 0.3s, 0.4s)
- Quote mark decorativo (::after pseudo-element)
- Avatar con gradient background
- Stars con color dorado
- Smooth color transitions

#### 🎨 Animaciones:
- `fadeInDown` - Header aparece
- `fadeInUp` - Cards entran escalonadas
- Quote mark: color cambio en hover (slate-200 → blue-light)

#### 🎯 Hover Effects:
```
- Card: translateY(-8px) + glow + border
- Avatar: scale(1.15) + box-shadow mejorada
- Autor: color cambio a blue
- Quote: opacity y color aumentan
```

---

### **06 - Contacto v2** (`06-contacto-v2.html`)
**Formulario de contacto con validación y animaciones.**

#### ✨ Características:
- 2 columnas (info + form) → 1 columna mobile
- Form fields con stagger animations
- Focus effects con gradient background
- Ripple effect en submit button (mouse tracking)
- Validación en tiempo real
- Mensajes de éxito/error animados

#### 🎨 Animaciones:
- `slideInLeft` - Sección izquierda
- `slideInRight` - Formulario
- `fadeInUp` - Form fields escalonados (0.1s-0.6s)
- `pulse` - Ripple en submit button
- `slideInDown` - Mensajes de feedback

#### ✅ Validación:
```javascript
- Campos requeridos
- Email format check (regex)
- Checkbox privacidad
- Mensajes con timeout (6s)
```

---

### **07 - Secciones Extra v2** (`07-seccion-extra-v2.html`)
**Combinación de Bio + Metodología + Comunidad + Escuela.**

#### A. Bio Section
- 2 columnas con quote y cards
- Bounce animation en quote icon
- Bio cards con hover elevation
- Stagger en cards (0.3s-0.6s)

#### B. Metodología
- 3 pasos con números grandes
- Conectores con gradiente
- Icons que rotan en hover
- Step connector desaparece en mobile

#### C. Comunidad
- 2 columnas → 1 mobile
- Imagen con hover float
- Button con reveal animation

#### D. Escuela
- Background gradient oscuro con floats
- Feature list con stagger (0.1s-0.4s)
- 4 stat cards con animación escalonada
- Botones con reveal y slide

#### 🎨 Animaciones Especiales:
- `bounce` - Quote icon flota 2s infinito
- `float` - Backgrounds flota (12s-18s)
- Stagger completo en cada sección

---

## 🎨 Sistema de Colores

```css
--navy: #0d1f3c           /* Color principal oscuro */
--blue: #1a56db           /* Azul medio */
--blue-light: #3b82f6     /* Azul claro */
--blue-accent: #60a5fa    /* Azul accent */
--white: #ffffff          /* Blanco */
--off-white: #f8f9fc      /* Blanco off */
--slate-50-900: Escala completa de grises
```

---

## 🔤 Tipografía

```
Títulos (h1, h2, h3):
  Font: Playfair Display
  Peso: 700 (Bold)
  Estilo: Italic para <em>

Cuerpo (p, span, label):
  Font: Inter
  Peso: 300-700 (según contexto)
  Tamaño: clamp() para responsive
```

---

## ✨ Efectos Globales

### Transiciones
```css
--transition: .3s cubic-bezier(.4,0,.2,1)
--transition-slow: .6s cubic-bezier(.4,0,.2,1)
```

### Animaciones Reutilizables
- `slideInLeft/Right` - Entrada lateral
- `slideInUp/Down` - Entrada vertical
- `fadeInUp/Down` - Fade + movimiento
- `fadeInScale` - Fade + scale
- `scaleX` - Expansión horizontal
- `bounceInUp` - Bounce curvado
- `float` - Flotación suave
- `bounce` - Rebote continuo
- `pulse` - Ripple effect
- `expandWidth` - Ancho expandible

---

## 📱 Estrategia Responsive

### Breakpoints
- **1024px**: Grids 2 columnas
- **768px**: Grids 1 columna, padding reducido
- **480px**: Font sizes reducido, mobile-first layout

### Características Mobile
- Menú hamburguesa (navbar no visible)
- Flex directions cambian
- Paddings y gaps reducidos
- Font sizes con clamp()
- Mask gradients para fade efectos

---

## 🚀 Implementación en Elementor

### Paso 1: Copiar el HTML completo

### Paso 2: En Elementor
1. **Elementor → Editar página**
2. **Agregar elemento → HTML**
3. **Pegar código completo**
4. **Full Width → Sin padding**

### Paso 3: Personalización
- Variables CSS en la sección `<style>` al principio
- Colores: Buscar y reemplazar hex codes
- Textos: Directamente en HTML
- URLs: Buscar enlaces y actualizar

---

## 🔧 Personalización Rápida

### Cambiar Color Primario
```css
/* En <style>, reemplazar: */
--blue: #1a56db  /* Cambiar este valor */
```

### Cambiar Tipografía
```css
--font-serif: 'Tu Font', Georgia, serif;
--font-sans: 'Tu Font', Arial, sans-serif;
```

### Ajustar Velocidad de Animaciones
```css
animation: slideInLeft 0.8s ease-out;
                      ^^^ cambiar a 0.5s, 1s, etc
```

### Modificar Delays
```css
animation-delay: 0.2s;  /* Cambiar escalonamiento */
```

---

## 📊 Características Técnicas

- ✅ Self-contained (sin dependencias externas)
- ✅ No requiere Custom CSS en Elementor
- ✅ Responsive mobile-first
- ✅ Accessible (roles, labels, alt text)
- ✅ Performance optimizado (no heavy JS)
- ✅ Cross-browser compatible
- ✅ Smooth animations (60fps)
- ✅ GPU accelerated transforms

---

## 🎯 Próximas Fases

### Fase 2: Integración Stripe + Calendar
- Sistema de reservas de peritaciones
- Página separada con calendario interactivo
- Integración con Stripe para pagos
- Confirmación automática de reservas

### Fase 3: Analytics & Optimización
- Tracking de conversiones
- A/B testing de CTAs
- Performance monitoring
- SEO optimization

---

## 📞 Soporte

Para personalización avanzada o bugs reportados:
- Revisar el código en GitHub
- Contactar al desarrollador
- Tickets en sistema de issues

---

**Última actualización:** 31 de Marzo 2026
**Versión:** 2.0 Enhanced
**Estado:** Producción
